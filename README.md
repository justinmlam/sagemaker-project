# SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

## Background:

This project is from Udacity's Deep Learning Nanodegree. I was given the task of creating, training, and fully deploying a web application that uses a Recurrent Neural Network to carry out sentiment analysis on any given review input by the user.

## Tasks and Learning Opportunities

This project required me to have the skills necessary to build a model using Amazon SageMaker, deploy and use such model, and to know how to update the model when needed. I was given all the files in this repository to work on, but in each file were sections labelled "TO-DO". In the next sections, I will go over the tasks needed.

### Data Pre-processing
- Transform the data
    - I was required to be able to transform a review, in the form of a string, into a form readable by the model.  This included tokenizing and stemming the words, removing stopwords, and splitting the review into a list of words. This project also required me to know how to transform a review into "bag-of-words" format and understanding how embedding works.
- Upload the data to S3
    - Using a cloud computing platform, I needed to upload the data to S3.

### Build and Train the PyTorch Model
- Writing the training method
    - This includes enough understanding of forward pass, backpropagation, loss functions, gradient descent, and updating weights.
- Train and test the model
    - Using cloud computing to train and test the model to make sure it is performing to an acceptable standard.

### Deploy and use the model for the web app
- Create a lambda function
    - For the API to call the model, a lambda function was created.
- Setting up an API gateway
    - Creating an API to be able to trigger the lambda function.
- Deploying and using the web app
    - Making sure that the endpoint and all components of the web application work as expected.

## Usage

To see the results, open SageMaker Project.ipynb, a jupyter notebook that has been run and saved.

