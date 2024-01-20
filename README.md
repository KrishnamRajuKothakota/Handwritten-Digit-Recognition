# Handwritten-Digit-Recognition
The Handwritten Digit Recognition Project is an innovative and practical application of machine learning and computer vision techniques designed to accurately identify and classify handwritten digits.

This project leverages Gradio, a user interface library for machine learning, to create an interactive web application for handwritten digit recognition. The application is powered by a convolutional neural network (CNN) trained on the MNIST dataset. Users can draw a digit on the canvas, and the model predicts the digit with real-time feedback.

**Components:**
Training Script (training.py):

Loads the MNIST dataset.
Preprocesses and normalizes the images.
Defines and trains a CNN using TensorFlow and Keras.
Saves the trained model for later use.
Application Script (app.py):

Loads the pre-trained CNN model.
Defines a Gradio interface with a canvas for drawing digits.
Utilizes the trained model to predict handwritten digits.
Displays real-time predictions and probability scores.


**How to Use**:
Run training.py to train the model and save it as 'model.h5'.
Run app.py to launch the web interface.
Draw a digit on the canvas and observe real-time predictions.


**Technologies Used:**
TensorFlow and Keras for model training.
Gradio for building the user interface.

Credit : NeuralNine (Youtube)
