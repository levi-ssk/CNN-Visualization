# Visualize CNN Feature Maps

This notebook demonstrates how a Convolutional Neural Network (CNN) extracts features from raw images by visualizing the feature maps generated after each layer. We will dissect the model layer by layer to see how the network transforms the input image into a representation that can be used for classification.

## Dataset

The notebook uses the benchmark CIFAR-10 dataset, which consists of 50,000 training images and 10,000 test images across 10 different classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck).

## Notebook Structure

1.  **Setup and Data Loading**: Imports necessary libraries (TensorFlow, Keras, NumPy, Matplotlib) and loads the CIFAR-10 dataset.
2.  **Data Preprocessing**: Normalizes the pixel values of the images and one-hot encodes the labels.
3.  **Random Image Selection**: Selects a random test image for visualization purposes.
4.  **Model Definition**: Defines a simple CNN model using the Keras Sequential API.
5.  **Visualization Function**: Creates a function to visualize the output (feature maps) of each layer in the model for a given input image.
6.  **Visualization Before Training**: Visualizes the feature maps before the model is trained to show the initial random state of the filters.
7.  **Training**: Trains the CNN model on the CIFAR-10 training data.
8.  **Visualization After Training**: Visualizes the feature maps again after training to observe how the filters have learned to extract meaningful features from the images.

## How to Use

1.  Run all the code cells in the notebook sequentially.
2.  Observe the output of the visualization cells before and after training to see the effect of training on the feature maps.

This notebook provides a visual intuition into how CNNs learn hierarchical representations of images through layers of convolutions and pooling.
