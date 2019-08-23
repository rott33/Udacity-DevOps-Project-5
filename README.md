[![CircleCI](https://circleci.com/gh/rott33/Udacity-Project-5.svg?style=svg)](https://circleci.com/gh/rott33/Udacity-Project-5)

## Project Overview

In this project, we have applied the skills acquired in this course to operationalize a Machine Learning Microservice API. 

We have been provided with a pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). This project demonstrates the ability to operationalize a Python flask app—in a provided file, `app.py`—that serves out predictions (inference) about housing prices through API calls. This project could be extended to any pre-trained machine learning model, such as those for image recognition and data labeling.

### Project Tasks

Our project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/), which is an open-source system for automating the management of containerized applications. In this project we have:
* Tested our project code using linting
* Completed a Dockerfile to containerize this application
* Deployed our containerized application using Docker and made a prediction
* Improved the log statements in the source code for this application
* Configured Kubernetes to create a Kubernetes cluster
* Deployed a container using Kubernetes and made a prediction
* Uploaded a complete Github repo with CircleCI to indicate that our code has been tested

You can find a detailed [project rubric, here](https://review.udacity.com/#!/rubrics/2576/view).

---

## Setup the Environment

* Create a virtualenv and activate it
* Run `make install` to install the necessary dependencies

### Running `app.py`

1. Standalone:  `python app.py`
2. Run in Docker:  `./run_docker.sh`
3. Run in Kubernetes:  `./run_kubernetes.sh`

### Kubernetes Steps

* Setup and Configure Docker locally
* Setup and Configure Kubernetes locally
* Create Flask app in Container
* Run via kubectl

### Prediction Testing

With the app running locally, execute: `./make_prediction.sh`
