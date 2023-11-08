# Scones Unlimited Machine Learning Workflow

## Overview

Scones Unlimited, a leading baked goods delivery company, faces challenges in efficiently managing their delivery fleet. To streamline their operations, we are tasked with building an advanced image classification model that can classify the vehicles used by delivery drivers into two categories: bicycles and motorcycles.

The primary goal of this project is to:

To enhance the efficiency of delivery routing, the model will accurately distinguish between delivery professionals using bicycles and those on motorcycles. This way, it can assign nearby orders to bicycle riders and reserve more distant ones for motorcyclists, ultimately reducing delivery times and improving overall delivery efficiency.


## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Model Deployment](#model-deployment)
- [Model Monitoring](#model-monitoring)

## Features

- Image classification for vehicles for optimizing delivery routing.
- Utilizes AWS microservices for scalability and flexibility.
- Training jobs for fine-tuning the model to the specific needs of Scones Unlimited.
- Automated workflows using Step Functions for seamless execution.
- Model monitoring to ensure high performance and timely retraining.

### The Scones Unlimited Machine Learning Workflow consists of several key stages, each with its own set of functionalities. Below is an overview of the major steps involved:

## Data Preparation


I initially readied the image dataset for model training by arranging the images into the correct folders and making sure each category was accurately labeled.

## Model Training

Next, SageMaker was employed to train the image classification model using the carefully prepared dataset. The model was adjusted and fine-tuned as necessary to attain the best possible outcomes in line with Scones Unlimited's specific needs and preferences.

## Model Deployment

After completing the training and testing phase, I proceeded to deploy the model using AWS Lambda. This deployment enables real-time inference on new images, enabling us to generate predictions that can inform traffic management decisions.

## Model Monitoring

I established a system for continuous model monitoring to keep a close eye on how well the model is performing as time goes on. Additionally, I configured alerts to notify us and initiate retraining whenever the model's accuracy falls below a specific pre-defined level.

