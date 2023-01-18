# Project Name
 Multiclass classification model using a custom convolutional neural network in TensorFlow.

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early.It accounts for 75% of skin cancer deaths. 
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

## Project Pipeline
* Data Reading/Data Understanding → Defining the path for train and test images 
* Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
* Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset 
* Model Building & training
* Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
* Model Building & training on the augmented data
* Class distribution: Examine the current class distribution in the training dataset 
* Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
* Model Building & training on the rectified class imbalance data.

## Technologies Used
- Language - Python 3
- library - Numpy
- library - Pandas
- library - matplotlib
- library - PIL
- library - Tensorflow

## Acknowledgements
- This project is part of a case study from Upgrad to build a CNN model which can accurately detect melanoma.


## Contacts
- Created by [@saswatdash]
