# Chest X-ray Disease Classification Using Convolutional Neural Networks

## Overview
This project investigates the application of Convolutional Neural Networks (CNNs) for automating the classification of chest X-ray images into various disease categories. The goal is to enhance diagnostic accuracy and efficiency in medical imaging.

## Dataset
The project leverages the **NIH Chest X-ray Dataset**, which contains over **112,000** labeled X-ray images. The dataset includes **14 disease categories** such as:
- Atelectasis
- Cardiomegaly
- Consolidation
- Edema
- And more

## Models
Several deep learning models were employed, including:

- **Base CNN**: A custom-designed convolutional neural network.
- **VGG16**: A pre-trained model known for its depth and performance.
- **ResNet50**: A deeper architecture with residual connections.
- **MobileNetV2**: A lightweight model optimized for mobile and resource-constrained environments.

## Methodology
### Data Preprocessing:
- Resizing images to **224x224 pixels**.
- Normalizing pixel values.
- Applying data augmentation techniques such as **rotation, flipping, zooming, and brightness adjustments**.

### Model Training:
- Using the **Adam optimizer** and **binary cross-entropy loss** for multi-label classification.
- Implementing **early stopping** and **learning rate scheduling** to prevent overfitting.

### Evaluation Metrics:
- **Accuracy**
- **AUC-ROC scores**
- **Precision, recall, and F1-score** for each disease category

## Results
- **VGG16** achieved the highest accuracy of approximately **60%**.
- **ResNet50** and **MobileNetV2** also performed well, with accuracies around **45%** and **44%**, respectively.
- The models faced challenges such as **data imbalance** and **multi-label classification complexities**.

## Future Work
- Addressing data imbalance through techniques like **SMOTE**.
- Exploring advanced architectures like **Vision Transformers**.
- Enhancing model interpretability with **Grad-CAM**.
- Validating models on **external datasets** to ensure robustness and generalizability.

## Conclusion
This project demonstrates the potential of CNNs in medical imaging but also highlights the need for further advancements to achieve clinically viable performance.

## References
- Krizhevsky, A., Sutskever, I., & Hinton, G. E. (2012). **Imagenet classification with deep convolutional neural networks**.
- Tan, C., et al. (2018). **A survey on deep transfer learning**.
- Shorten, C., & Khoshgoftaar, T. M. (2019). **A survey on image data augmentation for deep learning**.
- Ribeiro, M. T., Singh, S., & Guestrin, C. (2016). **Model-agnostic interpretability of machine learning**.

## Contact
For any questions or collaboration inquiries, please contact **Sumanth Mylar** at [mylas02@pfw.edu](mailto:mylas02@pfw.edu).
