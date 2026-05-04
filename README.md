# Predicting Employee Attrition: An HR Analytics Approach

## 📌 Project Overview
Employee turnover is costly for businesses. This project aims to identify the key factors that lead to employee attrition and build a machine learning classification model capable of predicting whether an employee is likely to leave the company based on demographic, role, and satisfaction data.

## 📊 Dataset Information
* **Dataset Name:** IBM HR Analytics Employee Attrition & Performance
* **Source:** [Kaggle Dataset Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
* **Shape:** 1,470 rows and 35 columns
* **Target Variable:** `Attrition` (Binary: Yes/No)

### How to Download the Dataset
1. Visit the Kaggle link above.
2. Click the "Download" button.
3. Extract the `.zip` file.
4. Place the `WA_Fn-UseC_-HR-Employee-Attrition.csv` file in the same directory as the Jupyter Notebook.

## 🛠️ Proposed Methodology & Models
* **Type of Task:** Supervised Learning - Classification
* **Data Preprocessing:** Handled categorical variables using Label Encoding and One-Hot Encoding. Scaled numerical features using `StandardScaler`.
* **Models Used:** 
  1. Logistic Regression (Baseline)
  2. Random Forest Classifier
* **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, and Confusion Matrices.

## 🚀 How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have Python installed.
3. Install the required libraries by running: `pip install -r requirements.txt`
4. Download the dataset using the instructions above and place it in the root folder.
5. Open `assignment_notebook.ipynb` in Jupyter Notebook or Jupyter Lab.
6. Run all cells from top to bottom.

## 📈 Generated Results & Figures
All generated results, tables, and figures can be viewed directly within the executed Jupyter Notebook. Key visualizations include:
* Attrition Distribution Plot
* Correlation Heatmap of Numerical Features
* Confusion Matrices for both models
* Top 15 Feature Importances Chart (Random Forest)
