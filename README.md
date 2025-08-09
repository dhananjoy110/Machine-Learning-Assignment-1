# Machine-Learning-Assignment-1

Handwritten Digit Recognition using TensorFlow (MNIST Dataset)

 Overview :
 
This project demonstrates a simple neural network implementation using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset.
The model is trained on grayscale 28x28 pixel images of digits (0–9) and evaluated for accuracy on unseen test data.


 Dataset:
 
         The MNIST dataset is a collection of:
         60,000 training images
         10,000 testing images
         Each image is a 28x28 grayscale picture of a handwritten digit (0–9).


 Technologies Used :
 
         Python 3
         TensorFlow / Keras
         Matplotlib (for visualization)
         NumPy (implicitly used by TensorFlow)

         
 How the Code Works :
 
Import Libraries – Loads TensorFlow, Matplotlib, and the MNIST dataset.

Load & Normalize Data – Pixel values are scaled to the range [0, 1] for better training performance.

Build the Model – A simple Sequential neural network with:

Flatten layer (28×28 → 784 input neurons)

Dense layer (128 neurons, ReLU activation)

Dense output layer (10 neurons, Softmax activation)

Compile the Model – Uses Adam optimizer and Sparse Categorical Crossentropy loss.

Train the Model – Runs for 5 epochs on the training dataset.

Evaluate Performance – Prints test accuracy.

Make Predictions – Predicts and visualizes sample outputs.


 Example Output:

Test Accuracy: ~97–98% (may vary depending on environment)

Displays the first test image with predicted and actual labels.


 Notes :
 
The current model is simple and may be improved by adding convolutional layers (CNN) for higher accuracy.

This code is beginner-friendly and ideal for learning TensorFlow basics.


 Author :
Dhananjoy Borgohain

B.Tech in Computer Science & Engineering

Barak Valley Engineering College

