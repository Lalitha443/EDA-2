# 📊 EDA-2: Adult Dataset Analysis

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the **Adult dataset** to understand patterns, clean data, and prepare it for machine learning models. It covers data preprocessing, feature scaling, and insights into both numerical and categorical variables.

## 📊 Dataset

* **File:** `adults_with_headers.csv`
* Contains demographic and employment-related attributes (age, education, occupation, income, etc.).
* Target variable: Income group classification.

## 🚀 Features

* Data cleaning and handling missing values
* Descriptive statistics for numerical and categorical features
* Scaling methods: **StandardScaler** and **MinMaxScaler**
* Comparison of scaled vs. original features
* Preparation of final dataset for model building

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```
├── data/
│   └── adults_with_headers.csv   # Dataset
├── EDA_2_ASSIGNMENT.ipynb        # Jupyter Notebook with workflow
├── results/                      # Processed datasets, outputs
└── README.md                     # Project documentation
```

## ⚡ Installation

```bash
git clone <repo-url>
cd eda-2-project
pip install -r requirements.txt
```

## ▶️ Usage

Open the notebook and run all steps to reproduce the workflow:

```bash
jupyter notebook EDA_2_ASSIGNMENT.ipynb
```

## 📈 Results

* Dataset cleaned and missing values analyzed
* Numerical features standardized and normalized
* Combined processed datasets (scaled + categorical features) created
* Ready-to-use dataset for classification models

## 📈 Future Work

* Apply feature selection techniques
* Perform visualization of key attributes and distributions
* Build classification models on the processed dataset

--
