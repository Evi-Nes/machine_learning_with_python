# Machine Learning with Python

This is part of the **Machine Learning with Python** course on **frecodecamp**. 
The files contain the implemented projects necessary to complete the course and obtain the certificate, which can be found [here](https://www.freecodecamp.org/certification/fcc1d349f5d-02ca-4bdf-ac8c-c78c9d023cc9/machine-learning-with-python-v7).

## Cat and Dog Image Classifier
For this challenge, I was tasked with creating a classifier to classify images of dogs and cats at least 63% of the time, using TensorFlow 2.0 and Keras.
Since there are a small number of training examples, I created more training data from existing training examples by using random transformations.

Finally, my model **correctly identified 68%** of the images of cats and dogs.

## Book Recommendation Engine using KNN
In this challenge, I was asked to create a book recommendation algorithm using K-Nearest Neighbors based on the ratings of the books, 
using the Book-Crossings dataset.

## Linear Regression Health Costs Calculator
In this challenge, I was asked to predict healthcare costs using a regression algorithm, given a dataset that contains information 
about different people including their healthcare costs. I used these data to predict healthcare costs based on new data.

To pass the challenge, model.evaluate must return a Mean Absolute Error of under 3500, meaning it predicts health care costs correctly within $3500.

Finally, model achieved **mean absolute error : 2770.90**

## Neural Network SMS Text Classifier

In this challenge, I needed to create a machine learning model that will classify SMS messages as either "ham" or "spam", using
the SMS Spam Collection dataset.
A "ham" message is a normal message sent by a friend and a "spam" message is an advertisement or a message sent by a company.