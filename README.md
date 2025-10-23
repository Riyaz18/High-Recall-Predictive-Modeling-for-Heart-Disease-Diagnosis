# High-Recall Predictive Modeling for Heart Disease Diagnosis

A critical machine learning classification pipeline focused on accurately diagnosing **Heart Disease** from patient health metrics, with a strong emphasis on **minimizing False Negatives** (maximizing Recall).

---

## Project Title & Short Description

**Title:** High-Recall Predictive Modeling for Heart Disease Diagnosis

**Description:** This project implements an end-to-end machine learning solution to classify individuals based on their probability of having heart disease. The pipeline includes detailed **Exploratory Data Analysis (EDA)**, comprehensive **preprocessing**, and the comparative tuning of multiple classification algorithms, including **KNN, SVM, Decision Trees, and Random Forest**.

---

## Problem Statement / Goal

The primary goal is to develop a predictive model capable of **accurately identifying all potential heart patients**. Given the grave implications of a missed positive diagnosis (a False Negative), the project prioritizes achieving **maximum Recall** for the positive class (class 1: heart disease) over overall accuracy.

---

## Tech Stack / Tools Used

The solution is implemented using a standard Python data science stack, with a focus on comprehensive modeling and preprocessing from Scikit-learn:

| Category | Tool / Library | Purpose |
| :--- | :--- | :--- |
| **Machine Learning**| Scikit-learn | Implementation and tuning of **KNN, SVM, Decision Trees, and Random Forest** |
| **Data Handling** | Pandas NumPy | Data loading, manipulation, and numerical operations |
| **Preprocessing**| Scikit-learn Preprocessing | Scaling, encoding, outlier treatment, and feature transformation |
| **Visualization**| Matplotlib Seaborn | Generating plots for EDA and model performance comparison |

---

## Approach / Methodology

1.  **Exploratory Data Analysis (EDA)**: Conducted extensive analysis to uncover data patterns, distributions, and bivariate relationships against the target variable.
2.  **Comprehensive Preprocessing**: Applied multiple transformation steps, including:
    * Handling missing values and treating outliers.
    * Encoding categorical features.
    * Transforming skewed features to achieve normal-like distributions.
3.  **Model Building**: Established `scikit-learn` pipelines for models requiring feature scaling (like KNN and SVM).
4.  **Model Tuning & Selection**: Implemented and tuned the various classification models with an objective function biased toward **high recall**.
5.  **Evaluation**: Compared the models using multiple metrics including **Precision, Recall, and F1-score** to determine the most effective classifier for the project's safety-critical objective.

---

## Topic Tags

MachineLearning Classification HeartDisease MedicalDiagnosis HighRecall DataPreprocessing Scikit-learn EDA Python

---

## How to Run the Project

### 1. Install Requirements

Install all necessary packages using the provided `requirements.txt` file:

```bash
pip install -r requirements.txt
