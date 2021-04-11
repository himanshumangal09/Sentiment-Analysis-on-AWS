# SageMaker Deployment Project on AWS

This project 'Sagemaker Deployment' which consists in deploying a Sentiment Analysis model using RNN in the Amazon AWS SageMaker tool. The notebook and Python files provided here result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews.

In the final architecture AWS API Gateway and AWS Lambda functions is used as well. The application architecture diagram is:

![Web app Diagram](./Web&#32;App&#32;Diagram.svg) 


## Setup Instructions
The notebooks provided in this repository are intended to be executed using Amazon's SageMaker platform. The following is a brief set of instructions on setting up a managed notebook instance using SageMaker, from which the notebooks can be completed and run.

### Log in to the AWS console and create a notebook instance

### Log in to the AWS console and go to the SageMaker dashboard. 
Click on 'Create notebook instance'. Change the region to North Virginia and apply for limit increase of ml.p2.xlarge(sagemaker) instance to 1. Also we need to apply limit increase of ml.p2.xlarge training (sagemaker training) to 1. Additionally We need to create IAM role, Lambda function, API gateway. Instructions are provided in the notebook.

* Use git to clone the repository into the notebook instance
* git clone https://github.com/himanshumangal09/Sentiment-Analyis-on-AWS.git

After you have finished, close the terminal window.

Open and run the notebook
jupyter notebook SageMaker Project.ipynb


## Web app final result

The final project will be executed in a simple html page which can be deployed anywhere. 

You will see the following:

![Web app example](./webapp.gif) 
