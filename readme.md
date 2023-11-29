# Quora Question Pairs Classifier

## Project Overview

Welcome to the Quora Question Pairs Classifier! This project aims to solve the challenge of identifying duplicate question pairs on Quora. The objective is to build a binary classification model that predicts whether a given pair of questions are duplicates or not.

### Type of ML Problem

This project is a binary classification problem. Given a pair of questions, the model needs to predict whether they are duplicate or not.

### Performance Metric

To evaluate the model's performance, we use log-loss as the primary metric, as recommended by Quora for the competition. Log-loss is a suitable metric for binary classification problems, especially when dealing with probability scores. Additionally, binary confusion metrics can also be used for a comprehensive evaluation.

## Problem Statement

Quora, a platform where users seek and contribute answers to questions, faces the challenge of multiple questions with the same intent. This can lead to inefficiencies as seekers spend more time navigating through duplicate questions, and writers find themselves answering similar queries repeatedly.

The goal of this project is to develop a robust model that can accurately classify whether question pairs are duplicates. By doing so, we aim to enhance the user experience on Quora by reducing redundancy and improving the efficiency of finding relevant answers.

## Dataset

The dataset for this project is sourced from the Quora Question Pairs competition on Kaggle. You can find the dataset and more information about the competition [here](https://www.kaggle.com/c/quora-question-pairs).

## Usage

1. **Data Preparation:** Ensure you have the dataset downloaded and stored appropriately.

2. **Environment Setup:** Set up your Python environment with the required libraries. You can use the provided `requirements.txt` file.

```bash
pip install -r requirements.txt
```

3. **Model Training:** Train the model using the provided scripts and notebooks.

4. **Model Evaluation:** Evaluate the model using log-loss and binary confusion metrics.

5. **Inference:** Deploy the trained model for making predictions on new question pairs.

## References

- [Quora Question Pairs Competition on Kaggle](https://www.kaggle.com/c/quora-question-pairs)
- [Quora Engineering Blog](https://quoraengineering.quora.com/...)
