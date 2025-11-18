# CM2604 Machine Learning: Bank Term Deposit Prediction

This project is a coursework submission for the **CM2604 Machine Learning** module at Robert Gordon University.

The primary goal is to address a classification problem: **predicting whether a bank client will subscribe to a term deposit** based on a "Bank Marketing" dataset.

This repository contains all the necessary code, notebooks, and documentation for the project.

## Project Objective

The project involves the complete machine learning pipeline to solve this classification task. The core requirements are:
* **Dataset:** Use the [Bank Marketing Dataset from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing).
* **Models:** Implement and compare two different machine learning models:
    1.  A **Decision Tree** algorithm
    2.  A **Neural Network**
* **Evaluation:** Use appropriate evaluation metrics to compare the performance of both models and determine the most effective approach.

## Methodology

The project is broken down into four key stages, following the assessment criteria:

### 1. Corpus Preparation
This stage involves all Data Preprocessing and Feature Engineering steps.
* Loading the dataset.
* Cleaning the data (handling missing values, duplicates, etc.).
* Encoding categorical features (e.g., 'job', 'marital', 'education').
* Scaling numerical features to prepare them for the models, especially the Neural Network.
* Splitting the data into training and testing sets.

### 2. Implementation
This stage involves building the two required models.
* **Model 1 (Decision Tree):** A baseline Decision Tree classifier is built and tuned.
* **Model 2 (Neural Network):** A sequential Neural Network is designed, compiled, and trained to fit the classification problem.

### 3. Experiments
This stage focuses on training, testing, and evaluating the models.
* Experimental settings for both models are defined.
* Models are trained on the prepared training data.
* Performance is measured on the unseen test data using optimal evaluation metrics (e.g., Accuracy, Precision, Recall, F1-Score, and ROC-AUC).

### 4. Discussion
The results from the experiments are analyzed and presented in the final project report. This includes:
* A direct comparison of the Decision Tree and Neural Network performance.
* A discussion on the solution methodology.
* An analysis of any limitations encountered.
* Suggestions for possible future enhancements to the models.

## 📂 Repository Structure
