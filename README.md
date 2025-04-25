# Adult Income Dataset Analysis

## Overview

This project focuses on analyzing the Adult Income Dataset to explore patterns, understand relationships between features, and build classification models to predict whether an individual's income exceeds \$50K annually. The analysis involves data cleaning, feature engineering, visualization, and the implementation of machine learning models, leveraging various tools and libraries to achieve accurate results.

---

## Table of Contents

1. [Features](#features)
2. [Dataset](#dataset)
3. [Key Components](#key-components)
4. [Results and Insights](#results-and-insights)
5. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Running the Analysis](#running-the-analysis)
6. [File Descriptions](#file-descriptions)
7. [Conclusion](#conclusion)

---

## Features

- **Data Cleaning**:
  - Identifying and handling missing values.
  - Removing duplicates.
  - Dealing with outliers and inconsistent data.

- **Feature Engineering**:
  - Encoding categorical variables using OneHotEncoding and LabelEncoding.
  - Scaling numerical features using StandardScaler and MinMaxScaler.
  - Feature selection using mutual information and dimensionality reduction with Principal Component Analysis (PCA).

- **Exploratory Data Analysis (EDA)**:
  - Statistical summary and visualization of features.
  - Correlation analysis through heatmaps.
  - Insights into data distribution and feature relationships.

- **Machine Learning Models**:
  - Implementation of models such as Random Forest, Support Vector Machines (SVM), and Multi-layer Perceptron (MLP).
  - Hyperparameter tuning using GridSearchCV.
  - Evaluation using metrics like accuracy, precision, recall, and F1-score.

- **Visualization**:
  - Heatmaps, correlation matrices, and other graphical tools for data exploration.

---

## Dataset

The dataset is provided in the `data.csv` file and contains the following columns:

- **age**: Age of the individual.
- **workclass**: Type of employment (e.g., Private, Federal-Gov, Self-Employed).
- **fnlwgt**: Final weight, representing the number of people the census entry represents.
- **education**: Education level of the individual.
- **educational-num**: Number of years of education.
- **marital-status**: Marital status of the individual.
- **occupation**: Type of occupation.
- **relationship**: Relationship status of the individual.
- **race**: Ethnicity of the individual.
- **gender**: Gender of the individual.
- **capital-gain**: Capital gain recorded for the individual.
- **capital-loss**: Capital loss recorded for the individual.
- **hours-per-week**: Weekly working hours.
- **native-country**: Country of origin.
- **income**: Income class (`<=50K` or `>50K`).

---

## Key Components

1. **Data Cleaning and Preparation**:
   - Missing values were addressed, duplicates removed, and numerical columns were scaled.
   - Categorical variables were encoded for compatibility with machine learning models.

2. **Exploratory Data Analysis**:
   - Statistical summaries and visualizations provided insights into the dataset structure.
   - Correlations between features were identified to inform model building.

3. **Machine Learning Implementation**:
   - Models such as Random Forest, SVM, and MLP were trained and evaluated.
   - Hyperparameter tuning was performed to optimize model performance.

4. **Visualization**:
   - Correlation heatmaps and detailed plots were created to enhance understanding of feature relationships.

---

## Results and Insights

- **Data Distribution**:
  - Age ranged from 17 to 90, with most individuals between 28 and 48 years old.
  - Capital gain and loss were highly skewed, with a majority of values concentrated around zero.

- **Correlations**:
  - Weak positive correlations between age and education level, as well as between hours-per-week and education level.
  - Weak negative correlation between capital gain and capital loss.

- **Model Performance**:
  - Random Forest achieved the highest accuracy and F1-score among the implemented models.
  - Non-linear models like Random Forest and MLP captured complex interactions better than linear models.

---

## Getting Started

### Prerequisites

- **Python 3.8 or later**
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`
  - `torch` (optional for advanced deep learning models)

Install the required libraries using:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn torch

### Running the Analysis
1. Clone the repository:
    ```bash
    git clone https://github.com/Lanamahd/Adult_Income_Dataset_Analysis.git
    cd Adult_Income_Dataset_Analysis

2. Open the Jupyter Notebook:
    ```bash
   jupyter notebook caseStudy1.ipynb

3. Follow the notebook to execute the analysis step-by-step.

---

## File Descriptions

### **`caseStudy1.ipynb`**
- Jupyter Notebook containing the full analysis, including data cleaning, exploratory data analysis (EDA), and machine learning implementation.

### **`caseStudy1_report.pdf`**
- Detailed report summarizing the analysis, results, and insights.

### **`data.csv`**
- The dataset used for analysis, containing demographic and income-related information.

---

## Conclusion

The **Adult Income Dataset Analysis** project demonstrates the application of data science techniques to clean, analyze, and model real-world data. Insights obtained from the analysis can be used to understand factors influencing income levels and build predictive models. 

