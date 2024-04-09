# Natural Language Processing with Disater Tweets (now X)

- URL: https://www.kaggle.com/competitions/nlp-getting-started/overview

# Project Description

Twitter, now known as X, is a real-time tool to observe emergencies with eye-witness accounts. The social media platform is an important communication outlet in today's times and even more important in times of emergency because of the immediate repsonse to people tweeting their observations. On the flip side however, Twitter also has a diverse group of user's and there are times where dialect, slang, or regional variations in language that leads to unambigous disater identifcation. We would need to differentiate between a metaphorical disater and real disaters, so that it can be utilized as a tool for quicker response time for emergency personel or quicker depolyment time for unexpected/ unprecidented disasters

The dataset used in this project contains 10,000 tweets and we will utilize natural language processing to train a model to detemine/ predict which tweets are true natural disasters and which are not. 

# Evaluation
For the competition, I submit the evaluated F1 between the predicted and expected answers

Formula:
$ F_1 = 2 * \frac{precision * recall}{precision + recall} $

Precision:
$precision = \frac{TP}{TP + FP}$

Recall:
$recall = \frac{TP}{TP + FN}$



### gloVe Url
https://www.kaggle.com/code/andreshg/nlp-glove-bert-tf-idf-lstm-explained/input
