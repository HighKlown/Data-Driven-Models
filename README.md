# Generative Model Testing with Naive Bayes

## Project Overview

This Python project focuses on testing a generative model using the Naive Bayes algorithm. The project involves supervised learning, where the goal is to classify flower species based on the provided dataset. The dataset consists of both training and test data, with features extracted from flower samples.

## Data Source

The dataset is sourced from the scikit-learn library, a popular machine learning library in Python. It includes information on various flower species, and the features used for classification are the sepal length and sepal width.

### Features:
- Sepal Length
- Sepal Width

## Naive Bayes Algorithm

The Naive Bayes algorithm is employed for its simplicity and efficiency in classification tasks. It assumes that features are conditionally independent given the class label, making it well-suited for this type of generative model testing.

## Project Structure

The project is structured as follows:

- `data/`: Contains the dataset files.
  - `train_data.csv`: Training data for model training.
  - `test_data.csv`: Test data for evaluating the trained model.

- `src/`: Holds the source code files.
  - `naive_bayes_model.py`: Implementation of the Naive Bayes generative model.
  - `data_processing.py`: Module for loading and processing the dataset.
  - `main.py`: Main script for training the model and evaluating its performance.

- `README.md`: This file, providing an overview of the project, its purpose, and the steps to run the code.

## Getting Started

To run the project, follow these steps:

1. Ensure you have Python installed on your system.
2. Install the required dependencies using the following command:
   ```bash
   pip install -r requirements.txt

