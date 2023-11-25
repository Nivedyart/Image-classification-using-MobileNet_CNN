# Image-classification-using-MobileNet_CNN
Nervousness detection using Mobilenet CNN architecture 

## Overview
The objective of nervousness detection using NERVOUS and NEUTRAL emotions is to develop an automated system that can accurately detect
nervousness in facial expressions from images.


## Applications
This system can be used for various applications, such as detecting nervousness in public speaking or job interviews, which can help
individuals improve their communication skills and boost their confidence.


## Methodology
### Step1 : Dataset Collection
The first step in this project is to collect the dataset having fear and neutral emotions, which is a publicly available on
websites of facial expressions. This dataset contains 9072 grayscale images of faces that are used for model training labeled with two emotions, including fear and neutral. And 2257 grayscale images of faces that are used for model validation.
### Step2 : Data Preprocessing
The collected dataset needs to be preprocessed to make it suitable for training the nervousness detection model. The preprocessing steps include resizing the images to a standard size, converting the images to grayscale, and normalizing the pixel values.
### Step3 : Model Selection
MobileNet is a computer vision model open-sourced by Google and designed for training classifiers. It uses depthwise convolutions to significantly reduce the number of parameters compared to other networks, resulting in a lightweight deep neural network. MobileNet is Tensorflow’s first mobile computer vision model.
### Step4 : Model Validation
We are validating the model on a dataset containing 2257 images of 2 classes namely NERVOUS and NEUTRAL. We are getting an accuracy of 75% approximately.
