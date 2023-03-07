[![CircleCI](https://dl.circleci.com/status-badge/img/gh/dexterous21/project-ml-mircoservices/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/dexterous21/project-ml-mircoservices/tree/main)


# Operationalizing the machine learning application
The goal of this project is to operationalize the Python Flask app, which is available in the file app.py. Using API calls, this Flask application provides house price forecasts.


Instructions For this project to be finished, a working knowledge of Flask, Python, and Docker is sufficient. The actions taken to finish this project were as follows:


For the app to be containerized, create a Dockerfile. Use Docker and Kubernetes to deploy the containerized application. Add the code to CircleCI so that it can be tested.


Tools required to finish the project An AWS account I made use of a Docker Hub account, Cloud9 CircleCi, and Amazon Linux EC2 accounts. In the Linux instance, install Minikube and Kubectl.


app.py: This Python Flask application provides house price forecasts via API requests. 
Dockerfile: The instructions for creating an app's Docker image are found in this file. 
        This shell script, make prediction.sh, requests a prediction from the Python Flask application. 
        The instructions for setting up and operating the Docker container are contained in the makefile file. 
        The dependencies needed to run the app are listed in requirements.txt.