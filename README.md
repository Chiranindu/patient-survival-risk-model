## Patient Survival Risk Prediction Using Machine Learning

This project was developed as part of my Master's thesis and aims to build a predictive model that can assess the risk of patient survival using publicly available clinical data. The model applies supervised machine learning algorithms to classify patients based on survival outcomes, with the goal of supporting early clinical decision-making.

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

- **Note**: The dataset is not included in this repository due to privacy and size constraints.  
   Please refer to the original data source: [Insert dataset link or name here]

---

  ## Tools & Technologies Used

- Python (Pandas, NumPy)
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook
- Machine Learning: Logistic Regression, Random Forest, Decision Trees
- Evaluation Metrics: Accuracy, Precision, Recall, ROC-AUC, F1-score, Confusion Matrix

---

  ## Visual Outputs

All model evaluation visualizations (ROC Curve, Confusion Matrix, Feature Importance, etc.) are displayed directly in the Jupyter Notebook.

To view them:
- Open `Risk_Prediction_Model.ipynb`
- Scroll to the evaluation and results sections at the end.

## Results Summary

- Best Model: Random Forest Classifier
- Accuracy: **0.94 (94%)**
- ROC-AUC Score: **0.84 (84%)**

