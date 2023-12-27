# Study on Myopia

## Overview

The "Study on Myopia" project aims to develop a deep learning model for the classification of fundus images, distinguishing between normal and myopic (cataract) conditions. This README provides an overview of the project, its objectives, and a step-by-step explanation of the implemented code.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Results](#results)

## Introduction

Myopia is a prevalent eye condition that can lead to various vision impairments. This project utilizes deep learning techniques to automatically classify fundus images, aiding in the study and understanding of myopia.

## Project Structure

The project is organized into several key sections:

1. **Data Loading and Exploration:** Initial loading and exploration of the dataset to understand its structure and characteristics.

2. **Data Preprocessing:** Filtering and preprocessing of the data, including the extraction of relevant columns and visualization of sample fundus images.

3. **Data Sampling and Combination:** Balancing the dataset by sampling normal fundus images and combining them with cataract images.

4. **Labeling Data:** Labeling images based on diagnostic keywords and creating a binary label for each image.

5. **Image Loading and Preprocessing:** Loading and preprocessing images for model training and evaluation.

6. **Splitting Data:** Splitting the dataset into training and validation sets to train and assess model performance.

7. **Model Definition:** Defining a convolutional neural network (CNN) model for image classification.

8. **Model Training:** Training the CNN model on the dataset with early stopping and learning rate reduction callbacks.

9. **Model Evaluation:** Evaluating the trained model on the validation set and computing relevant metrics.

10. **Performance Visualization:** Visualizing the training and validation accuracy and loss over epochs.

11. **Sample Predictions:** Displaying sample predictions with actual and predicted labels.

## Usage

To run the project, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your-username/study-on-myopia.git
cd study-on-myopia
```

## Dependencies

Ensure you have the following dependencies installed:

- **Python 3.x**
- **Jupyter Notebook**
- **NumPy, Pandas, OpenCV, Matplotlib**
- **TensorFlow, Keras**
- **Scikit-learn, mlxtend**

Install the dependencies using:

```bash
pip install -r requirements.txt
```

## Results

The trained model has shown promising results in classifying fundus images. Key outcomes include:

- **Accuracy:** The model achieved a high accuracy rate on the validation set, indicating its ability to generalize well to new data.

- **Loss:** The loss metric, which measures the model's deviation from the actual labels, reached a satisfactory level, demonstrating effective training.

- **Confusion Matrix:** The confusion matrix provides a detailed breakdown of the model's predictions, including true positives, true negatives, false positives, and false negatives. This aids in understanding the model's performance on different classes.

These results collectively indicate the model's capability to distinguish between normal and cataract-indicative fundus images.

