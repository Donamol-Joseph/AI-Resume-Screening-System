<div align="center">

# AI Resume Screening System

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=30&duration=3500&pause=1000&color=58A6FF&center=true&vCenter=true&width=850&lines=AI-Powered+Resume+Screening+System;Machine+Learning+and+NLP+Pipeline;Automated+Resume+Classification" alt="Typing Animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=1f6feb" />
  <img src="https://img.shields.io/github/stars/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=1f6feb" />
  <img src="https://img.shields.io/github/forks/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=8957e5" />
  <img src="https://img.shields.io/badge/Python-3.11-111827?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat-square&logo=scikitlearn" />
</p>

</div>

---

## Overview

The AI Resume Screening System is a machine learning and natural language processing project designed to automate resume classification across multiple professional domains.

The system processes resume text, performs preprocessing and feature extraction using TF-IDF Vectorization, and predicts the corresponding job category using machine learning models.

This project demonstrates practical applications of:

* Natural Language Processing
* Text Classification
* Feature Engineering
* Machine Learning Pipelines
* Resume Analytics

---

## Dataset

Dataset used from Kaggle:

```bash
/kaggle/input/datasets/snehaanbhawal/resume-dataset
```

The dataset contains resumes from multiple categories including:

| Categories          |
| ------------------- |
| Data Science        |
| Python Developer    |
| Java Developer      |
| HR                  |
| DevOps Engineer     |
| Business Analyst    |
| Web Designing       |
| Testing             |
| Sales               |
| Mechanical Engineer |

---

## Workflow

```mermaid
flowchart LR
    A[Resume Dataset] --> B[Text Cleaning]
    B --> C[NLP Preprocessing]
    C --> D[TF-IDF Vectorization]
    D --> E[Model Training]
    E --> F[Prediction]
    F --> G[Evaluation]
```

---

## Technology Stack

| Category             | Technologies                       |
| -------------------- | ---------------------------------- |
| Programming Language | Python                             |
| Libraries            | Pandas, NumPy, Matplotlib, Seaborn |
| NLP Techniques       | Regex, TF-IDF Vectorization        |
| Machine Learning     | Random Forest, XGBoost             |
| Environment          | Kaggle Notebook, Jupyter Notebook  |

---

## Core Capabilities

* Automated Resume Classification
* NLP-based Text Processing
* TF-IDF Feature Extraction
* Machine Learning Model Training
* Model Evaluation and Comparison
* Data Visualization and Analysis
* End-to-End Prediction Pipeline

---

## Machine Learning Pipeline

### Data Preprocessing

* Removal of URLs and special characters
* Text normalization and cleaning
* Lowercase transformation
* Noise reduction using regex

### Feature Engineering

* TF-IDF Vectorization
* Numerical feature transformation from textual resume data

### Models Used

| Model                    | Purpose               |
| ------------------------ | --------------------- |
| Random Forest Classifier | Resume Classification |
| XGBoost Classifier       | Optimized Prediction  |

### Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix
* Model Performance Comparison

---

## Project Structure

```bash
AI-Resume-Screening-System/
│
├── ai-resume-screening-system.ipynb
├── README.md
├── LICENSE
└── dataset/
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/Donamol-Joseph/AI-Resume-Screening-System.git
```

### Navigate to Project Directory

```bash
cd AI-Resume-Screening-System
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

### Launch Notebook

```bash
jupyter notebook
```

Open the notebook:

```bash
ai-resume-screening-system.ipynb
```

---

## Results

The trained models successfully classify resumes into their respective job categories using NLP and machine learning techniques.

The project demonstrates effective performance in identifying resume domains from textual content.

---

## Future Improvements

* Streamlit or Flask Deployment
* Resume Ranking System
* PDF Resume Upload Support
* Deep Learning Integration
* ATS Dashboard Development

---

## Author

**Donamol Joseph**

<p>
<a href="https://github.com/Donamol-Joseph">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/donamoljoseph/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:donajoseph272006@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
</p>

---

<div align="center">

Built using Machine Learning and Natural Language Processing

</div>
