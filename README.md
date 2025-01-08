# Brain_Tumor_Detection_DL

## Project Overview
This project focuses on brain tumor detection using deep learning techniques. The goal is to classify MRI images into four categories:

- No Tumor
- Pituitary Tumor
- Meningioma Tumor
- Glioma Tumor

The dataset used for this project is the Brain Tumor Classification MRI Dataset from [Kaggle](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri/data). It consists of MRI images divided into training and testing folders with the following distribution:

- No Tumor: 500 images
- Pituitary Tumor: 901 images
- Meningioma Tumor: 937 images
- Glioma Tumor: 936 images

## Data Preprocessing

To ensure high model performance, the following preprocessing steps were applied:
- Cropping: Focused on the brain region to remove unnecessary parts.
- Resizing: Standardized image dimensions for uniform input.
- Normalization: Scaled pixel values between 0 and 1.
- Data Splitting: Split the data into training, testing, and validation sets.
- Data Augmentation: Performed on the training data to improve generalization by applying transformations like rotation, flipping, and zooming.



## Models Used
Four models were implemented and evaluated for this classification task:

- Custom CNN Model - A self-designed convolutional neural network optimized for speed and efficiency.
- InceptionV3 - A well-known deep learning model with high accuracy for image classification tasks. 
- DenseNet - A densely connected convolutional network known for feature reuse and efficient learning. 
- EfficientNet B0 - A state-of-the-art model that balances accuracy and computational efficiency.



Models Used

Four models were implemented and evaluated for this classification task:

Custom CNN Model - A self-designed convolutional neural network optimized for speed and efficiency.

InceptionV3 - A well-known deep learning model with high accuracy for image classification tasks.

DenseNet - A densely connected convolutional network known for feature reuse and efficient learning.

EfficientNet B0 - A state-of-the-art model that balances accuracy and computational efficiency.

## Results
The models were evaluated based on accuracy and computational efficiency. Below is a comparison of the performance:

![Screenshot 2025-01-08 102007](https://github.com/user-attachments/assets/96fb615f-9fc1-4540-a767-51388a624b77)

## Future Work
- Expand Dataset: The current dataset size is limited. A larger and more diverse dataset can improve model performance and generalization.
- Tumor Segmentation: Current models classify the presence of tumors. Implementing YOLO (You Only Look Once) or segmentation networks can help detect and localize tumor regions within the MRI images.
- Model Optimization: Further tuning of the custom CNN architecture could lead to higher accuracy while maintaining efficiency.
- Multi-Class Segmentation: Beyond binary tumor detection, future models could classify the tumor type and segment the exact tumor boundaries.

## Acknowledgments
- Kaggle: For providing the Brain Tumor Classification MRI Dataset.
- TensorFlow/Keras: Used for building and training the deep learning models.
