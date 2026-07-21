# 🚢 Titanic - Machine Learning from Disaster

> End-to-End Machine Learning Pipeline for Kaggle's Titanic Competition

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Kaggle](https://img.shields.io/badge/Kaggle-Titanic-blue)
![Status](https://img.shields.io/badge/Best%20Score-0.81339-success)

---

# 📌 Project Overview

This project documents my complete end-to-end Machine Learning workflow for the famous Kaggle **Titanic: Machine Learning from Disaster** competition.

Instead of directly training a model, I approached this project like a real-world Data Science project by following every stage of the ML lifecycle:

- Data Understanding
- Data Quality Audit
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Model Development
- Hyperparameter Tuning
- Ensemble Learning
- Competition Optimization
- Advanced Group Intelligence

The objective was not only to obtain a high Kaggle score but also to understand **why each improvement worked** and build a reproducible machine learning pipeline.

---

# 🎯 Competition Objective

Predict whether a passenger survived the Titanic disaster using demographic and ticket information.

Competition Link:

https://www.kaggle.com/competitions/titanic

Evaluation Metric:

**Accuracy**

---

# 📂 Project Structure

```
Titanic-ML/

│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   ├── 04_feature_engineering.ipynb
│   ├── 05_baseline_models.ipynb
│   ├── 06_hyperparameter_tuning.ipynb
│   ├── 07_model_comparison.ipynb
│   ├── 08_ensemble_learning.ipynb
│   ├── 09_final_model_submission.ipynb
│   ├── 10_competition_optimization.ipynb
│   ├── 11_group_survival_intelligence.ipynb
│   └── 12_advanced_group_intelligence.ipynb
│
├── models/
│
├── submissions/
│
├── results/
│
└── README.md
```

---

# 📊 Dataset

The Titanic dataset contains passenger information including:

- Passenger Class
- Sex
- Age
- Fare
- Cabin
- Ticket
- Embarked Port
- Family Relationships

Target Variable

```
Survived

0 → Did not survive

1 → Survived
```

Training Dataset

- 891 passengers

Test Dataset

- 418 passengers

---

# 📖 Project Workflow

---

# Phase 1 — Data Understanding

Notebook:

```
01_data_understanding.ipynb
```

Performed

- Loaded datasets
- Understood each feature
- Created data dictionary
- Checked data types
- Checked missing values
- Statistical summaries
- Target distribution
- Baseline accuracy

Key Finding

Baseline Accuracy

```
61.6%
```

---

# Phase 2 — Data Cleaning

Notebook

```
02_data_cleaning.ipynb
```

Performed

✔ Missing value analysis

✔ Age imputation

✔ Fare imputation

✔ Embarked imputation

✔ Cabin processing

✔ Duplicate checking

✔ Data validation

✔ Data consistency checks

---

# Phase 3 — Exploratory Data Analysis

Notebook

```
03_exploratory_data_analysis.ipynb
```

Performed

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distributions
- Fare distributions
- Correlation analysis
- Family analysis
- Embarked analysis
- Cabin analysis
- Ticket analysis

Generated

- Countplots
- Histograms
- Boxplots
- Heatmaps
- Pairplots
- KDE plots

---

# Phase 4 — Feature Engineering

Notebook

```
04_feature_engineering.ipynb
```

Created Features

### Passenger Features

- Title
- AgeBand
- AgeMissing
- CabinKnown

### Family Features

- FamilySize
- IsAlone
- FamilyCategory

### Ticket Features

- TicketPrefix
- SharedTicket

### Fare Features

- LogFare
- FarePerPerson

### Interaction Features

- Sex × Class
- Title × Class

---

# Phase 5 — Baseline Models

Notebook

```
05_baseline_models.ipynb
```

Models Trained

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- Extra Trees

Evaluation

- Cross Validation
- Accuracy
- Confusion Matrix
- ROC Curve

---

# Phase 6 — Hyperparameter Tuning

Notebook

```
06_hyperparameter_tuning.ipynb
```

Performed

Grid Search

Random Search

Optimized

- Number of Trees
- Tree Depth
- Learning Rate
- Minimum Samples
- Feature Selection

---

# Phase 7 — Model Comparison

Notebook

```
07_model_comparison.ipynb
```

Compared

- Random Forest
- Gradient Boosting
- Extra Trees
- Logistic Regression

Metrics

- Cross Validation Accuracy
- Standard Deviation
- ROC AUC
- Precision
- Recall
- F1 Score

---

# Phase 8 — Ensemble Learning

Notebook

```
08_ensemble_learning.ipynb
```

Implemented

- Soft Voting
- Hard Voting
- Weighted Voting

Goal

Improve robustness and reduce variance.

---

# Phase 9 — Final Submission Pipeline

Notebook

```
09_final_model_submission.ipynb
```

Created

- Final Random Forest model
- Weighted Ensemble
- Submission generation pipeline

## Kaggle Scores

| Submission | Score |
|------------|-------|
| Random Forest | **0.75119** |
| Weighted Ensemble | **0.75119** |

---

# Phase 10 — Competition Optimization

Notebook

```
10_competition_optimization.ipynb
```

Improvements

- Better feature engineering
- Better preprocessing
- Improved model tuning
- Better ensemble strategy

## Kaggle Scores

| Submission | Score |
|------------|-------|
| Gender Baseline | **0.76555** |
| Robust Model | **0.77990** |

---

# Phase 11 — Group Survival Intelligence ⭐

Notebook

```
11_group_survival_intelligence.ipynb
```

This was the biggest improvement of the project.

New Ideas

✔ Family Survival Intelligence

✔ Ticket Group Survival

✔ Family IDs

✔ Ticket Groups

✔ Cross-Fitted Group Features

✔ Hybrid Models

✔ Ensemble Learning

✔ Demographic Group Features

## Kaggle Scores

| Submission | Score |
|------------|-------|
| Best Individual | **0.79186** |
| Group Ensemble | **0.81339** |
| Group Hybrid | **0.81339** |
| Demographic Hybrid | **0.81339** |

🏆 Best Public Score

```
0.81339
```

---

# Phase 12 — Advanced Group Intelligence

Notebook

```
12_advanced_group_intelligence.ipynb
```

Experimented With

- Nested Cross Validation
- Nested Cross-Fitting
- Demographic Group Intelligence
- Protected Passenger Groups
- Family Intelligence
- Ticket Intelligence
- Probability Ensembles
- Rule-Based Validation
- Threshold Optimization

Although significantly more advanced technically, this phase did not outperform Phase 11.

## Kaggle Scores

| Submission | Score |
|------------|-------|
| Nested Ensemble | **0.80861** |
| Validated Hybrid | **0.80861** |
| Stable Threshold | **0.80861** |
| Best Individual | **0.78947** |

Conclusion

Greater model complexity does not always improve generalization performance.

---

# 📈 Kaggle Progression

| Phase | Submission | Public Score |
|---------|------------|-------------|
| Phase 9 | Random Forest | **0.75119** |
| Phase 9 | Weighted Ensemble | **0.75119** |
| Phase 10 | Gender Baseline | **0.76555** |
| Phase 10 | Robust Model | **0.77990** |
| Phase 11 | Best Individual | **0.79186** |
| Phase 11 | Group Ensemble | **0.81339** ⭐ |
| Phase 11 | Group Hybrid | **0.81339** ⭐ |
| Phase 11 | Demographic Hybrid | **0.81339** ⭐ |
| Phase 12 | Nested Ensemble | **0.80861** |
| Phase 12 | Validated Hybrid | **0.80861** |
| Phase 12 | Stable Threshold | **0.80861** |
| Phase 12 | Best Individual | **0.78947** |

---

# 🏆 Best Competition Result

Public Leaderboard Score

```
0.81339
```

Achieved Using

- Family Survival Intelligence
- Ticket Group Intelligence
- Hybrid Ensemble
- Cross-Fitted Group Features

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- Kaggle

---

# 📚 Key Learnings

Through this project I learned:

- End-to-end Machine Learning workflow
- Data cleaning strategies
- Exploratory Data Analysis
- Feature engineering
- Model selection
- Hyperparameter tuning
- Cross Validation
- Ensemble Learning
- Competition optimization
- Leakage prevention
- Cross-fitted target encoding
- Group-based feature engineering
- Model evaluation
- Kaggle competition workflow

---

# 🚀 Future Improvements

Potential future work includes:

- XGBoost
- LightGBM
- CatBoost
- Stacking Models
- Bayesian Optimization
- Automated Feature Selection
- SHAP Explainability
- Model Interpretability
- Advanced Stacking Ensembles

---

# 👨‍💻 Author

**Acelin Nazareth**

Final Year Engineering Student

Artificial Intelligence & Data Science

Passionate about Machine Learning, Data Science and AI.

---

# ⭐ Final Result

✅ End-to-End Machine Learning Project

✅ Complete Data Science Workflow

✅ 12 Detailed Notebooks

✅ Advanced Feature Engineering

✅ Ensemble Learning

✅ Kaggle Competition Experience

🏆 **Best Public Leaderboard Score: 0.81339**
