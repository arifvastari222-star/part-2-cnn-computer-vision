# Part 2 - Computer Vision Problem Formulation and CNN Prototype

## Project Overview

This project focuses on building a Convolutional Neural Network (CNN) model for image classification. 
The objective is to classify product images into different categories based on visual defects.

The dataset contains images belonging to the following classes:
- normal
- scratch
- dent
- stain

The project demonstrates how CNNs learn visual patterns using convolution layers, pooling layers, activation functions, and dense layers.

---

## Problem Type

This project represents an image classification problem because each image belongs to one specific category.

The CNN model learns visual features from images and predicts the appropriate defect class.

---

## Dataset Exploration

The dataset was analyzed by:
- counting images per class
- visualizing sample images
- checking image dimensions
- analyzing class distribution

This helped in understanding dataset balance and image characteristics before model training.

---

## Image Preprocessing

The following preprocessing steps were applied:
- resizing images to fixed dimensions
- normalizing pixel values
- train-validation split
- data augmentation

Data augmentation was used to improve model generalization and reduce overfitting.

---

## CNN Architecture

The CNN model contains:
- convolution layers
- max pooling layers
- flatten layer
- dense layers
- dropout layer
- softmax output layer

The model was compiled using:
- Adam optimizer
- categorical crossentropy loss
- accuracy metric

---

## Model Evaluation

The CNN model was evaluated using:
- validation accuracy
- validation loss
- confusion matrix
- classification report
- sample predictions
- accuracy and loss curves

The model demonstrated the ability to identify different defect categories with reasonable classification performance.

---

## Key Learnings

This project helped in understanding:
- image preprocessing
- convolution operations
- pooling layers
- CNN architecture
- image classification workflow
- model evaluation techniques

---

## Business Use Case

This type of CNN-based solution can be used in manufacturing industries for automated defect detection and quality inspection.

The system can help reduce manual inspection effort and improve consistency in product quality monitoring.

---

## Repository Structure

```text
part-2-cnn-computer-vision/
│
├── dataset/
├── sample_predictions/
├── results/
├── notebook.ipynb
├── README.md
└── requirements.txt
```

---

## Dataset Source

Dataset provided as part of the assignment dataset package.
