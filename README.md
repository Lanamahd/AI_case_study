# Adult Income Dataset Analysis

This repository contains an analysis of the Adult Income dataset, focusing on exploring relationships between demographic and economic factors and predicting income categories. The analysis is performed using Jupyter Notebook.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis Steps](#analysis-steps)
- [Requirements](#requirements)

## Introduction
The Adult Income dataset is widely used for exploring machine learning techniques and understanding demographic factors affecting income. This project performs data preprocessing, exploratory data analysis (EDA), and predictive modeling to classify individuals as earning more or less than \$50,000 per year.

## Dataset
The dataset used in this project is the [Adult Income dataset](https://archive.ics.uci.edu/ml/datasets/adult), derived from the 1994 Census database. It contains information such as age, education, marital status, occupation, and more.

### Features
- **Age**: The age of the individual.
- **Workclass**: Type of employment.
- **Education**: Level of education achieved.
- **Marital Status**: Marital status of the individual.
- **Occupation**: Type of work performed.
- **Relationship**: Family relationship of the individual.
- **Race**: Race of the individual.
- **Gender**: Gender of the individual.
- **Hours per week**: Weekly working hours.
- **Native country**: Country of origin.
- **Income**: Binary classification of income (<=50K, >50K).

## Analysis Steps
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
2. **Exploratory Data Analysis (EDA)**: Visualizing and summarizing the dataset to uncover patterns and insights.
3. **Modeling**: Building classification models using machine learning algorithms to predict income categories.
4. **Evaluation**: Assessing model performance using metrics such as accuracy, precision, recall, and F1-score.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

You can install the required libraries using:
```bash
pip install -r requirements.txt
