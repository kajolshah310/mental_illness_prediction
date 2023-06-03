# Mental Illness Prediction

![Mental Health](mental_health.jpg)

## Description
This repository contains a Jupyter Notebook that focuses on the prediction of mental health disorders - depression, anxiety, and stress in teenagers. The motivation behind this project is the significant impact of stress, anxiety, and depression on the lives of teenagers, particularly during the crucial ages of 13-19. The objective of the project is to develop a machine learning model that predicts the severity scales of these mental illnesses, providing insights into the mental health of teenagers.

The project utilizes a dataset collected with an online version of the Depression Anxiety Stress Scales (DASS). The DASS is a 42-item self-report instrument designed to measure the negative emotional states of depression, anxiety, and tension/stress. The dataset used for this project can be found at [Kaggle](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses?select=codebook.txt).

The notebook showcases the following:
- Preprocessing of the dataset, including changing the scale from 1-4 to 0-3, filtering the dataset for the age group 13-19, and creating outcome columns for stress, anxiety, and depression.
- Exploration and visualization of the dataset to gain insights into the severity levels of the mental disorders.
- Implementation of machine learning algorithms to predict the severity scales of depression, anxiety, and stress.
- Evaluation of model performance using appropriate metrics.

## Features
- Prediction of mental health disorders - depression, anxiety, and stress in teenagers
- Preprocessing techniques to transform the dataset and create outcome columns
- Visualization and analysis of severity levels for mental disorders
- Application of machine learning algorithms for prediction
- Evaluation of model performance using appropriate metrics

## Dataset
The dataset used for this project is available at [Kaggle](https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses?select=codebook.txt). It was collected using an online version of the Depression Anxiety Stress Scales (DASS), which consists of 42 questions designed to measure the negative emotional states of depression, anxiety, and tension/stress. The response values in the dataset range from 1 to 4, which were converted to the range 0 to 3 to align with the DASS(42) standard scales. The dataset was filtered for the age group 13-19 to focus on teenagers.

## Usage
1. Clone the repository to your local machine using the following command:
```shell
git clone https://github.com/kajolshah310/mental_illness_prediction.git


Dataset used for this project:- https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses?select=codebook.txt
This data was collected with an on-line version of the Depression Anxiety Stress Scales (DASS). The DASS is a 42-item self report instrument designed to measure the three related negative emotional states of depression, anxiety and tension/stress.

Dass(42) contains total of 42 questions which has to be answered. Each stress, anxiety, depression we
allocated with 14 questions.

The DASS-42 response form can be found here:- http://www2.psy.unsw.edu.au/dass/Download%20files/Dass42.pdf

The rating scale for the responses is as follows:-

1 = Did not apply to me at all\
2 = Applied to me to some degree, or some of the time\
3 = Applied to me to a considerable degree, or a good part of the time\
4 = Applied to me very much, or most of the time\

This dataset has response values in the range 1 – 4 but ideally DASS(42) considers response values in the range 0 – 3. So, the scales in the dataset were changed from 1 – 4 to 0 – 3 . As our focus is on teenagers, the age group 13 – 19 was considered and dataset was filtered on this age group. Dataset doesn’t contain outcome columns, so based on the DASS(42) template and scales, the outcome columns for Stress, Anxiety, Depression were created by adding the respective response values. As per DASS(42), response time for each question should not be more. 

Dass(42) contains total of 42 questions which has to be answered. Each of the mental disorders - stress, anxiety, depression were allocated with 14 questions.

The DASS(42) standard scales used to measure the severity levels of the three mental disorders are as mentioned below:-\

**Depression:-**
Normal	                0-9\       
Mild	                  10-13\	      
Moderate	              14-20\     
Severe	                21-27\
Extremely Severe	      28+\


**Anxiety:-**
Normal	                0-7\	      
Mild	                  8-9\	      
Moderate	              10-14\	    
Severe	                15-19\
Extremely Severe	      20+\

**Stress:-**
Normal	                0-14\
Mild	                  15-18\
Moderate	              19-25\
Severe	                26-33\
Extremely Severe	      34+\

