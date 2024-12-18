# Project Name

Melanoma Detection

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
### Problem Statement:

Skin cancer is one of the most common cancers globally, with melanoma being the deadliest form. Despite accounting for only a small percentage of skin cancer cases, melanoma is responsible for 75% of skin cancer-related deaths. Early detection of melanoma can significantly improve survival rates. However, the manual evaluation of skin lesion images by dermatologists is time-consuming and prone to human error.

The goal of this assignment is to build a custom Convolutional Neural Network (CNN) model in TensorFlow to accurately classify skin lesions into nine distinct categories. This automated solution has the potential to assist dermatologists by reducing the manual effort required for diagnosis, thereby enabling quicker and more accurate detection of melanoma and other skin conditions.

### Dataset Overview
The dataset contains 2,357 dermatoscopic images of malignant and benign oncological diseases, sourced from the International Skin Imaging Collaboration (ISIC). The dataset is categorized into the following nine classes:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

### Objectives
- Develop a robust CNN model capable of accurately classifying skin lesion images.
- Handle data imbalances effectively to improve model performance across all classes.
- Evaluate and refine the model to ensure high accuracy and reliability without overfitting or underfitting.
- Provide insights into the dataset and the model's decision-making process.


By completing this project, we aim to create a reliable and scalable solution for the early detection of melanoma, which could potentially assist dermatologists in saving lives.


The dataset is imbalanced, with some classes, such as melanomas and moles (nevus), having a higher representation. Addressing this imbalance is a critical part of the project.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Overfitting: 
	Due to the small size of the dataset, the model tends to overfit to the training data, resulting in poor generalization on unseen data.

Data Augmentation in TensorFlow:

	While TensorFlow-based data augmentation helped mitigate overfitting, it did not result in a notable improvement in model accuracy.
	
Class Imbalance:
	The dataset suffers from significant class imbalance, leading to the dominance of certain diseases in the predictions. This impacts the model's ability to generalize across all classes effectively.



## Technologies Used
- Python - 3.12
- seaborn - 0.12.2
- matplotlib - 3.8.0
- pandas -  2.1.4
- numpy -  1.26.4
- Scikit-Learn - version 1.5.1
- Statsmodels - verion 0.14.2
- TensorFlow - version 2.17.1
- Augmentor - version 0.2.12

## Acknowledgements
- This project was done as part during the PG Program in ML and AI from IIIT - B, in association with Upgrad.



## Contact
Created by [@ramyap-learnspace] - feel free to contact me!
