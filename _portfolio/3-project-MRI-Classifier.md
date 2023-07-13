---
title: "MRI image Classifier for Alzheimer's Disease" 
excerpt: "MRI image classifier using ResNet50 arquitecture for Alzheimer's disease. Grad-CAM is also implemented to give explainability.<br><img src='/images/project-MRI-Classifier/diagram.png'>"
collection: portfolio
---
<p align="center">
  <img width="50%" src='/images/project-MRI-Classifier/diagram.png'>
</p>
In this project convolutional neural networks will be applied on a dataset of MRI images with the aim of generating a model capable of predicting the degree ofAlzheimer's disease of any patient. We will focus on the detection of Alzheimer's disease and its different degrees based on 2D images of Magnetic Resonance Imaging(MRI) scans.

Furthermore, a grad-camera will be applied to the model in order to visualize the areas of the image that have been more relevant for the classification.

<p align="center">
  <img width="50%" src='/images/project-MRI-Classifier/grad-cam.png'>
</p>

## Dataset
The dataset has been obtained from the Kaggle platform which contains MRI images in zenith plane of different people separated into four classes. These classes are "NonDemented", "VeryMildDemented", "MildDemented" and "ModerateDemented" where each one represents the degree of Alzheimer's of the patient.

The dataset itself separates the images into two folders: train (5121 instances) and test (1279 instances), which will be used to train and test the convolutional network respectively.

<p align="center">
    <a class="btn" href="https://github.com/alberto-mate/MRI-Alzheimer-Classifier"> <i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
</p>