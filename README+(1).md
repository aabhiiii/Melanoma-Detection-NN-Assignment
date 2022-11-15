# Melanoma Detection Assignment
> We are trying to build a multiclass classification model using a custom convolutional neural network in TensorFlow which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this case study we are provided with the dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- The data set contains the following diseases:
Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
- Our objective is build a multiclass classification model using a custom convolutional neural network in TensorFlow which can accurately detect melanoma. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- We have got good train accuracy score 0.98 and validation accuracy score of 0.76
- We have reduced the overfitting using Data Augmentation
- We have handled the class imbalance using Augmetor library

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.13
- Pandas - version 1.3.5
- Matplotlib - version 3.2.2
- Seaborn - version 0.11.2
- tensorflow
- Augmentor
- sklearn
- Kaggle

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by International Skin Imaging Collaboration (ISIC)
- References if any...
- This project was based on CNN module in ML EPGP program in Upgrad.


## Contact
Created by [@aabhiiii] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->