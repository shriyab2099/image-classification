# Scene Image Classification

This project aims to classify natural scene images into six categories: buildings, forest, glacier, mountain, sea, and street. The dataset comprises around 25,000 images of size 150x150, divided into training, testing, and prediction sets. The training set contains approximately 14,000 images, the testing set contains 3,000 images, and the prediction set contains 7,000 images.

## Preprocessing
All input images are resized to 150x150.


## Deep Learning Models Used
1. Convolutional Neural Network (CNN)
CNN is a widely-used deep learning model for image classification tasks.
It excels in capturing spatial hierarchies and patterns in images through convolutional layers.
2. VGG16
VGG16 is a deep convolutional neural network known for its simplicity and effectiveness.
It consists of 16 convolutional and fully connected layers, making it suitable for various image classification tasks.
3. MobileNet
MobileNet is a lightweight deep learning model designed for mobile and embedded vision applications.
It achieves high accuracy with significantly fewer parameters compared to traditional architectures, making it suitable for resource-constrained environments

## Methodology
Data Preprocessing: The input images are preprocessed to enhance their quality and prepare them for feature extraction.

Feature Extraction: Features are extracted from the preprocessed images using the selected deep learning models.

Model Training: The extracted features are used to train the classification models, including CNN, VGG16, and MobileNet.

Model Evaluation: The trained models are evaluated on a separate test dataset to measure their accuracy and effectiveness.

Model Integration: The outputs of the individual models are combined to leverage the strengths of each model and improve overall classification performance.

