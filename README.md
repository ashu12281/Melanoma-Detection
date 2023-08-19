# Melanoma-Detection
a CNN based model which can accurately detect melanoma

**Problem Statement:**
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

**The Dataset:**
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
  1. Actinic keratosis
  2. Basal cell carcinoma
  3. Dermatofibroma
  4. Melanoma
  5. Nevus
  6. Pigmented benign keratosis
  7. Seborrheic keratosis
  8. Squamous cell carcinoma
  9. Vascular lesion

**Project Pipeline:**
1. Data Reading/Data Understanding 
2. Dataset Creation
3. Dataset visualisation
4. Model Building & training : 
    -Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to         normalize pixel values between (0,1).
    -Choose an appropriate optimiser and loss function for model training
    -Train the model for ~20 epochs
    -Write findings after the model fit. Check if there is any evidence of model overfit or underfit.
5. Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
6. Model Building & training on the augmented data :
    -Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to           normalize pixel values between (0,1).
    -Choose an appropriate optimiser and loss function for model training
    -Train the model for ~20 epochs
    -Write your findings after the model fit, see if the earlier issue is resolved or not?
7. Class distribution
    - class having the least number of samples
    - classes dominating the data in terms of the proportionate number of samples
8. Handling class imbalances: Rectify class imbalances present in the training dataset with Augmentor library.
9. Model Building & training on the rectified class imbalance data :
    -Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to         normalize pixel values between (0,1).
    -Choose an appropriate optimiser and loss function for model training
    -Train the model for ~30 epochs
    -findings after the model fit
