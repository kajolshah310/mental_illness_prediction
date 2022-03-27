# mental_illness_prediction
**Prediction of Mental Health Disorders - Depression, Anxiety and Stress in Teenagers

Motivation:-
Major career decisions of a human are to be decided between the ages 13-19 and also the physical and pyschosocial growth happens at this age. In some cases, these are affected by stress, anxiety and depression of that person. So, a model was developed to predict stress, anxiety and depression for teenagers using machine learning algorithms. Instead of just predicting a single mental disorder, in this model, we are predicting the severity scales of all three mentioned mental illnesses. 

Dataset used for this project:- https://www.kaggle.com/datasets/lucasgreenwell/depression-anxiety-stress-scales-responses?select=codebook.txt
This data was collected with an on-line version of the Depression Anxiety Stress Scales (DASS). The DASS is a 42-item self report instrument designed to measure the three related negative emotional states of depression, anxiety and tension/stress.

Dass(42) contains total of 42 questions which has to be answered. Each stress, anxiety, depression we
allocated with 14 questions.

The DASS-42 response form can be found here:- http://www2.psy.unsw.edu.au/dass/Download%20files/Dass42.pdf

The rating scale for the responses is as follows:-

1 = Did not apply to me at all 
2 = Applied to me to some degree, or some of the time
3 = Applied to me to a considerable degree, or a good part of the time
4 = Applied to me very much, or most of the time

This dataset has response values in the range 1 – 4 but ideally DASS(42) considers response values in the range 0 – 3. So, the scales in the dataset were changed from 1 – 4 to 0 – 3 . As our focus is on teenagers, the age group 13 – 19 was considered and dataset was filtered on this age group. Dataset doesn’t contain outcome columns, so based on the DASS(42) template and scales, the outcome columns for Stress, Anxiety, Depression were created by adding the respective response values. As per DASS(42), response time for each question should not be more. 

Dass(42) contains total of 42 questions which has to be answered. Each of the mental disorders - stress, anxiety, depression were allocated with 14 questions.

The DASS(42) standard scales used to measure the severity levels of the three mental disorders are as mentioned below:-

DASS (42) Scoring	  Depression	  Anxiety	  Stress
Normal	                0-9	        0-7	      0-14
Mild	                  10-13	      8-9	      15-18
Moderate	              14-20	      10-14	    19-25
Severe	                21-27	      15-19	    26-33
Extremely Severe	      28+	        20+	       34+
