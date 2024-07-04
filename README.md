# Pneumonia Detection in X-ray Images using ResNet18 Architecture 
This project focuses on developing a deep learning model for classifying pneumonia in chest X-ray images. The model is built on the ResNet18 architecture and is trained to distinguish between normal lungs and lungs with pneumonia. This project leverages the dataset provided by the RSNA Pneumonia Detection Challenge on Kaggle, aiming to assist in the early diagnosis of pneumonia through automated image analysis.

### Features
X-ray images have been efficiently loaded and preprocessed from a directory. The ResNet18 architecture has been modified to include custom layers for pneumonia classification. Various image transformations have been appplied to images to enhance the robustness of the model. The model has been trained on the provided dataset and its performance has been evaluated on unseen data.

### Dataset
The dataset consists of X-ray images with labels indicating the presence or absence of pneumonia. The dataset is provided by the RSNA Pneumonia Detection Challenge on Kaggle, and the images are stored in a directory structure.

### Model Architecture
The model is based on the ResNet18 architecture, a powerful convolutional neural network known for its residual learning capabilities. The classifier part of the ResNet18 model is modified to include custom fully connected layers for binary classification.

### Training
The model is trained on 24000 images using the Adam optimizer and CrossEntropyLoss, which is appropriate for classification tasks. The training loop iterates through the dataset, computes the loss, performs backpropagation, and updates the model weights.

### Evaluation
The model's performance is evaluated using a validation set consisting of 2684 images.
