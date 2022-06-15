# Melenoma Detection Using CNN
> Multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)



## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma.
  Melanoma is a type of cancer that can be deadly if not detected early. 
  It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma
  has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
  All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images,
  with the exception of melanomas and moles, whose images are slightly dominant.
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



## Conclusions
- This final model still seems to be overfitting
- This problem of overfitting can be solved by various methods such as adding neuron layers, adding drop outs etc
- The Accuracy on training data has increased a lot
- We can use hyper parameter tuning to still better this mode




## Technologies Used
- Python 3.10.1
- Pandas 1.3.5
- seaborn 0.11.2
- Matplotlib 3.5.1
- keras
- sklearn



## Contact
Created by [@NikhileshwarReddy] - feel free to contact me!
