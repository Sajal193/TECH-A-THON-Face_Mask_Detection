# TECH-A-THON

This project is made for Tech-A-Thon event organised by ECE Society BIT, Mesra. The domain chosen is Machine Learning and the topic is Health and Safety with Recognition prerequisites.


# Face_Mask_Detection
Having various application in multiple fields, this project aims to spread awareness among people about covid-19 and refrain from any potential outbreak cause for the diease.
Staying safe and healthy is a far sighted-aim for this project. This project determines whether a person is wearing a face mask or not. If the person does, a 'green' rectangle will be formed with 'With_ MASK' written on top of rectangle, or else a 'red' rectangle with 'Without_MASK' mentioned on the screen.

In this project, we have developed a deep learning model for face mask detection using Python, Keras, and OpenCV. We developed the face mask detector model for detecting whether person is wearing a mask or not. We have trained the model using Keras with network architecture. Training the model is the first part of this project and testing using webcam using OpenCV is the second part.

Before implementing face mask detection problem, first we need to understand that how to handle images. Images are simply a collection of colors in red, green and blue format.
As a human we see an image with some object or shape in it, but for computer it is just an array with color values range from 0 to 255.

# Introduction to OpenCV
-OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library.
-The library has more than 2500 optimized algorithms.
-It has C++, Python, Java and MATLAB interfaces and supports Windows, Linux, Android and Mac OS.
-Will help us to load images in Python and convert them into array.
-Each index of array represents (red, green, blue) color pixel which ranges from 0 to 255.

# Features of OpenCV
-Face Detection
-Geometric Transformations
-Image Thresholding
-Smoothing Images
-Canny Edge Detection
-Background Removals
-Image Segmentation

# Information about Keras
Keras is an open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library.
Keras is:
-Simple -- but not simplistic. Keras reduces developer cognitive load to free you to focus on the parts of the problem that really matter.
-Flexible -- Keras adopts the principle of progressive disclosure of complexity: simple workflows should be quick and easy, while arbitrarily advanced workflows should be possible via a clear path that builds upon what you've already learned.
-Powerful -- Keras provides industry-strength performance and scalability: it is used by organizations and companies including NASA, YouTube, or Waymo.

# Keras and Tensorflow
TensorFlow 2 is an end-to-end, open-source machine learning platform. You can think of it as an infrastructure layer for differentiable programming. It combines four key abilities:

Efficiently executing low-level tensor operations on CPU, GPU, or TPU.
Computing the gradient of arbitrary differentiable expressions.
Scaling computation to many devices, such as clusters of hundreds of GPUs.
Exporting programs ("graphs") to external runtimes such as servers, browsers, mobile and embedded devices.
Keras is the high-level API of TensorFlow 2: an approachable, highly-productive interface for solving machine learning problems, with a focus on modern deep learning. It provides essential abstractions and building blocks for developing and shipping machine learning solutions with high iteration velocity.

# Face Mask Detection Flow Diagram
![image](https://user-images.githubusercontent.com/74758269/135734981-8be63f2e-aebb-440f-9587-4446af4a31d7.png)
