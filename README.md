# 🧠 Machine Learning Projects Collection

Welcome to the **Machine Learning Projects Collection**! This repository contains a curated set of end-to-end machine learning projects, each implemented in a Jupyter Notebook. The projects cover a wide range of real-world problems, including classification, regression, clustering, and recommendation systems. Each notebook demonstrates data preprocessing, model building, evaluation, and insightful visualizations.

---

## 📚 Table of Contents

- [Project List](#project-list)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Project Details](#project-details)
- [Contributing](#contributing)
- [License](#license)

---

## 🚀 Project List

| #   | Project Name                               | Task Type      |
| --- | ------------------------------------------ | -------------- |
| 01  | Sonar Rock vs Mine                         | Classification |
| 02  | Diabetes Prediction                        | Classification |
| 03  | House Price Prediction                     | Regression     |
| 04  | Fake News Prediction                       | Classification |
| 05  | Loan Status Prediction                     | Classification |
| 06  | Car Price Prediction                       | Regression     |
| 07  | Gold Price Prediction                      | Regression     |
| 08  | Heart Disease Prediction                   | Classification |
| 09  | Credit Card Fraud Detection                | Classification |
| 10  | Medical Insurance Cost Prediction          | Regression     |
| 11  | Big Mart Sales Prediction                  | Regression     |
| 12  | Customer Segmentation (K-Means Clustering) | Clustering     |
| 13  | Parkinson's Disease Detection              | Classification |
| 14  | Titanic Survival Prediction                | Classification |
| 15  | Calories Burnt Prediction                  | Regression     |
| 16  | Spam Mail Prediction                       | Classification |
| 17  | Movie Recommendation System                | Recommendation |
| 18  | Breast Cancer Detection                    | Classification |

---

## 🛠️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/shakibkhandev/ml-projects.git
   cd ml-projects
   ```
2. **(Recommended) Create a virtual environment:**
   ```bash
   uv venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```
3. **Install dependencies:**

   ```bash
   uv pip install -r requirements.txt
   ```

   _If `requirements.txt` is not present, see the [Requirements](#requirements) section below for the list of packages to install._

4. **Start Jupyter Notebook or Lab:**
   ```bash
   jupyter-lab
   ```
   ```bash
   jupyter-notebook
   ```

---

## ▶️ Usage

- Open any notebook (`.ipynb` file) in Jupyter Notebook or JupyterLab.
- Run the cells sequentially to reproduce the results.
- Each notebook is self-contained and includes explanations, code, and visualizations.

---

## 📦 Requirements

The following Python libraries are used across the projects:

```txt
numpy
pandas
scikit-learn
matplotlib
seaborn
xgboost
nltk
scipy
difflib
```

> **Note:** Some projects may require additional libraries (e.g., `nltk` for text processing, `xgboost` for regression tasks). Install any missing packages using `pip install package-name`.

---

## 📂 Project Details

Below is a brief description of each project:

### 1. Sonar Rock vs Mine

- **Task:** Classify sonar signals as rock or mine.
- **Techniques:** Logistic Regression, Data Preprocessing

### 2. Diabetes Prediction

- **Task:** Predict whether a patient has diabetes.
- **Techniques:** Logistic Regression, Data Analysis

### 3. House Price Prediction

- **Task:** Predict house prices based on features.
- **Techniques:** XGBoost, Regression, Feature Engineering

### 4. Fake News Prediction

- **Task:** Detect fake news articles.
- **Techniques:** NLP, TF-IDF, Logistic Regression

### 5. Loan Status Prediction

- **Task:** Predict loan approval status.
- **Techniques:** SVM, Data Imputation

### 6. Car Price Prediction

- **Task:** Predict used car prices.
- **Techniques:** Linear Regression, Lasso

### 7. Gold Price Prediction

- **Task:** Predict gold prices.
- **Techniques:** Random Forest, Regression

### 8. Heart Disease Prediction

- **Task:** Predict presence of heart disease.
- **Techniques:** Logistic Regression

### 9. Credit Card Fraud Detection

- **Task:** Detect fraudulent transactions.
- **Techniques:** Logistic Regression, Data Balancing

### 10. Medical Insurance Cost Prediction

- **Task:** Predict insurance charges.
- **Techniques:** Linear Regression

### 11. Big Mart Sales Prediction

- **Task:** Predict sales for a retail store.
- **Techniques:** XGBoost, Regression

### 12. Customer Segmentation (K-Means Clustering)

- **Task:** Segment customers based on spending patterns.
- **Techniques:** K-Means Clustering

### 13. Parkinson's Disease Detection

- **Task:** Detect Parkinson's disease from biomedical data.
- **Techniques:** SVM, Feature Scaling

### 14. Titanic Survival Prediction

- **Task:** Predict survival on the Titanic.
- **Techniques:** Logistic Regression

### 15. Calories Burnt Prediction

- **Task:** Predict calories burnt during exercise.
- **Techniques:** XGBoost, Regression

### 16. Spam Mail Prediction

- **Task:** Detect spam emails.
- **Techniques:** NLP, TF-IDF, Logistic Regression

### 17. Movie Recommendation System

- **Task:** Recommend movies based on content similarity.
- **Techniques:** Content-Based Filtering, Cosine Similarity

### 18. Breast Cancer Detection

- **Task:** Classify tumors as benign or malignant.
- **Techniques:** Logistic Regression, Data Analysis

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, new projects, or bug fixes.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
