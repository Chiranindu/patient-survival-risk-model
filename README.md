## Patient Survival Risk Prediction Using Machine Learning

## Overview
This project was developed as part of my Master’s thesis in Medical Informatics at Deggendorf Institute of Technology (Germany).

It focuses on analyzing publicly available clinical data and building predictive models to estimate patient survival outcomes.
The project applies supervised machine-learning techniques to classify patients based on survival, and explores clinical factors associated with outcome patterns.

---

## Objectives

- Identify relevant clinical and demographic factors associated with patient survival.
- Develop and evaluate machine learning models to predict survival outcomes.
- Compare the performance of different classification algorithms.
- Present insights clearly using visualizations and evaluation metrics.

---

## Dataset

- **Source**: Public clinical dataset *(used only locally for academic purposes)*
- **Format**: CSV
- **Size**: ~XXX rows × XX columns  
- **Target variable**: Patient survival status (0 = No, 1 = Yes)

- **Note**: The dataset is not included in this repository 
   Please refer to the original data source: [(https://datadryad.org/dataset/doi:10.5061/dryad.v142481)]

---

## Tools & Technologies Used

- **Python:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn  
- **Jupyter Notebook** for development and analysis  
- **Machine Learning Models:** Logistic Regression, Random Forest, Decision Tree  
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix

---

## Methodology
1. **Data Cleaning & Preprocessing**  
   - Handling missing values, outliers, normalization
2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots, correlations, and patterns
3. **Feature Selection**  
   - Identifying most influential factors
4. **Predictive Modeling**  
   - Survival prediction using classification models
5. **Visualization & Insights**  
   - Charts and tables highlighting key findings

  ## Visual Outputs

All model evaluation visualizations (ROC Curve, Confusion Matrix, Feature Importance, etc.) are displayed directly in the Jupyter Notebook.

To view them:
- Open `Risk_Prediction_Model.ipynb`
- Scroll to the evaluation and results sections at the end.

## Model Comparison & Key Results

- Best Model: Random Forest Classifier
- Accuracy: **0.94 (94%)**
- ROC-AUC Score: **0.84 (84%)**

