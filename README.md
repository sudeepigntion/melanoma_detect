# Melanoma Detection Assignment

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The task is to detect different type of melanoma.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Have to use TPU or GPU to reduce the processing time of the training
- With epoch 20 (loss: 0.5076 - accuracy: 0.8164 - val_loss: 2.0125 - val_accuracy: 0.5034)
- With epoch 50 (loss: 0.7337 - accuracy: 0.7143 - val_loss: 1.5440 - val_accuracy: 0.5526)
- Total params: 3,989,801
- Trainable params: 3,989,801
- Non-trainable params: 0
- Predictions:
 [0 1 0 0 0 1 0 0 1 0 0 0 1 1 1 1 0 0 0 0 1 1 1 1 0 0 0 0 1 0 0 0 1 0 0 0 0
 0 1 1 1 1 0 0 0 0 1 0 1 1 1 0 0 0 0 1 0 1 0 0 0 1 0 0 0 1 0 1 1 0 1 0 1 1
 0 0 1 1 0 1 0 0 1 1 0 0 0 0 1 0 0 0 0 0 1 1 0 0 0 0 1 1 0 0 1 0 1 0 0 1 0
 0 0 1 0 1 0 0 0 0 1 1 1 1 0 0 0 0 0 1 1 1 1 0 0 0 1 0 1 1 1 1 0 0 0 0 0 0
 1 1 0 0 0 0 1 1 0 0 1 0 0 0 0 1 1 0 1 1 0 1 1 0 0 0 1 1 0 1 0 0 0 0 0 1 1
 1 1 0 0 1 1 0 0 1 1 0 1 0 0 0 0 1 1 0 1 0 0 0 0 1 0 1 1 0 0 0 1 1 1 0 1 1
 0 1 0 0 0 1 1 1 1 0 0 0 0 0 1 1 1 1 0 0 0 0 1 0 1 1 1 0 0 1 0 1 0 0 0 0 0
 1 0 0 1 1 0 0 1 0 1 0 0 1 0 0 0 0 0 1 0 0 1 0 1 0 1 0 0 1]
Labels:
 [8 4 3 7 2 1 1 7 1 2 0 5 7 4 3 4 1 5 2 3 4 1 6 3 2 4 3 2 7 1 7 7]

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python v3
- Pandas
- Numpy
- Matplotlib
- Tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by the teachings of Upgrad course and faculties.

## Contact
Sudeep Dasgupta - sudeep.ignition@gmail.com

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
