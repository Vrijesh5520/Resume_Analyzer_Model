# Resume Analyzer using NLP & Machine Learning

## Overview

The **Resume Analyzer** is an NLP and Machine Learning based project that automatically classifies resumes into different job categories based on resume content. The project performs text preprocessing, feature extraction using TF-IDF, model training, evaluation, and prediction.
This project helps recruiters and HR teams automate the resume screening process by identifying the most suitable domain for a candidate.

---

# Features

* Resume text preprocessing and cleaning
* NLP-based text normalization
* Stopwords removal and lemmatization
* TF-IDF feature extraction
* Multiple Machine Learning models comparison
* Resume category prediction
* Model evaluation with accuracy and confusion matrix
* Feature importance visualization
* Model saving using Pickle

---

# Technologies Used

## Programming Language

* Python

## Libraries & Frameworks

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLTK
* Pickle

## Machine Learning Models

* Logistic Regression
* Multinomial Naive Bayes
* Linear SVC
* Random Forest Classifier

---

# Project Workflow

## 1. Data Collection

* Loaded resume dataset containing resume text and category labels.

## 2. Data Cleaning

Performed text preprocessing such as:

* Lowercase conversion
* Removing punctuation
* Removing special characters
* Removing stopwords

## 3. Exploratory Data Analysis (EDA)

* Category-wise resume distribution
* Most frequent words analysis
* Resume length analysis
* Word frequency visualization

## 4. Feature Engineering

* Converted resume text into numerical vectors using **TF-IDF Vectorizer**.

## 5. Model Training

Trained and compared multiple machine learning models:

* Logistic Regression
* Naive Bayes
* Linear SVC
* Random Forest

## 6. Model Evaluation

Evaluated models using:

* Accuracy Score
* Classification Report
* Confusion Matrix

## 7. Model Saving

Saved trained model and vectorizer using Pickle:

* `best_model.pkl`
* `tfidf.pkl`
* `label_encoded.pkl`

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Resume-Analyzer.git
cd Resume-Analyzer
```

# How to Run

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Resume_Analyzer_Model.ipynb
```

---

# Sample Use Cases

* Automated resume screening
* HR recruitment automation
* Resume domain classification
* Candidate profile filtering
* NLP text classification learning project

---

# Model Performance

The project compares multiple ML algorithms and selects the best-performing model based on accuracy.

Evaluation metrics used:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

# Future Improvements

* Deploy project using Streamlit or Flask
* Add PDF/DOCX resume upload feature
* Improve skill extraction system
* Integrate job recommendation engine
* Add deep learning models

---

Example folder structure:

```bash
Resume-Analyzer-Model/
│
├── screenshots/
│   ├── category_distribution.png
│   ├── confusion_matrix.png
│   ├── model_accuracy.png
│   └── prediction_output.png
```

## Add Screenshots in README

### Resume Category Distribution

```markdown
![Category Distribution](screenshots/category_distribution.png)
```

### Confusion Matrix

```markdown
![Confusion Matrix](screenshots/confusion_matrix.png)
```

### Prediction Output

```markdown
![Prediction Output](screenshots/prediction_output.png)
```

---

# Example Prediction

## Input Resume Text

```text
Experienced Python Developer skilled in Machine Learning, Data Analysis, Pandas, NumPy, Scikit-learn, and SQL.
```

## Predicted Category

```text
Python Developer
```

---
