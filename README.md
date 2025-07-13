# Sales Promoter Resignation Analysis

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>

# 📊 Employee Resignation Risk Prediction

This project presents a complete data science workflow to **predict the probability that an employee will resign**, based on features extracted from internal company data.

---

## 📂 Repository Structure

```
├── LICENSE
├── README.md
├── data
│   ├── external
│   ├── interim
│   ├── processed
│   └── raw
├── models
└── notebooks
```

---

## 🎯 Objective

The objective of this project is to develop and evaluate machine learning models that can **classify whether an employee is at risk of resigning or not**. The target variable is binary:

- `RESIGN_RISK = 1`: High resignation risk (majority class)
- `RESIGN_RISK = 0`: Low resignation risk (minority class)

This classification task helps companies anticipate and mitigate attrition by identifying at-risk employees in advance.

---

## 🧰 Tools & Technologies

- Python 3.x  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- XGBoost
- Jupyter Notebook  

---

## 🚀 Getting Started

To run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sales_promoter_resignation_analysis.git
cd sales_promoter_resignation_analysis
```

### 2. (Optional) Create and activate a virtual environment

Using Conda:

```bash
conda env create -f environment.yml
conda activate sales_promoter_resignation_analysis
```

### 4. Run the notebooks

```bash
jupyter notebook
```

Open the notebooks in order:  
`1.0-data-exploration.ipynb` → `1.0-model-training.ipynb`

---

## 📊 Project Workflow

1. **Exploratory Data Analysis**
   - Distribution plots for key features
   - Correlation analysis

2. **Preprocessing**
   - Handling missing values
   - Feature selection and scaling
   - Optional: Dimensionality reduction

3. **Model Training**
   - Class imbalance inspection
   - Stratified cross-validation
   - Models tested: Logistic Regression, Random Forest, SVM, KNN, etc.
   - GridSearchCV for hyperparameter tuning

4. **Evaluation Metrics**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix

---

## 📈 Sample Results

*(Replace these with your actual metrics)*

- **Best Model:** Random Forest  
- **Macro-F1-score:** 0.836  
- **Macro-Precision:** 0.806  
- **Macro-Recall:** 0.898  

---

## 💡 Highlights

- Addressed severe class imbalance using stratified splitting and metric prioritization  
- Compared multiple classifiers with cross-validation and grid search  
- Produced meaningful insights from model interpretability  
- Delivered reproducible and modular analysis pipeline  

---

## 📌 Future Improvements

- Use SMOTE or other oversampling techniques  
- Incorporate SHAP or LIME for model explanation  
- Deploy using Streamlit as an internal HR dashboard  
- Monitor model drift and retrain with new data  

---

## 👤 Author

**Alonso González Escobedo**  
_Data Science & Machine Learning Enthusiast_    

---

## ⭐️ Show Your Support

If you found this project helpful, consider starring ⭐ the repository and connecting with me on [LinkedIn](https://www.linkedin.com/in/alonsoglez/).  
