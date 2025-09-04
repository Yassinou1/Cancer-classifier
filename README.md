# Cancer Classifier using a Convolutional Neural Network

A deep learning project for **classifying cancer types based on histopathological images**, implemented in a Jupyter Notebook.

## Repository Contents

- `main.ipynb` – Core notebook with data loading, model definition, training, and evaluation.
- `Kather_texture_2016_image_tiles_5000` – Directory containing the image dataset (not included in repository, must be downloaded separately).

## Description

This project explores the use of convolutional neural networks (CNNs) for classification of histopathological images of colorectal cancer.  
The goal is to preprocess image data, define and train a CNN model, and evaluate its performance.  
It serves as an application of deep learning in medical image analysis.

## Data

The dataset used in this project is the **KATHER_texture_2016_image_tiles_5000**, available on Zenodo:  
→ [KATHER_texture_2016_image_tiles_5000 (Zenodo)](https://zenodo.org/records/53169#.XFoqfs9KjOS)

This dataset contains 5,000 images of colorectal cancer histopathology tiles (150x150 px), each assigned to one of 8 classes.

## Model

The model is a sequential CNN with multiple convolutional and pooling layers, batch normalization, dropout, and dense layers.  
It uses data augmentation to improve generalization and is compiled with SGD optimizer and categorical crossentropy loss.

## Usage

1. Download the dataset from Zenodo and place it in the project directory under the folder `Kather_texture_2016_image_tiles_5000`
2. Run the Jupyter Notebook `main.ipynb` to train the model and evaluate its performance

## Results

The notebook includes evaluation of the model on a validation set and plots showing the training history (loss and accuracy curves).
