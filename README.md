# Titanic Passenger Survival Analysis and Prediction

## 🚢 Project Overview

This project aims to build a machine learning model that can predict whether a passenger survived the Titanic tragedy or not. Using the classic dataset from the Kaggle competition, this project covers the entire data science workflow from data cleaning to model evaluation.

## 💾 Dataset

The dataset used is from the Kaggle https://www.kaggle.com/datasets/yasserh/titanic-dataset. This dataset contains demographic and travel details for 891 passengers.

## ⚙️ Project Workflow

The workflow in this notebook includes several main stages:
1.  **Exploratory Data Analysis (EDA):** Understanding patterns and insights from the data through descriptive statistics and visualization.
2.  **Data Cleaning:** Handling missing values in columns such as 'Age', 'Cabin', and 'Embarked'.
3.  **Feature Engineering:** Creating new, relevant features from existing data (e.g., 'FamilySize' from 'SibSp' and 'Parch', or 'Title' from passenger names) to improve model performance.
4.  **Data Visualization:** Creating various plots using Matplotlib and Seaborn to illustrate relationships between features.
5.  **Modeling:** Training with classification models Random Forest.
6.  **Model Evaluation:** Evaluating the performance of the best model using metrics like accuracy, precision, recall, and the confusion matrix.

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy** (For data manipulation and analysis)
* **Matplotlib & Seaborn** (For data visualization)
* **Scikit-learn** (For building and evaluating machine learning models)
* **Jupyter Notebook** (As the working environment)

## 📊 Results

The best model produced RandomForestClassifier achieved an accuracy of about **80.3%** on the test data.

## 🚀 How to Run

1.  Clone this repository.
2.  Install all the required dependencies from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```
3.  Open and run the `.ipynb` file using Jupyter Notebook or Jupyter Lab.
