Dataset Link : https://drive.google.com/drive/folders/1GwE9QWjIhsX-YFfSH7svFgSW0Zeu522p?usp=sharing

GOOGLE COLAB LINK : https://colab.research.google.com/drive/1PtkBnkkpr38NLvvShN3eOpOjAHagHZ-n?usp=sharing


Neural Style Transfer:
This project implements neural style transfer using TensorFlow and PyTorch, offering two different approaches. One approach uses TensorFlow and Keras to build a style learning model, while the other uses PyTorch for neural style transfer.

TensorFlow Style Learning Model
Overview
The TensorFlow part of the project consists of two main components:

Style Learning Model Construction:

The build_style_network function defines a convolutional neural network (CNN) for style learning.
The model is compiled using mean squared error (MSE) loss.
Training the Style Network:

The train_style_network function trains the style network using a dataset of artistic images.
Dummy targets are created for the MSE loss during training.
Usage
Ensure you have TensorFlow installed: pip install tensorflow.
Set the data_path variable to the path of your dataset.
Run the script to train the style learning model.
PyTorch Neural Style Transfer
Overview
The PyTorch part of the project focuses on neural style transfer using a pre-trained VGG19 model. The key components include:

Style Network Definition:

The StyleNetwork class defines the architecture for style learning, using a truncated VGG19 model.
Neural Style Transfer Function:

The neural_style_transfer function combines content and style losses to optimize the content image.
Usage
Install the required dependencies: pip install torch torchvision Pillow matplotlib.
Set the paths for the content and style images and the desired output path in the neural_style_transfer function.
Run the script to perform neural style transfer.