> Melanoma Detection Case Study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Background - 
  - Melanoma is a type of cancer that can be deadly if not detected early.
  - It accounts for 75% of skin cancer deaths.
- Objective (What):
  - To build a CNN based model which can accurately detect melanoma.
- Reason (Why):
  - A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Data Description:
  - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
  - All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
  - The data set contains the following diseases:
    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The model is overfitting as the training accuracy is increasing with each epoch but the validation accuracy is not increasing.
- The training loss is decreasing with each epoch but the validation loss is not decreasing.
- The model is not able to generalize well on the validation dataset.
- The model is not able to learn the patterns in the validation dataset.
- The model did not got rid of overfitting/underfitting even after adding more samples to the training dataset i.e. class re-balance did not help.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - v3.9.0
- Seaborn - v0.13.0
- pandas - v2.1.1
- numpy - v1.26.1
- Tensorflow - v2.14.0
- matplot-lib - v3.8.0
- Augmentor - v0.2.12
- Keras - v2.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!--## Acknowledgements -->

## Contact
Created by [@sophophilic] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
