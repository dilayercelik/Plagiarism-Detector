# Plagiarism-Detector

This repository contains code and associated files for deploying a plagiarism detector using AWS SageMaker.
This Project is part of the Module 'Machine Learning, Case Studies' in the Machine Learning Engineer Nanodegree, offered at Udacity, School of AI.

![img](https://github.com/dilayercelik/Plagiarism-Detector/blob/master/plagiarism-checker.png)

# Project Overview
In this project, you will be tasked with building a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text. Detecting plagiarism is an active area of research; the task is non-trivial and the differences between paraphrased answers and original work are often not so obvious.

# Outline

This project will be broken down into three main notebooks:

## Notebook 1: Data Exploration

- Load in the corpus of plagiarism text data.

- Explore the existing data features and the data distribution.


## Notebook 2: Feature Engineering

- Clean and pre-process the text data.

- Define features for comparing the similarity of an answer text and a source text, and extract similarity features.

- Select "good" features, by analyzing the correlations between different features.

- Create train/test .csv files that hold the relevant features and class labels for train/test data points.


## Notebook 3: Train and Deploy Your Model in SageMaker

- Upload your train/test feature data to S3.

- Define a binary classification model and a training script.

- Train your model and deploy it using SageMaker.

- Evaluate your deployed classifier.

# Setup

Please see the [README](https://github.com/udacity/ML_SageMaker_Studies/tree/master/README.md) in the root directory of Udacity's repo for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).


# Files

- [1_ Data_Exploration](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/1_%20Data_Exploration)

- [2_Plagiarism_Feature_Engineering](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/2_Plagiarism_Feature_Engineering)

- [3_Training_a_Model](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/3_Training_a_Model)


- [notebook_ims](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/notebook_ims)

- [plagiarism_data](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/plagiarism_data)

- [preliminary-notebook/calculate-containment](https://github.com/dilayercelik/Plagiarism-Detector/tree/master/preliminary-notebook/calculate-containment)

- [helpers.py](https://github.com/dilayercelik/Plagiarism-Detector/blob/master/helpers.py)


# Acknowledgement
This repository was made possible by Udacity, most specifically the popular Machine Learning Engineer Nanodegree, and is the fruit of my own work and effort as well.

Special credits and thanks go to the instructors and mentors at Udacity for providing high-quality content and tailored help to their students. If you'd like to know more about the specific nanodegree mentioned above, you can have a look [here](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t).

To access the syllabus of the programme, here's the [link](https://s3.amazonaws.com/iridium-content/documents/en-US/machine-learning-engineer-nanodegree-program-syllabus.pdf).
