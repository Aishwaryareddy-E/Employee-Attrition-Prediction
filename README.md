# Employee Attrition Prediction System

An end-to-end Data Science and Machine Learning project that predicts employee attrition, analyzes salary trends, and groups employees using HR analytics data.

This project helps organizations identify employees at risk of leaving and supports data-driven HR decision-making using machine learning techniques.

---

# Project Objectives

* Predict whether an employee is likely to leave the company
* Predict employee salary using regression models
* Group similar employees using clustering
* Perform HR analytics using machine learning and data visualization

---

# Technologies Used

## Programming & Analysis

* Python
* Jupyter Notebook

## Libraries

* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

# Machine Learning Tasks

## 1. Employee Attrition Prediction (Classification)

Predict whether an employee will:

* Stay in the company
* Leave the company

### Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Neural Network (MLPClassifier)

### Evaluation Metric

* Accuracy Score

---

## 2. Salary Prediction (Regression)

Predict employee monthly salary using regression techniques.

### Models Used

* Linear Regression
* Ridge Regression

### Evaluation Metric

* R² Score

---

## 3. Employee Segmentation (Clustering)

Group employees based on:

* Income
* Experience
* Age
* Job satisfaction
* Years at company

### Algorithm Used

* K-Means Clustering

---

# Dataset Information

Dataset used:
IBM HR Analytics Employee Attrition Dataset

Dataset contains:

* 1470 employee records
* 35 HR-related features

Example Features:

* Age
* Department
* JobRole
* MonthlyIncome
* JobSatisfaction
* OverTime
* YearsAtCompany
* Attrition

---

# Project Workflow

## Step 1 — Data Loading

* Load CSV dataset using pandas

## Step 2 — Exploratory Data Analysis (EDA)

* Analyze employee attrition distribution
* Explore salary and satisfaction patterns
* Understand employee demographics

## Step 3 — Data Preprocessing

* Remove unnecessary columns
* Encode categorical variables
* Scale numerical features

## Step 4 — Clustering

* Group employees using K-Means clustering

## Step 5 — Regression Modeling

* Train salary prediction models
* Compare model performance using R² score

## Step 6 — Classification Modeling

* Train attrition prediction models
* Compare accuracy across models

## Step 7 — Model Evaluation

* Compare all models
* Select best-performing algorithms

---

# Key Insights

* Employees working overtime showed higher attrition
* Low job satisfaction increased resignation probability
* Younger employees were more likely to leave
* Salary strongly depended on experience and job role

---

# Project Structure

```text
Employee-Attrition-Prediction-System/
│
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── notebooks/
│   ├── Employee_Attrition_Clean.ipynb
│   └── Employee_Attrition_Prediction.ipynb
│
├── scripts/
│   ├── complete_detailed_guide.py
│   └── create_notebook.py
│
├── README.md

```

---

# How to Run the Project

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/Employee-Attrition-Prediction-System.git
```

## 2. Navigate to Project Folder

```bash
cd Employee-Attrition-Prediction-System
```

## 3. Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

* Employee_Attrition_Prediction.ipynb

---

# Results

## Classification

Random Forest and Neural Network achieved strong employee attrition prediction performance.

## Regression

Ridge Regression improved salary prediction by reducing overfitting.

## Clustering

Employees were successfully segmented into meaningful groups using K-Means.

---

# Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Classification
* Regression
* Clustering
* Model Evaluation
* Machine Learning Workflow
* HR Analytics

---

# Future Improvements

* Use SMOTE for handling class imbalance
* Add SHAP explainability
* Deploy using Streamlit or FastAPI
* Improve evaluation using Precision, Recall, and F1-score
* Add dashboard visualizations

---

# Author

Aishwarya Reddy

Data Science & Machine Learning Enthusiast


