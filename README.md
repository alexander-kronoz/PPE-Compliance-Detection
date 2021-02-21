# Face Mask Type Detector


This repository contains the code and Google Colab notebook for training a face mask type detector with [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection). 

The model is used to detect face masks of 4 classes: homemade cloth covers, surgical mask, n95 mask and no mask. The corresponding labels are:
- homemade
- surgical 
- n95
- bare


### Dependencies
- Python 3.5
- TensorFlow 1.10

### Training image examples
The images used for training are from Google and Upslashe. There are 247, 197, 184 and 255 images for each class. 


### Model Output
