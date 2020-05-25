
## Project Overview

This is one the required projects to graduate in Udacity's Machine Learning Engineer Nanodegree.

In this project, it was built a plagiarism detector that examines an answer text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided, source text. all the project was made using AWS SageMaker. All additional information can be found at the two notebooks files in this repository.

## Files
This repository contain the following files:

#### 2_Plagiarism_Feature_Engineering.ipynb

A jupyter Notebook file containing the steps necessary to complete the project. The main objectives in this Notebook are to download, explore, pre-process and split the data into train and test sets. After that a feature Engineering is done to select the best features to train the model. The original file without the __TODO'S__ parts can be found at https://github.com/udacity/ML_SageMaker_Studies.

#### 3_Training_a_Model.ipynb

A jupyter Notebook file containing the steps necessary to complete the project. The main objectives in this Notebook are to upload the data to S3,define a classification model and a training script, train the model and deploy it and evaluate the model. The original file without the __TODO'S__ parts can be found at https://github.com/udacity/ML_SageMaker_Studies.

#### Other Files 
* __model.py__: This file defines the classifier in Pytorch.
* __train.py__: This file contains the script to train the model.
* __predict.py__: This file contains the script to make the model predict if a given text is plagiarism or not.
* __helpers.py__: This file contains some helpers functions when preprocessing and splitting the data.
* __problem_unittests.py__: This file contains some unit tests to check the if the code is correct.
