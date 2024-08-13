![Uploading bigstock-group-of-sad-people-and-a-hap-12165734.jpg…]()

This project demonstrates the use of a Convolutional Neural Network (CNN) for classifying images into two categories: "Happy" and "Sad." The model is trained on a dataset of labeled images, with the goal of accurately predicting the emotional expression in new images

### Project Overview

#### Objective:
To build and train a deep learning model that can classify images as either "Happy" or "Sad."

#### Dataset: 
The project uses a custom dataset of images stored in Google Drive. The images are categorized into "happy" and "sad" folders.

#### Tools and Libraries:
The project is implemented in Python using TensorFlow and Keras for deep learning, along with OpenCV for image processing.

### Key Features

#### Image Preprocessing:
- The images are loaded, and any corrupted or non-image files are removed.
- The images are resized and normalized to prepare them for model training.

#### Model Architecture:
- The model is built using a Convolutional Neural Network (CNN) with several layers of convolution, max pooling, and dense layers.
- The final output layer uses a sigmoid activation function for binary classification.

#### Training:
- The model is trained on 70% of the dataset, with 20% used for validation and 10% for testing.
- Early stopping and TensorBoard are used to monitor the training process and prevent overfitting.

#### Evaluation:
- The model is evaluated using Precision, Recall, and Accuracy metrics on the test set.
- The performance metrics are visualized to understand the model's behavior.

#### Prediction:
- The trained model is used to predict the emotion in new images. The model outputs "happy" if the prediction is less than 0.5, otherwise, it outputs "sad."

### Installation
 -To run this project, you need to have the following libraries installed:
    pip install tensorflow opencv-python matplotlib

### How to Run

#### Data Preparation:
- Place the images into appropriate "happy" and "sad" folders.
- Ensure that the directory structure matches the one used in the code.

#### Training the Model:
- Run the notebook to preprocess the images, build the model, and train it on your dataset.

#### Evaluation and Prediction:
- Evaluate the model on the test dataset and use it to classify new images.

#### Model Saving:
- The trained model can be saved to Google Drive or your local directory for future use.

### Results
- The model achieves high precision, recall, and accuracy on the test set, demonstrating its effectiveness in emotion classification.

### Contributing
If you'd like to contribute to this project, please fork the repository and submit a pull request.
