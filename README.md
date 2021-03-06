<img src="https://circleci.com/gh/kiduskore/Operationalize-a-Machine-Learning-Microservice.svg?style=svg" alt="kiduskore"/>

**Operationalize-a-Machine-Learning-Microservice-API
Microservice Project [Udacity Cloud DevOps Engineer Nanodegree]

**Project Overview**
In this project, you will apply the skills you have acquired in this course to operationalize a Machine Learning Microservice API. 

Deploy a containerized Python flask application to serve out predictions (inference) about housing prices through API calls on on [the data source site](https://www.kaggle.com/c/boston-housing). It uses a a pre-trained, sklearn model that has been trained to predict housing prices in Boston according to several features.


**Project Tasks**
* Test your project code using linting
* Complete a Dockerfile to containerize this application
* Deploy your containerized application using Docker and make a prediction
* Improve the log statements in the source code for this application
* Configure Kubernetes and create a Kubernetes cluster
* Deploy a container using Kubernetes and make a prediction
* Upload a complete Github repo with CircleCI to indicate that your code has been tested


**START WITH
Seting the Environment**
* Create a virtualenv and activate it
     _ python3 -m venv <your_venv>
      source <your_venv>/bin/activate_
* Run `make install` to install the necessary dependencies


**Running `app.py`**

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

**Kubernetes Steps**

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl
