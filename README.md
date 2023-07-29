# Satellite Image Classification with Keras (multi-class)

The present project was conducted as the final assignment for a remote Data Analytics Bootcamp at Ironhack and was carried out in 10 days.

## Problem Description
Classification of satellite photography into 4 classes ("cloudy", "desert", "green area" or "water"), depending on the area depicted.

## Dataset
The dataset contains a total of 5631 images, separated in 4 folders, each representing one of the 4 classes. The original data can be found [here](https://www.kaggle.com/datasets/mahmoudreda55/satellite-image-classification).

## Approach
The data was mapped, explored, processed and augmented with the purpose of training a Deep Learning Model, namely Keras, which is an API, written in Python and utilising Tensorflow's machine learning platform. Data augmentation was achieved via Keras's ImageDataGenerator class.

Parameter tuning during first touch was conducted manually and was based on paradigms, articles, documentation and literature.
<br>
<br>The process followed has been saved in 2 Notebooks,  the first one [satimclass_data_cleaning](https://github.com/Evangelos-Z/Ironhack_Final_Project-Sat_Img_Class/blob/main/satimclass_data_cleaning.ipynb) pertaining to the data cleaning and the second one [satimclass_training_evaluation_keras](https://github.com/Evangelos-Z/Ironhack_Final_Project-Sat_Img_Class/blob/main/satimclass_training_evaluation_keras.ipynb) containing the script on data augmentation, model training, evaluation, a short demo of the model's capabilities when evaluated against the test data and finally a further exploration on the performance of the model for different settings of batch size and learning rate.

## Model Performance
The model performed fairly well both when in with imbalanced as well as with balanced data (96% and 98% accuracy respectively), but it was more stable throughout the process when dealing with the balanced set and was able to get closer to its learning curve's plateau faster. 

## Environment:

JupyterLab

## Libraries, Utils, APIs

Pandas<br>
Numpy<br>
Os<br>
Shutil<br>
Re<br>
Matplotlib<br>
Seaborn<br>
PIL<br>
Random<br>
Tensorflow<br>
Keras<br>
Sklearn<br>
Warnings<br>
Time<br>
Winsound<br>


## Hurdles
Unfortunately, the time dedicated to the project had to be cut short. Due to technical difficulties and a misunderstanding of the time needed to collect the right kind of data from multiple sources, a new direction had to be chosen. As a result, what was supposed to be a 3-week project ended up being wrapped up in 10 days.

The time constrain along with the suboptimal resource management by Tesnsorflow on Windows 10 Native, made it hard to get into a more extensive exploration of different configurations for the model.

## Special Thanks and Acknowledgments

This project would not have been possible if not for:

- Xisca, whose guidance, hands-on knowledge and words of encouragement helped have been an incredible help throughout this experience.

- Laz, who has been my anchor to reality, supported me and has helped me debug my brain and processes when I needed it the most.

- [Sabina](https://github.com/sabinagio), who has been an inspiration from day 1 on this bootcamp and whose influence on my scripts is all too obvious.

- & last, but far, far from least [Isi](https://github.com/isi-mube). Thank you for all the help, technical support, the psychological support, the code sharing and for being such a sweet person.         _<br>[...]If there was some amazing force outside of time
<br>To take us back to where we were
<br>And hang each moment up like pictures on the wall._

 
