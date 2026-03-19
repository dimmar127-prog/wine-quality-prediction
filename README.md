# 🍷 Wine Quality Prediction & Analysis

<a href="https://colab.research.google.com/github/dimmar127-prog/wine-quality-prediction/blob/main/wine_quality_analysis.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

## 📌 Project Overview
Predicting wine quality is a complex task because it relies on the subtle balance of various chemical characteristics (like acidity and alcohol) rather than just the sum of individual ingredients. This project explores machine learning techniques to predict wine quality scores based on physicochemical tests.

## 🛠️ Methods & Technologies Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Numpy, Pandas, Scikit-Learn 
* **Models Evaluated:** Linear Models vs. Non-Linear Models (NN, Random Forest)

## 📊 Key Findings
* **Non-Linear Superiority:** The Random Forest model significantly outperformed the linear models. This confirms the hypothesis that wine quality is dictated by non-linear interactions between features. 
* **Feature Interactions:** The analysis highlights that predicting a subjective measure like "quality" requires algorithms capable of capturing complex relationships, such as the balance between different types of acidity and alcohol content.

## 🚀 Future Next Steps
To further optimize this model, future iterations will include:
1. **Feature Selection:** Dropping variables with the lowest correlation to the target variable to reduce noise and improve model generalization.
2. **Hyperparameter Tuning:** Optimizing the Random Forest parameters (e.g., number of estimators/trees, maximum depth) to squeeze out better performance and prevent overfitting.
