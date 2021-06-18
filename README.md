# Sentiment analysis Web Application
This repository includes files for creating and deploying a sentiment analysis model using PyTorch and SageMaker.

The project is a part of `Machine Learning Engineer Nanodegree Program` at [Udacity](https://www.udacity.com/).

## Project Overview
In this project, I am tasked with

- constructing a recurrent neural network to determine whether a movie review is Positive or Negative (the IMDB data set was defined beforehand);
- creating/ training/ deploying/ testing the model in the SageMaker framework;
- creating a Lambda Function and setting up API Gateway for interactions between a user and the deployed model.

The project includes the following files.

`SageMaker Project.ipynb`: creating/ training/ deploying/ testing a sentiment analysis model using PyTorch and SageMaker

`report.html` : An HTML export of the `SageMaker Project.ipynb` file

`train.py`, `predict.py`: python files for training and testing the model

`index.html`: web app
