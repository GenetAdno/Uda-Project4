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
```bash
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
