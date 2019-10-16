# SAARC Flag Prediction
Predict SAARC country name from a given flag.

# Description
This project was written in [ImageAi](https://github.com/OlafenwaMoses/ImageAI) library.The model was trained with approximately 2800 images divided 
into 8 different countries. The dataset was handpicked from loosely scraped websites and contains images, photos, drawings, 
sketches at various color schemes (black/white, RGB etc), different angles and sometimes with other images as background.

# Model Metric
The model has an accuracy of 98.345%

# Features
The model was created using [Custom Image Prediction](https://github.com/OlafenwaMoses/ImageAI/blob/master/imageai/Prediction/CUSTOMPREDICTION.md)
class of ImageAi.

### Train
Python "train.py" file was used to train the dataset. Link for dataset is given below. Dataset is divided into two directories train 
and test. Each carry 8 flag(classes). After training, three additional directories produce 
logs,models,jsons. Models directories contain all the model files. Above file was run on google colab.

### Test
Python "test.py" file was used to test the models. Here the model with highest accuracy was used.
Output of this file shows the predicted class(country) of a given flag.Directory 'Image' contains
 the images to be classified.

# Links
Links for precompiled dataset,models,jsons and ImageAi documentation is given below:
  1.Documentation - [Link](https://imageai.readthedocs.io/en/latest/)
    
# Requirements
All the requirements for this to run is given in documentation link.
