# Money, Muscle and Votes: Predicting Lok Sabha Election 2019 Winners Using Machine Learning

## Project Overview

This project explores the relationship between financial status, criminal records, educational qualifications, demographic characteristics, and political party affiliation with electoral outcomes in the 2019 Indian Lok Sabha General Election.

Using machine learning classification techniques, the study attempts to predict whether a candidate wins or loses an election based on selected candidate-level attributes.

The project also compares different classification algorithms and examines the factors contributing to model predictions.

## Research Objectives

- Analyze the relationship between candidate assets and election outcomes.
- Examine the role of liabilities and criminal cases.
- Explore the influence of education, age, and gender.
- Investigate the importance of political party affiliation.
- Compare multiple machine learning classification algorithms.
- Evaluate model performance using standard classification metrics.

## Dataset Information

**Dataset:** Indian Candidates for General Election 2019  
**Source:** Kaggle – Prakrut Chauhan  
**Original Sources:** myneta.info and Election Commission results  
**Total Records:** 2,018 candidates  
**Total Columns:** 19  
**Target Variable:** `WINNER`

### Important Features

| Feature | Description |
|---|---|
| STATE | State of the candidate |
| CONSTITUENCY | Electoral constituency |
| PARTY | Political party affiliation |
| GENDER | Candidate's gender |
| AGE | Candidate's age |
| EDUCATION | Educational qualification |
| CRIMINAL_CASES | Number of criminal cases |
| ASSETS | Declared candidate assets |
| LIABILITIES | Declared liabilities |
| WINNER | Election outcome |

## Technologies Used

- **Programming Language:** Python
- **Development Environment:** Jupyter Notebook
- **Data Processing:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Version Control:** Git and GitHub

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded and explored the original election dataset.
2. Standardized column names and handled missing values.
3. Converted relevant numerical and categorical features into appropriate formats.
4. Applied logarithmic transformations to financial variables to reduce skewness.
5. Encoded categorical variables for machine learning.
6. Prepared training and testing datasets.
7. Addressed class imbalance during model development.

## Machine Learning Algorithms

Four classification algorithms were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)
4. Naive Bayes

## Model Evaluation

The models were evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### Model Comparison Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Decision Tree | 88.37% | 80.20% | 75.00% | 77.51% | 84.81% |
| Logistic Regression | 85.64% | 70.83% | 78.70% | 74.56% | 88.97% |
| KNN | 75.74% | 52.98% | 82.41% | 64.49% | 84.07% |
| Naive Bayes | 42.33% | 30.89% | 93.52% | 46.44% | 58.58% |

### Key Observations

- Decision Tree achieved the highest accuracy and F1-score in the candidate-level evaluation.
- Logistic Regression achieved the highest ROC-AUC score.
- KNN demonstrated relatively high recall but lower precision.
- Naive Bayes achieved high recall but comparatively low accuracy and precision.

## Feature Importance Analysis

Feature importance was examined to understand which variables contributed to the Decision Tree model's predictions.

Some of the prominent features included:

- Political party affiliation
- Candidate assets
- State
- Criminal cases
- Candidate age
- Candidate liabilities

The analysis highlights the predictive contribution of these variables within the trained model. Feature importance does not establish a causal relationship.

## Constituency-Based Validation

An additional validation experiment was performed by separating constituencies between training and testing datasets.

| Dataset | Candidates | Constituencies |
|---|---:|---:|
| Training | 1,606 | 433 |
| Testing | 412 | 109 |

This experiment provides an additional evaluation of model performance on candidates belonging to constituencies not included in the training dataset.

## Repository Structure

```text
Election-ML-Research/
│
├── Election_ML_project.ipynb
├── LS_2.0.csv
├── .gitignore
├── README.md
│
├── outputs/
│   ├── cleaned_election_data.csv
│   │
│   ├── figures/
│   │   ├── feature_importance.png
│   │   ├── final_confusion_matrices.png
│   │   ├── final_f1_comparison.png
│   │   ├── final_feature_importance.png
│   │   ├── final_roc_curve.png
│   │   └── model_comparison.png
│   │
│   └── tables/
│       ├── classification_reports.txt
│       ├── constituency_based_results.csv
│       ├── feature_importance.csv
│       ├── final_feature_importance.csv
│       ├── final_model_comparison.csv
│       ├── final_odds_ratios.csv
│       ├── group_feature_importance.csv
│       ├── group_odds_ratios.csv
│       ├── logistic_odds_ratios.csv
│       └── model_comparison.csv
│
└── paper/
    └── Election_ML_Research_Paper_Tejasvi.pdf
```

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/tejasvichaturvedi871/Election-ML-Research.git
```

### 2. Navigate to the Project Directory

```bash
cd Election-ML-Research
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Execute the Notebook

Open `Election_ML_project.ipynb` and run the notebook cells sequentially.

## Research Paper

The complete research paper is included in the `paper` directory.

**[View Research Paper (PDF)](paper/Election_ML_Research_Paper_Tejasvi.pdf)**

## Limitations

- The study focuses only on the 2019 Lok Sabha General Election.
- The dataset is observational; the results indicate associations rather than causation.
- Political party and constituency context may strongly influence election outcomes.
- Class imbalance can affect classification performance.
- Model predictions should not be interpreted as definitive explanations of electoral success.

## Author

**Tejasvi Chaturvedi**  
B.Sc. (Hons.) Computer Science  
Ramanujan College, University of Delhi

**Project:** Machine Learning  
**Supervisor:** Mr. Nikhil Kumar  
**Problem Number:** 49

---

*This project was developed for academic and research purposes.*

