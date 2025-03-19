# Dog Breed Classification Project

## Overview
This repository contains an end-to-end multi-class image classification project aimed at identifying dog breeds from images. The project leverages TensorFlow 2.x and TensorFlow Hub to build a deep learning model capable of classifying 120 different dog breeds.

## Problem Statement
The goal is to classify the breed of a dog given an image. This can be particularly useful in real-world scenarios, such as identifying the breed of a dog from a photo taken at a cafe.

## Data
The dataset used is from Kaggle's Dog Breed Identification competition. It includes:

Training Data: Approximately 10,000+ labeled images of dogs.

Test Data: Approximately 10,000+ unlabeled images for prediction.

Dataset Link: https://www.kaggle.com/c/dog-breed-identification/data

## Evaluation
The model's performance is evaluated based on prediction probabilities for each dog breed in the test set. The evaluation metric is detailed on the Kaggle competition page.

Evaluation Link: https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## Features
Deep Learning: Utilizes TensorFlow and TensorFlow Hub for building and training the model.

Transfer Learning: Employs pre-trained models to enhance performance.

GPU Support: Ensures efficient training by leveraging GPU acceleration.

## Usage
Open in Colab: The notebook is designed to run in Google Colab with GPU support.

Data Preparation: Unzip the dataset and prepare it for training.

Model Training: Run the notebook cells to import necessary libraries, prepare data, and train the model.

Evaluation: Evaluate the model's performance on the test set.

## Dependencies
Python 3.x

TensorFlow 2.x

TensorFlow Hub

pandas

