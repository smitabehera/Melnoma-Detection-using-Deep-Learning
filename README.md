# Melnoma-Detection-using-Deep-Learning
Melanoma Detection based on Deep Learning using CNN

## Problem Statement

This projet aims to build a CNN based model which can accurately detect melanoma which is a type of cancer that accounts for 75% of skin cancer deaths if not detected early. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Dataset
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Technologies Used
- TensorFlow
- Keras
- Python

## Conclusions
- We started with a base CNN model with 3 convolution layers plus pooling layers followed by flattenning and two dense layers and later added dropout and augmented the data.
- The final model that best fit the data was obtained by rebalancing the data using Augmentor module
