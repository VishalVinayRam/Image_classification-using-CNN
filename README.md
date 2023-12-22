# Image Classification with TensorFlow

This project focuses on image classification using TensorFlow, specifically for classifying happy and sad images.

## Project Overview

The goal of this project is to build a convolutional neural network (CNN) using TensorFlow to classify images into two categories: happy and sad. The dataset is organized into subdirectories, and the project includes data preprocessing, model building, training, and evaluation.

## Project Structure

- `data/`: Directory containing the image dataset with subdirectories for happy and sad images.
- `image_classification.ipynb`: Jupyter Notebook containing the project code.

## Dataset Cleaning

The dataset is cleaned to ensure that only valid image files with specified extensions (jpeg, jpg, bmp, png) are used. Images not meeting the criteria are removed from the dataset.

## Data Preprocessing

The images are loaded using TensorFlow's `image_dataset_from_directory` function. Data is normalized, and a subset is split into training, validation, and testing sets.

## Convolutional Neural Network (CNN) Model

A CNN model is built using TensorFlow's Sequential API. The model includes convolutional layers, max-pooling layers, and dense layers for classification. The model is compiled using the Adam optimizer and binary cross-entropy loss.

## Training and Evaluation

The model is trained on the training set and evaluated on the validation set. Training progress is logged using TensorBoard for visualization.

## Usage

To run the project, follow these steps:

1. Clone the repository:

   ```

   git clone https://github.com/your-username/image-classification-tensorflow.git
   cd image-classification-tensorflow
   ```
   
Open and run the Jupyter Notebook image_classification.ipynb in your preferred environment.

Ensure that you have the required dependencies installed. You can install them using:

```
pip install -r requirements.txt

```
