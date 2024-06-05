# CNN BASED IRIS LOCALISATION MODEL

## Main Idea:
This project addresses a significant industrial challenge related to managing specular reflection during biometric identification processes, specifically in the context of iris scanning. Specular reflections, which are bright spots caused by light reflecting off the eye's surface, can interfere with the accuracy and reliability of iris recognition systems. This project aims to develop methods and technologies to effectively mitigate these reflections, enhancing the performance and robustness of biometric systems that rely on iris scanning for identity verification and security applications.

## Overview
This project aims to develop a Convolutional Neural Network (CNN) model for iris localization using the VGG16 architecture. The goal is to locate the iris in eye images accurately, a crucial step in various biometric and computer vision applications, including eye-tracking systems and security authentication.

## Model Architecture
The model uses the VGG16 architecture pre-trained on ImageNet as a backbone, with additional layers for regression to predict the iris center coordinates (x, y) and radius (r).


## Requirements
Python 3.7+<br>
TensorFlow 2.x<br>
Keras<br>
OpenCV<br>
NumPy<br>
Matplotlib<br>
Pandas<br>
scikit-learn<br>
labelme

