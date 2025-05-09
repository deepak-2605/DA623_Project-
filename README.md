## Please find the link attached if unable to render code on Github. You can also download the file.
https://colab.research.google.com/drive/1Vkcbu4_SI_TXNhR4lN3-QvtePwuJyI-H?usp=sharing
# Privacy-Preserving Face Matching using PCA (Eigenfaces)

**Author**: Deepak Singh

## Project Overview

This project demonstrates a privacy-preserving approach to face recognition using Principal Component Analysis (PCA), also known as the Eigenfaces method. It is intended for use in scenarios like surveillance or smart locks where storing raw face images is not desirable.

## Objectives

- Perform face recognition without using raw facial images
- Use PCA to reduce dimensionality and extract facial features
- Classify faces using k-Nearest Neighbors (k-NN)

## Dataset

The project uses the Olivetti Faces dataset from `sklearn.datasets`, containing 400 grayscale images of 40 individuals.

## Methodology

- Extract principal components (eigenfaces) using PCA
- Project face images into the PCA space
- Use k-NN for classification based on PCA-transformed data
- Visualize eigenfaces and face reconstructions

## Results

- Visualizations show that eigenfaces capture key facial features
- Classification performs well using a reduced set of features
- Demonstrates effective face matching while preserving privacy

## Dependencies

- numpy
- matplotlib
- scikit-learn
- ipywidgets
- jupyter notebook
