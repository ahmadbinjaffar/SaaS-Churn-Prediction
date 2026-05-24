# SaaS Customer Churn Prediction

## Project Overview
Customer churn is a critical metric for Software as a Service (SaaS) businesses. Retaining an existing customer is significantly more cost-effective than acquiring a new one. 

This project involves building a Machine Learning pipeline to predict which customers are at a high risk of canceling their subscriptions. By identifying these users early, businesses can implement targeted retention strategies, thereby reducing revenue leakage.

## Tech Stack & Libraries
* **Language:** Python 3
* **Environment:** Jupyter Notebook
* **Data Processing & EDA:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Classification Models, Preprocessing, Evaluation)

## Machine Learning Pipeline
This notebook walks through the entire end-to-end data science lifecycle:
1. **Data Ingestion & Cleaning:** Handling missing values, formatting data types, and dealing with outliers.
2. **Exploratory Data Analysis (EDA):** Visualizing customer demographics, account information, and usage patterns to find correlations with churn rates.
3. **Feature Engineering:** Encoding categorical variables, scaling numerical features, and creating new behavioral metrics.
4. **Predictive Modeling:** Training and tuning classification algorithms (e.g., Random Forest, Logistic Regression) to identify at-risk customers.
5. **Model Evaluation:** Assessing performance using advanced metrics beyond basic accuracy, including Precision, Recall, F1-Score, and ROC-AUC, to ensure the model effectively catches true churners.

## 📁 Repository Structure
* `Churn_Prediction_SaaS.ipynb`: The complete, runnable Jupyter Notebook containing all code, visualizations, and analytical commentary.

## How to Use
1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook or JupyterLab installed.
3. Install the required Python packages (`pip install pandas numpy scikit-learn matplotlib seaborn`).
4. Run the cells sequentially to view the data processing steps and final model outputs.
