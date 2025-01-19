#MNIST Digit Classification with Convolutional Neural Networks (CNNs)


##Overview
This project demonstrates how to classify handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN) implemented in TensorFlow/Keras. The model is designed to recognize digits (0-9) with high accuracy, incorporating features like data augmentation and regularization to enhance performance and generalization.

##Key Features
###Data Augmentation: Random rotations, shifts, and zooms improve model robustness and generalization.

###CNN Architecture: Includes convolutional layers, max-pooling, batch normalization, and dropout for efficient feature extraction and reduced overfitting.

###Early Stopping: Stops training when validation loss plateaus to prevent overfitting.

###Custom Image Prediction: Preprocesses and predicts handwritten digits from user-uploaded grayscale images.

###Visualization: Displays training/validation accuracy trends and preprocessed input images for analysis.\

##How to Use
#Clone the repository.

1.Install the required dependencies listed below.

2.Upload a custom grayscale image of a handwritten digit using the provided script.

3.Train the model or load the pre-trained model.

4.Test predictions on custom or test data.

##Installation
```bash
###Clone this repository
git clone https://github.com/your-username/mnist-digit-classification.git

# Navigate to the project directory
cd mnist-digit-classification

# Install dependencies
pip install -r requirements.txt
```
##Requirements
⦁Python 3.x

⦁TensorFlow

⦁Keras

⦁NumPy

⦁Matplotlib

⦁Pillow

##Results
###Model Accuracy
⦁Achieved over 98% accuracy on the MNIST test dataset.

⦁Custom images are correctly classified with high confidence.
