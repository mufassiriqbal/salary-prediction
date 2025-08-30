# Salary Prediction Project

This repository contains a machine learning project that predicts salaries based on various factors using different models in Python.

## 📌 Project Overview

The goal of this project is to explore how machine learning can be applied to predict salaries of candidates. The dataset contains information about candidates' experiences and other attributes. Multiple models are tested to find the best-performing one. Additionally, the trained model is saved as a **pickle file** for easy reuse.

## ⚙️ Tech Stack

* **Python**
* **Pandas** – data manipulation
* **NumPy** – numerical computations
* **Scikit-learn** – machine learning models
* **Google Colab** – development environment

## 📂 Dataset

The dataset used is `hiring (1).csv` which contains candidate details and salaries.

## 🚀 Models Implemented

1. **Linear Regression** – for continuous salary prediction.
2. **Decision Tree Classifier** – for rule-based modeling.
3. **Random Forest Classifier** – for ensemble-based prediction.

## 📊 Evaluation Metrics

* **Mean Squared Error (MSE)**
* **R² Score**

## 📝 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```

2. Open the notebook in **Google Colab** or Jupyter Notebook.

3. Upload the dataset (`salary.csv`).

4. Run all cells to train and evaluate the models.

5. Use the provided **pickle file (`LRmodel.pkl`)** to quickly load and test the trained model without retraining.

## 📈 Results

* Linear Regression provides a baseline continuous prediction.
* Decision Tree and Random Forest are compared for better accuracy.

## 🔮 Future Improvements

* Feature engineering for better prediction accuracy.
* Hyperparameter tuning for Random Forest.
* Adding more regression-based models.
* Deployment of the pickle model in a simple web app (Flask/Streamlit).
