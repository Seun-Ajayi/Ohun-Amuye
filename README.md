# Ohun-Amuye
Landmark Classification &amp; Tagging for Social Media


## Project Overview
In this project, we aim to apply Convolutional Neural Networks (CNN) to build a landmark classifier. The primary goal is to automatically predict the location of an image based on any landmarks depicted in the image.

## Project Steps
### Step 1: Create a CNN to Classify Landmarks (from Scratch)
- In the cnn_from_scratch.ipynb notebook, we begin by visualizing the dataset, preparing it for training, and building a convolutional neural network from scratch. This custom CNN is designed to classify landmarks. We discuss the data preprocessing techniques used and the rationale behind our network architecture. We also export the best network using Torch Script for deployment.

### Step 2: Create a CNN to Classify Landmarks (using Transfer Learning)
- In the transfer_learning.ipynb notebook, we delve into the world of transfer learning. We investigate different pre-trained models and carefully choose one to adapt for the landmark classification task. We explain the decision-making process behind selecting the pre-trained network. The notebook covers the training and testing of this transfer-learned network and the export of the best transfer learning solution using Torch Script.

### Step 3: Deploy your algorithm in an app
- In the app.ipynb notebook, we reach the final phase of our project. Here, we leverage the power of our best model to create a user-friendly application. This app enables users to find the most likely landmarks depicted in an image. We test the model within the app and reflect on its strengths and weaknesses.

Each of these major steps is thoroughly detailed in the corresponding Jupyter Notebooks 


## Repository Structure

- **src:** Source code and project files.
- **LICENSE:**(MIT License).
- **README.md:** The main documentation file (this file).
- **app.ipynb:** Jupyter notebook for deploying the app.
- **cnn_from_scratch.ipynb:** Jupyter notebook for creating a CNN from scratch.
- **transfer_learning.ipynb:** Jupyter notebook for using transfer learning.