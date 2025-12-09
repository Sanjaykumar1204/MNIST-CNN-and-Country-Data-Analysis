# MNIST-CNN-and-Country-Data-Analysis
A single-notebook project that loads and analyzes Country-data.csv and trains a Convolutional Neural Network (CNN) on the MNIST handwritten digits dataset using TensorFlow. Includes full preprocessing, model training, evaluation, and visual prediction outputs.
🚀 Features
✅ 1. Country-data.csv Loading

Reads a CSV file containing country statistics

Displays shape, preview table, and basic info

Works automatically if the CSV file is in the same folder

✅ 2. MNIST CNN Model

Loads MNIST (60,000 training images, 10,000 test images)

Normalizes and reshapes data for CNN

Builds a deep learning model using:

Conv2D layers

MaxPooling

Dense layers

Compiles the model with Adam optimizer

Trains for 5 epochs with validation split

Achieves ~99% accuracy

✅ 3. Prediction Visualization

Predicts first 16 test images

Displays true label vs predicted label

Visualizes all images using Matplotlib

🧠 Technologies Used

Python

TensorFlow / Keras

NumPy

Pandas

Matplotlib

Jupyter Notebook
