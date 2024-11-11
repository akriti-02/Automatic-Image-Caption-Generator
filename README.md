# Automatic-Image-Caption-Generator
This repository provides code and resources to build an image caption generation model, which generates natural language descriptions of images. The model uses a pre-trained VGG16 network for feature extraction and an LSTM network for sequence generation.


# Table of Contents
Overview
Model Architecture
Dataset

# Overview
The model utilizes two main components:

VGG16 CNN Model for image feature extraction.
LSTM RNN Model for generating captions from the extracted image features.

# Model Architecture
The VGG16 model extracts a feature vector from an image. The LSTM model then takes this feature vector and, using word embeddings, generates descriptive captions word-by-word.

# Dataset
The model is trained on the dataset, which contains:

8,000 images with five captions per image.
Text files detailing training, validation, and test splits along with captions.

# References

VGG16 Model: Simonyan, K., & Zisserman, A. (2015). Very deep convolutional networks for large-scale image recognition. arXiv. https://arxiv.org/abs/1409.1556
