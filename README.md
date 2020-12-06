# Summary

This NN aims to target object detection by using "You Only Look Once" (YOLO) algorithm with displaying bounding boxes. It displays box by using non-max supression to output only 1 bounding box per object. Particularly, it is used in autonomous driving to allow predicatable changes.

# Neural Network Architecture

This project uses pretrained model of YOLO algorithm which consits of 22 Convolutional Layers with 5 Max Pooling layers. It uses batch normalization to speed up the process of output.The common activation function used is Leaky ReLU a subset of ReLU activation function. 
Total params: 50,983,561
Trainable params: 50,962,889
Non-trainable params: 20,672

# Problem Statement

You are working on a self-driving car. As a critical component of this project, you'd like to first build a car detection system. To collect data, you've mounted a camera to the hood (meaning the front) of the car, which takes pictures of the road ahead every few seconds while you drive around.

You've gathered all these images into a folder and have labelled them by drawing bounding boxes around every car you found. Here's an example of what your bounding boxes look like.If you have 80 classes that you want the object detector to recognize, you can represent the class label cc either as an integer from 1 to 80, or as an 80-dimensional vector (with 80 numbers) one component of which is 1 and the rest of which are 0. The video lectures had used the latter representation; in this notebook, we will use both representations, depending on which is more convenient for a particular step.

# Frameworks

This project uses tensorflow, keras,scipy,numpy, pandas and Matplotlib.
