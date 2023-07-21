# Land Use Scene Classification using InceptionV3

This repository contains code for land use scene classification using the InceptionV3 deep learning model. The project aims to accurately classify images into different land use categories.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The land use scene classification project leverages the InceptionV3 model, pre-trained on the ImageNet dataset, and fine-tuned on a custom dataset consisting of 21 land use classes. The code provided includes model implementation, training, evaluation metrics, and prediction examples.

## Installation

To run the code locally, you need to have the following dependencies installed:

- Python (version 3.12)
- TensorFlow (version 2.12)
- Numpy (version 1.25.0)
- Scikit-Learn (version 1.2.2)
  

You can install the required packages by running the following command:

  ```shell
  pip install tensorflow numpy pillow scikit-learn
  ```


## Dataset 

This dataset contains satellite images of 21 classes such as buildings, baseball fields, freeways, etc. The original size of the images is 256x256 pixels. Originally there were 100 images per class. After augmenting each image 4 times the size of each class was brought up to 500 images. This allows for making a more robust model.

You can access and download the dataset in `.zip` format from __https://www.kaggle.com/datasets/apollo2506/landuse-scene-classification__ and unzip it. 

## Usage 

**Prepare your dataset:**

  Organize your dataset into separate directories based on class labels.
  Ensure that the images are properly labeled and in a compatible format.

**Train the model:**

  Adjust the hyperparameters and settings in the file to suit your needs.


**Evaluate the model:**

  Run the evaluation script to measure the performance of the trained model.

**Make predictions:**

  Use the trained model to predict the class of new, unseen images.

## Contributing
  Contributions are welcome! If you find any issues or have suggestions for improvement, please submit a pull request or open an issue.
