# 🚢 Titanic Data Preprocessing & Feature Engineering

This repository contains a Jupyter Notebook that demonstrates preprocessing techniques on the Titanic dataset. It includes data extraction, cleaning, encoding, and basic preparation for machine learning pipelines.

## 📦Dataset Courtesy:  
This notebook uses the Titanic dataset provided by Mr. [Aurélien Géron](https://github.com/ageron/handson-ml2) as part of his book *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* (3rd Edition).

## 📌 Key Features

- Extraction from compressed archive
- Handling missing values:
  - Age: median imputation
  - Embarked: mode imputation
- Encoding:
  - Gender: binary encoding (male → 1, female → 0)
  - Embarked: one-hot encoding
- Feature reduction:
  - Dropped `Cabin`, `Name`, `Ticket`, and `PassengerId`
- Ready-to-use cleaned dataset for supervised learning models

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook / IPython
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib scikit-learn
