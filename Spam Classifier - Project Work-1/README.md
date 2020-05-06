## Introduction to the Project

Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'.

In this mission we will be using the Naive Bayes algorithm to create a model that can classify dataset SMS messages as spam or not spam, based on the training we give to the model. It is important to have some level of intuition as to what a spammy text message might look like. Usually they have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!

Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions. 

## Installation

You will be requiring following modules to run the [notebook](https://github.com/hjain5164/Udacity-NLP-Nanodegree/blob/master/Spam%20Classifier%20-%20Project%20Work-1/Bayesian_Inference_solution.ipynb)
* pandas
* sklearn

## Improvements
In this project, Naive Bayes was used. But you can go ahead and use any classifier you want to work with. Just make sure that the input vectors are compatible with the type of model or classifier you are choosing.

