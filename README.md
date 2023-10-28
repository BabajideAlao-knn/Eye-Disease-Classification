# Eye-Disease-Classification

This repository contains the code and resources for an eye disease classification system using deep learning. The system is designed to classify various eye diseases based on retinal images. Deep learning models are used to automate the diagnosis process, allowing for early detection and intervention.

## ABOUT THE DATASET
The dataset consists of retinal images of different classes. These images are collected from various sources like IDRiD, Oculus recognition, HRF, etc. The number of images for each class is as follows:

Cataract = 1038 images
Glaucoma = 1007 images
Normal = 1074 images
Diabetic retinopathy = 1098 images

## MODEL 
The model was created with a training data consisting of 3,374 images, while the validation was 843 images. A simple CNN model was then created. The model takes an input image of size (224, 224, 3), applies multiple convolutional and max-pooling layers to extract features, and finally passes these features through fully connected layers to make predictions.

