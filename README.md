[![CircleCI](https://dl.circleci.com/status-badge/img/gh/GenetAdno/Uda-Project4/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/GenetAdno/Uda-Project4/tree/main)

## Project Overview
In this project, I have working on operationalizing microservices by deploying a machine learning inference API using docker and kubernetes.
  
### How to run this Project
In this project you will:
* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction to test the project Build it is integrated with CircleCI

## Setup the Environment

* Create a virtualenv with Python 3.7 and activate it. Refer to this link for help on specifying the Python version in the virtualenv. 
   bash
 For Linux

    python3 -m venv ~/.devops
    source ~/.devops/bin/activate
    make install
    python app.py


 For Windows


    python -m venv /.devops
    /.devops/Scripts/activate
    make install
    python app.py

 ##  Running with Docker

First you have to make sure that you have docker installed and running, then run the run_docker.sh bash script as below:

./run_docker.sh

If it throws a permission denied error, change the mode to executable using the command below

chmod +x run_docker.sh

## Running with Kubernetes

First you have to make sure that Kubernetes and kubectl command line utility are installed and well configured. Then, run the command below:

./run_kubernetes.sh

### Making Predictions
Once the service running, then you can make a call to the endpoint features data for which prediction is to be made. 
 ./make_prediction.sh


 ### CI/CD

This project integrates CircleCI for CI/CD.