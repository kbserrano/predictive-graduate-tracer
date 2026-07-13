# ML-Based Graduate Tracer System 🎓

A predictive analytics-based graduate tracer system that leverages machine learning to analyze alumni outcomes, identify employability patterns, and generate data-driven insights for educational institutions. This project aims to transform traditional graduate tracer studies from descriptive reporting into a predictive decision-support tool that supports curriculum enhancement, career guidance, quality assurance, and institutional planning.

---

## Table of Contents

1. [Project-overview
2. #installation
3. [Usage](#usageaset-information
5. [Model Training-and-evaluation
6. [Research-objectives
7. [Technologies](#technologiesucture
9. Results
10. #contributors
11. #status

---

## Project Overview

This project applies Educational Data Mining (EDM) and Machine Learning techniques to graduate tracer data to predict employment outcomes and discover factors associated with graduate employability. The system classifies graduates into employment outcome categories and provides predictive insights that can support institutional decision-making.

### Machine Learning Models

- Random Forest
- XGBoost
- LightGBM
- CatBoost

The project compares the predictive performance of multiple machine learning algorithms and identifies the best-performing model for employment outcome prediction.

### Key Features

- Graduate profiling and tracer data management
- Employment outcome classification
- Data cleaning and preprocessing pipeline
- Exploratory Data Analysis (EDA)
- Employability factor analysis
- Machine learning-based prediction
- Feature importance analysis
- Predictive analytics dashboard
- Graduate outcome reporting
- Decision-support insights for educational institutions

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/ml-based-graduate-tracer-system.git

cd ml-based-graduate-tracer-system
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## Usage

### Data Preparation

```bash
python 1_data_preparation_final.py
```

### Exploratory Data Analysis

```bash
python 2_EDA_final.py
```

### Machine Learning Modeling

```bash
# Coming Soon
```

### Web-Based System

```bash
# Flask application under development
```

---

## Dataset Information

The study utilizes anonymized graduate tracer data obtained from the City College of San Fernando, Pampanga (CCSFP). Personal identifiers such as names, addresses, student numbers, and contact information are excluded in compliance with data privacy regulations.

### Predictor Variables

- Academic Program
- Age
- Sex
- Study Hours
- Internship Experience
- Number of Mandatory Internships
- Working Student Experience
- Job Search Timing
- Number of Job Applications
- Number of Job Interviews
- Skills Index
- Learning Environment Index

### Target Variable

- Employment Outcome Classification

The employment outcome is classified into the following categories:

- Fast Employment
- Moderate Employment
- Slow Employment
- Not Employed

---

## Model Training and Evaluation

The machine learning workflow includes:

1. Data cleaning and preprocessing
2. Missing value treatment
3. Variable encoding
4. Feature engineering
5. Composite index construction
6. Exploratory Data Analysis (EDA)
7. Feature importance analysis
8. Model training and comparison
9. Performance evaluation
10. Employment outcome prediction

### Evaluation Objectives

- Determine significant employability factors
- Compare multiple machine learning algorithms
- Identify the best-performing predictive model
- Generate feature importance rankings
- Provide actionable institutional insights

---

## Research Objectives

This study seeks to:

- Identify factors that influence graduate employability.
- Predict graduate employment outcomes using machine learning.
- Compare the performance of Random Forest, XGBoost, LightGBM, and CatBoost models.
- Discover important employability patterns from alumni data.
- Support curriculum enhancement through data-driven insights.
- Assist career guidance initiatives and intervention planning.
- Strengthen institutional decision-making through predictive analytics.
---

## Technologies

### Data Analytics & Machine Learning

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

### Machine Learning

- Random Forest
- XGBoost
- LightGBM
- CatBoost

### Web Development

- Flask
- HTML
- CSS
- Bootstrap

### Data Sources

- Excel
- CSV

### Version Control

- Git
- GitHub

---

## Project Structure

```text
ml-based-graduate-tracer-system/
│
├── data/
├── notebooks/
├── screenshots/
├── documentation/
│
├── 1_data_preparation_final.py
├── 2_EDA_final.py
├── README.md
├── requirements.txt
│
└── flask_app/  (In Progress)
```

---

## Results

🚧 Work in Progress

Planned outputs include:

- Employment outcome prediction
- Feature importance rankings
- Employability factor analysis
- Predictive dashboards
- Institutional reports and recommendations

---

## Contributors

### Kirson B. Serrano

- Graduate Researcher
- Data Analytics Researcher
- Machine Learning Enthusiast
- College Professor

GitHub Profile: *Add your GitHub profile URL here*

---

## Status

🚧 **Work in Progress**

This project is currently under active development as part of graduate research in Data Analytics and Machine Learning.


## Features

- Graduate profiling and tracer data management
- Employment outcome classification and analysis
- Data cleaning and preprocessing pipeline
- Exploratory Data Analysis (EDA) and visualization
- Employability factor analysis
- Machine learning-based employment outcome prediction
- Feature importance and predictive insights generation
- Interactive analytics dashboard
- Graduate outcome reporting and monitoring
- Decision-support tools for curriculum enhancement and institutional planning

## Technologies

### Programming & Analytics
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

### Machine Learning
- Random Forest
- XGBoost
- LightGBM
- CatBoost

### Database
- PostgreSQL / MySQL

### Web Development
- Flask
- HTML
- CSS
- Bootstrap

### Version Control
- Git
- GitHub
