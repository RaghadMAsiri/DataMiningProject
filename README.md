# Predicting Credit Approval Using Data Mining Techniques

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

## 📖 Project Overview
This project applies comprehensive data mining and machine learning techniques to predict the creditworthiness of loan applicants. Developed for the **Data Mining & Warehousing (CPIT440)** course, the system automates the credit evaluation process to assist financial institutions in minimizing lending risks, reducing human bias, and improving operational efficiency.

The task is framed as a **binary classification problem**, predicting whether a credit application should be approved or rejected based on historical applicant data.

## 📊 Dataset Information
* **Source:** OpenML Credit Approval Dataset (Dataset ID: 31).
* **Attributes:** The dataset contains a mix of categorical and numerical features representing personal and financial indicators (e.g., income, credit history, employment status, and debt level).
* **Target Variable:** Binary status (Approved / Denied).

## ✨ Key Features & Methodology
1. **Data Preprocessing & Cleaning:** Handling missing values, encoding categorical variables, and normalizing numerical distributions.
2. **Exploratory Data Analysis (EDA):** Visualizing feature correlations, class balances, and identifying significant risk indicators using Seaborn and Matplotlib.
3. **Model Building:** Implementation and comparison of multiple classification algorithms including:
   * Logistic Regression
   * Decision Trees
   * Random Forest Ensembles
4. **Performance Evaluation:** Assessing models using standard validation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC curves.

## 🏗️ Repository Structure
* **`Group4_CreditApproval_phase3.ipynb`:** Jupyter notebook containing data preprocessing, feature engineering, model training, and performance visualizations.
* **`CPIT 440phase 1+2.pdf`:** Project proposal and literature review documentation.
* **`data mining phase 4 updated.pdf`:** Final comprehensive project report summarizing experimental results and evaluation.

## 🚀 Getting Started

### Prerequisites
Ensure you have Python 3.8+ and the following packages installed:
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook

### Installation & Running
1. Clone the repository:
   git clone <repository_url>

2. Navigate to the project directory:
   cd DataMiningProject

3. Launch Jupyter Notebook to view and run the source code:
   jupyter notebook Group4_CreditApproval_phase3.ipynb

## 🔮 Future Work
* **Hyperparameter Tuning:** Implementing Grid Search or Randomized Search to further optimize classifier performance.
* **Advanced Ensemble Methods:** Integrating gradient boosting techniques such as XGBoost, LightGBM, or CatBoost.
* **Real-Time Deployment:** Developing an interactive web dashboard (e.g., Streamlit or Flask) for practical real-time credit decision-making.

---
*Developed for academic purposes to demonstrate end-to-end data mining pipelines and machine learning application in fintech.*
