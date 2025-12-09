# CE6146 Introduction to Deep Learning<br>Final-Project with Multi Cancer Dataset
Final Project of CE6146 with Multi Cancer Dataset

## Dataset Introduction
Multi Cancer Dataset
- 8 Types of Cancer Images

- Each types has some subclasses
    - At most 5 subclasses
    - At least 2 subclasses
    - Totally 26 subclasses

## Task & Goal
Selecting some types, training models with these types, and comparing performances between each models

- Selected Types
    - Brain Cancer
    - Breast Cancer
    - Cervical Cancer
    - Kidney Cancer
    - Lung & Colon Cancer
    - Lymphoma Cancer
    - Oral Cancer

- Classification task

## Data Preprocess
- Data split
    - Training Set : 70%
    - Validation Set : 15%
    - Test Set : 15%
    
- Feature Scaling
    - Standardization
    
- Data augmentation 
    - Random Flip
    - Random Rotation

## Model Selection
- Traditional CNN
    - Learn from Scratch
    - Number of Parameters :	26M
    
- ResNet
    - Pretrained Model : Resnet50
    - Number of Parameters : 25M
    
- EfficientNet
    - Pretrained Model :		EfficientNet_B0
    - Number of Parameters :	5M
