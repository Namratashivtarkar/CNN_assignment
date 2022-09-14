# CNN_assignment

# CNN Based Skin Cancer Detection
> Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- To build a multiclass classification model using a custom convolutional neural network in TensorFlow.
- To build a CNN based model which can accurately detect melanoma.
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC)


## Conclusions
- This seems like model is overfit since training accuracy is very high and validation accuracy so low 
- After using data augumentation strategy, training accuracy and validation accuracy gap seems reduces from last time. validation loss has also reduced than last time. But as epohs increases training loss also reduced.
- Class 6(seborrheic keratosis) has the least No. of samples 
- So, now we have added 700 images to all the classes to maintain some class balance. We can add more images as we want to improve training process.
- After augmentation with augmentor library, we are able to balance the class and built a good Model. Training Accuracy=95% Validation Accuracy=83% Thus Model is generalisable model now.



## Contact
Created by [@namratashivtarkar] - feel free to contact me!
