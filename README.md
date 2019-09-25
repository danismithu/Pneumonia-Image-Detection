# Pneumonia-Image-Detection

## Description
This is a tool for detecting Pneumonia Virus and Pneumonia Bacteria in the images of X-rays of patients. The model is trained using transfer learning with the model InceptionV3.

## Dataset
For training it uses [this dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia) from Kaggle. It contains three folders: one for training, one for testing and one for validation. The model has a 68.75% of accuracy.

## Recomendations
For future improvement it is recommended to improve the Convolutional Network used to retrain the model and test if changing the weights in the InceptionV3 could make differences. In the validation section 6 out of 8 images where predicted correctly.
