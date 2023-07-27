# Wildlife_Detector_and_Classifier_using_CNN
This repository contains a CNN model for classifying images of animals into five categories: cow, dog, elephant, leopard, and tiger. The model achieves an impressive accuracy of 95 percent on a test dataset, making it highly effective for animal recognition tasks.

# Dataset
The model is trained on a carefully curated dataset of labeled images containing various instances of cows, dogs, elephants, leopards, and tigers. The dataset has been preprocessed and split into training, validation, and testing sets to ensure accurate evaluation of the model's performance.
[Link](https://drive.google.com/drive/folders/1tElkQ_W0V2o7XrZpxUjmq5BBBsjEB3lf?usp=sharing)

# Model Architecture
The CNN architecture used in this project is designed to effectively learn and extract meaningful features from the input images. The model consists of multiple convolutional layers followed by max-pooling layers to downsample the feature maps. Batch normalization and dropout layers are incorporated to enhance the model's generalization and prevent overfitting.

The final layers of the CNN include fully connected (dense) layers with appropriate activation functions to map the extracted features to the respective classes. The output layer uses the softmax activation function to generate class probabilities.

# Training
The model is trained using an iterative process called stochastic gradient descent (SGD) with adaptive learning rate adjustments. During training, the model learns from the training data and updates its parameters to minimize the cross-entropy loss between predicted and actual labels. The training process is monitored using the validation set to prevent overfitting and select the best-performing model.

# Model Performance
The CNN model achieves an impressive accuracy of 95 percent on the test dataset, demonstrating its capability to accurately classify images of cows, dogs, elephants, leopards, and tigers.
