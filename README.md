# Hybrid Deep Learning Model for Precipitation Prediction

This repository contains the implementation of a hybrid deep learning model that combines Convolutional Neural Networks (CNNs) for satellite cloud images and Recurrent Neural Networks (RNNs) for meteorological data to predict precipitation categories (No Rain, Light Rain, Moderate Rain, Heavy Rain) up to three days in advance.

## Repository Structure

- `visualization.ipynb`: This notebook contains code for visualizing the satellite cloud images and meteorological data. It includes various plots and charts to help understand the data distribution and patterns.

- `pre-processing.ipynb`: This notebook handles data preprocessing. It includes steps for cleaning, normalizing, and preparing the satellite images and meteorological data for training the hybrid model.

- `hybrid-CNN-RNN.ipynb`: This notebook implements the hybrid CNN-RNN model. It combines the strengths of CNNs for feature extraction from images and RNNs for handling sequential data. The model is trained to predict precipitation categories for one, two, and three days in advance.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/hybrid-cnn-rnn-precipitation-prediction.git
   cd hybrid-cnn-rnn-precipitation-prediction
   
2. **Install the required packages:**
  ```bash
  Copy code
  pip install -r requirements.txt
