# ASD-early-Prediction-ML
A machine learning pipeline designed to optimize early-stage Autism Spectrum Disorder (ASD) risk screening using Python.

## 📌 Project Overview
The goal of this project is to develop a predictive model that can analyze behavioral, demographic, or clinical screening data to identify early signs of ASD traits. Early detection plays a vital role in ensuring timely support and intervention.

## 🛠️ Proposed Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 📂 Project Structure (Planned)
* `data/` - For datasets (raw and cleaned)
* `notebooks/` - For Exploratory Data Analysis (EDA) and model prototyping
* `src/` - For final Python scripts and pipeline automation 

## 📌 Project Workflow

1. **Data Cleaning & Preprocessing:** Replaced missing values (`?`) with the string `'Others'`, and converted binary categorical variables (`yes` / `no`) into numerical values (`1` / `0`) to prepare them for the model.
2. 
3. **Data Splitting:** Separated the target variable (`Class/ASD`) from the feature set, and split the dataset into 75% for training and 25% for testing.
4. 
5. **Feature Scaling:** Applied `StandardScaler` to normalize the feature scales, ensuring stable and faster convergence for the classification algorithm.
6. 
7. **Training & Evaluation:** Trained a **Logistic Regression** model, achieving an excellent test accuracy of **95.8%** based on the evaluation of the Confusion Matrix.
