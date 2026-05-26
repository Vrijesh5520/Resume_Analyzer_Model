# Resume Analyzer Model using NLP & Machine Learning

# Project Overview

The Resume Analyzer is an NLP and Machine Learning based project developed to automate the resume screening and classification process. The system analyzes resume text, performs preprocessing and feature extraction, and predicts the most suitable job category using Machine Learning algorithms.
The project helps recruiters and organizations reduce manual effort in resume shortlisting by automatically identifying candidate domains based on resume content.

---

# Problem Statement

Recruiters often receive thousands of resumes for multiple job roles, making manual screening time-consuming and inefficient.

The objective of this project is to build an intelligent Resume Analyzer that can:

* Automatically classify resumes into job categories
* Extract meaningful information from resume text
* Reduce recruitment screening time
* Improve candidate filtering efficiency

---

# Technologies Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Pickle

## NLP Techniques

* Text Cleaning
* Stopword Removal
* TF-IDF Vectorization

## Machine Learning Models

* Logistic Regression
* Multinomial Naive Bayes
* Linear SVC
* Random Forest Classifier

---

# Dataset Information

The dataset contains resumes from multiple professional domains such as:

* Data Science
* HR
* Python Developer
* Java Developer
* Web Designing
* DevOps Engineer
* Mechanical Engineer
* Civil Engineer
* Business Analyst
* Health and Fitness
* Sales
* Electrical Engineering
* Network Security Engineer
* Database
* Automation Testing
* SAP Developer
* Operations Manager

## Dataset Features

| Column Name | Description         |
| ----------- | ------------------- |
| Resume      | Resume text data    |
| Category    | Target job category |

---

# Workflow

## 1. Data Collection

* Loaded resume dataset containing resume text and corresponding categories.

## 2. Data Preprocessing

Performed NLP preprocessing techniques:

* Converted text to lowercase
* Removed punctuation and special characters
* Removed stopwords
* Removed unwanted symbols
* Text normalization

## 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Resume category distribution
* Frequently occurring keywords
* Resume length analysis
* Feature importance

## 4. Feature Engineering

Used **TF-IDF Vectorizer** to convert textual resume data into numerical vectors.

## 5. Model Building

Trained multiple Machine Learning models:

* Logistic Regression
* Naive Bayes
* Linear SVC
* Random Forest Classifier

## 6. Model Evaluation

Evaluated model performance using:

* Accuracy Score
* Classification Report
* Confusion Matrix

## 7. Prediction System

Built a prediction system to classify new resumes into job categories.

---

# Results

* Successfully classified resumes into multiple job categories.
* Achieved high classification accuracy using TF-IDF and Machine Learning models.
* Linear SVC and Random Forest provided strong performance for resume classification.
* The system effectively identified domain-specific resume patterns.

---

# Key Business Insights

* Automated resume screening can significantly reduce recruiter workload.
* NLP techniques improve resume understanding and candidate categorization.
* Skill-based resume classification helps recruiters shortlist candidates faster.
* Machine Learning models can identify domain-specific keywords efficiently.
* Resume classification systems can improve hiring productivity and reduce manual errors.

---

# Screenshots

## 1. Dataset Overview
<img width="1005" height="604" alt="dataset_overview" src="https://github.com/user-attachments/assets/228608b6-6c30-4faf-b2af-e11c6cd17639" />

## 2. Category-wise Resume Distribution
<img width="1372" height="574" alt="category-wise_resume_distribution" src="https://github.com/user-attachments/assets/f82ffd0e-b97a-4e45-ba0a-8705a88b65ec" />

## 3. Accuracy Comparison Chart
<img width="870" height="578" alt="accuracy-comparison" src="https://github.com/user-attachments/assets/5b1ce284-a042-48a5-8250-a01fd2abe68f" />

## 4. Confusion Matrix
<img width="679" height="580" alt="confusion_matrix" src="https://github.com/user-attachments/assets/a4b6798c-2f40-477f-84fe-575242cf113e" />

## 5. Important Features 
<img width="1136" height="690" alt="important_features" src="https://github.com/user-attachments/assets/d411499f-0a5b-44ec-8f61-99d8e8e38df8" />

## 6. Prediction Output
<img width="1372" height="517" alt="example_1" src="https://github.com/user-attachments/assets/ad8a4c2d-4392-4a62-a3c0-f23f5a9ea6be" />

---

# How to Run

## Step 1: Clone Repository

```bash
git clone https://github.com/Vrijesh5520/Resume_Analyzer_Model.git
cd Resume_Analyzer_Model
```

## Step 2: Install Required Libraries

```bash
pip install -r requirements.txt
```

## Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

## Step 4: Run Notebook

Open and run:

```bash
Resume_Analyzer_Model.ipynb
```

---

# Example

## Input Resume

```text
sample_resume1 = """
John Doe
Python Developer and Data Analyst
Skills: Python, SQL, Machine Learning, Deep Learning, NLP, Power BI, Tableau, Pandas, NumPy, Scikit-learn, Data Visualization
Projects: Built machine learning models for customer churn prediction and sentiment analysis.
Experience: Worked on predictive analytics and dashboard development.
"""
analyze_resume(sample_resume1)```

## Predicted Output

```text
Predicted Role: Data Science
ATS Match Score: 56.94 %
Resume Skills:
['data visualization', 'pandas', 'c', 'sql', 'nlp', 'machine learning', 'deep learning', 'numpy', 'power bi', 'scikit-learn', 'tableau', 'python']
Missing Skills:
['statistics', 'data analysis']
```

---

# Future Improvements

* Deploy application using Streamlit
* Add PDF/DOCX resume upload support
* Improve skill extraction system
* Integrate job recommendation engine
* Use Deep Learning and Transformer models
* Build recruiter dashboard for analytics

---
