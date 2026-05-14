<div align="center">

# AI Resume Screening System

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=34&duration=3500&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=AI-Powered+Resume+Screening+System;Natural+Language+Processing+%2B+Machine+Learning;Automated+Resume+Classification+Pipeline" alt="Typing Animation" />
</p>

<p align="center">
  <img src="https://img.shields.io/github/stars/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=1f6feb" />
  <img src="https://img.shields.io/github/forks/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=8957e5" />
  <img src="https://img.shields.io/github/license/Donamol-Joseph/AI-Resume-Screening-System?style=flat-square&color=238636" />
  <img src="https://img.shields.io/badge/Python-3.11-111827?style=flat-square&logo=python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat-square&logo=scikitlearn" />
</p>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0f172a,100:1e3a8a&height=2" />

</div>

## Overview

This project is an end-to-end AI-based Resume Screening System designed to automate resume classification using Natural Language Processing and Machine Learning.

The system processes resume text, performs NLP-based preprocessing, extracts textual features using TF-IDF Vectorization, and predicts the corresponding job category using machine learning models.

Built as a Kaggle notebook project, this repository demonstrates practical applications of:

* Natural Language Processing
* Text Classification
* Machine Learning Pipelines
* Feature Engineering
* Resume Analytics

---

## Dataset

Dataset Source:

```bash
/kaggle/input/datasets/snehaanbhawal/resume-dataset
```

The dataset contains resumes from multiple professional domains including:

| Categories          |
| ------------------- |
| Data Science        |
| Python Developer    |
| Java Developer      |
| HR                  |
| Testing             |
| DevOps Engineer     |
| Business Analyst    |
| Web Designing       |
| Mechanical Engineer |
| Sales               |

---

## Architecture

```mermaid
flowchart LR
    A[Resume Dataset] --> B[Text Cleaning]
    B --> C[NLP Preprocessing]
    C --> D[TF-IDF Vectorization]
    D --> E[Model Training]
    E --> F[Prediction Engine]
    F --> G[Evaluation Metrics]
```

---

## Technology Stack

<table>
<tr>
<td width="50%">

### Core Technologies

* Python
* Jupyter Notebook
* Kaggle
* Scikit-learn
* XGBoost

</td>
<td width="50%">

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Regex
* TF-IDF Vectorizer

</td>
</tr>
</table>

---

## Machine Learning Pipeline

### Data Preprocessing

* Text cleaning using regex
* Lowercase normalization
* Removal of URLs and special characters
* Noise reduction

### Feature Engineering

* TF-IDF Vectorization
* Numerical feature extraction from resume text

### Models Used

| Model         | Purpose               |
| ------------- | --------------------- |
| Random Forest | Resume Classification |
| XGBoost       | Optimized Prediction  |

### Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix
* Model Comparison

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

### Navigate to Project

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

Open:

```bash
ai-resume-screening-system.ipynb
```

---

## Key Highlights

<table>
<tr>
<td>

* Automated Resume Classification
* NLP-based Text Processing
* TF-IDF Feature Extraction
* Multiple ML Models
* Data Visualization
* End-to-End ML Workflow

</td>
<td>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Donamol-Joseph&theme=github_dark" />

</td>
</tr>
</table>

---

## Future Enhancements

* Streamlit Deployment
* Resume Ranking System
* PDF Resume Upload Support
* Deep Learning Integration
* ATS Dashboard Development

---

## Author

<div align="left">

<strong>Donamol Joseph</strong>

<br><br>

<a href="https://github.com/Donamol-Joseph">
  <img src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=white" />
</a>

<a href="https://www.linkedin.com/in/donamoljoseph/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="mailto:donajoseph272006@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

</div>

---

<div align="center">

<sub>Built with Machine Learning and Natural Language Processing</sub>

</div>
