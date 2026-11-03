\# Money, Muscle and Votes: Predicting Lok Sabha Election 2019 Winners Using Machine Learning



\## Project Overview

This project analyzes Indian Lok Sabha Election 2019 candidate data to explore whether financial assets, liabilities, criminal cases, education, age, gender, and political party affiliation are associated with election outcomes.



Machine learning classification algorithms are used to predict whether a candidate wins or loses an election.



\## Research Objectives

\- Analyze the relationship between candidate assets and election outcomes.

\- Study the role of criminal cases and liabilities.

\- Examine the influence of political party affiliation.

\- Compare different machine learning classification models.

\- Evaluate model performance using classification metrics.



\## Dataset

\*\*Dataset:\*\* Indian Candidates for General Election 2019



\*\*Source:\*\* Kaggle – Prakrut Chauhan  

\*\*Original data source:\*\* myneta.info candidate affidavits and Election Commission results.



The dataset contains candidate information such as:

\- State and constituency

\- Political party

\- Gender and age

\- Education

\- Criminal cases

\- Assets and liabilities

\- Election results



\## Technologies Used

\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn



\## Methodology

1\. Data loading and exploration

2\. Data cleaning and preprocessing

3\. Missing-value handling

4\. Log transformation of financial variables

5\. Categorical feature encoding

6\. Model training and evaluation

7\. Feature importance and odds-ratio analysis

8\. Constituency-based validation



\## Machine Learning Models

\- Logistic Regression

\- Decision Tree

\- K-Nearest Neighbors (KNN)

\- Naive Bayes



\## Model Evaluation



| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |

|---|---:|---:|---:|---:|---:|

| Decision Tree | 88.37% | 80.20% | 75.00% | 77.51% | 84.81% |

| Logistic Regression | 85.64% | 70.83% | 78.70% | 74.56% | 88.97% |

| KNN | 75.74% | 52.98% | 82.41% | 64.49% | 84.07% |

| Naive Bayes | 42.33% | 30.89% | 93.52% | 46.44% | 58.58% |



\*Note: These results represent the candidate-level test evaluation. Constituency-based validation is also included in the repository.\*



\## Repository Structure



```text

Election-ML-Research/

│

├── Election\_ML\_project.ipynb

├── LS\_2.0.csv

├── outputs/

│   ├── cleaned\_election\_data.csv

│   ├── figures/

│   └── tables/

│

├── paper/

│   └── Election\_ML\_Research\_Paper\_Tejasvi.pdf

│

└── .gitignore

```



\## Research Paper

The complete research paper is available here:



\[Download Research Paper (PDF)](paper/Election\_ML\_Research\_Paper\_Tejasvi.pdf)



\## How to Run

1\. Clone this repository.

2\. Install the required Python libraries.

3\. Open `Election\_ML\_project.ipynb` in Jupyter Notebook.

4\. Ensure the dataset `LS\_2.0.csv` is in the project directory.

5\. Run the notebook cells sequentially.



Install dependencies:



```bash

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

```



\## Limitations

\- The analysis focuses only on the 2019 Lok Sabha General Election.

\- The dataset is observational; results indicate associations, not causation.

\- Political party and constituency context may strongly influence election outcomes.

\# Money, Muscle and Votes: Predicting Lok Sabha Election 2019 Winners Using Machine Learning



\## Project Overview

This project analyzes Indian Lok Sabha Election 2019 candidate data to explore whether financial assets, liabilities, criminal cases, education, age, gender, and political party affiliation are associated with election outcomes.



Machine learning classification algorithms are used to predict whether a candidate wins or loses an election.



\## Research Objectives

\- Analyze the relationship between candidate assets and election outcomes.

\- Study the role of criminal cases and liabilities.

\- Examine the influence of political party affiliation.

\- Compare different machine learning classification models.

\- Evaluate model performance using classification metrics.



\## Dataset

\*\*Dataset:\*\* Indian Candidates for General Election 2019



\*\*Source:\*\* Kaggle – Prakrut Chauhan  

\*\*Original data source:\*\* myneta.info candidate affidavits and Election Commission results.



The dataset contains candidate information such as:

\- State and constituency

\- Political party

\- Gender and age

\- Education

\- Criminal cases

\- Assets and liabilities

\- Election results



\## Technologies Used

\- Python

\- Jupyter Notebook

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn



\## Methodology

1\. Data loading and exploration

2\. Data cleaning and preprocessing

3\. Missing-value handling

4\. Log transformation of financial variables

5\. Categorical feature encoding

6\. Model training and evaluation

7\. Feature importance and odds-ratio analysis

8\. Constituency-based validation



\## Machine Learning Models

\- Logistic Regression

\- Decision Tree

\- K-Nearest Neighbors (KNN)

\- Naive Bayes



\## Model Evaluation



| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |

|---|---:|---:|---:|---:|---:|

| Decision Tree | 88.37% | 80.20% | 75.00% | 77.51% | 84.81% |

| Logistic Regression | 85.64% | 70.83% | 78.70% | 74.56% | 88.97% |

| KNN | 75.74% | 52.98% | 82.41% | 64.49% | 84.07% |

| Naive Bayes | 42.33% | 30.89% | 93.52% | 46.44% | 58.58% |



\*Note: These results represent the candidate-level test evaluation. Constituency-based validation is also included in the repository.\*



\## Repository Structure



```text

Election-ML-Research/

│

├── Election\_ML\_project.ipynb

├── LS\_2.0.csv

├── outputs/

│   ├── cleaned\_election\_data.csv

│   ├── figures/

│   └── tables/

│

├── paper/

│   └── Election\_ML\_Research\_Paper\_Tejasvi.pdf

│

└── .gitignore

```



\## Research Paper

The complete research paper is available here:



\[Download Research Paper (PDF)](paper/Election\_ML\_Research\_Paper\_Tejasvi.pdf)



\## How to Run

1\. Clone this repository.

2\. Install the required Python libraries.

3\. Open `Election\_ML\_project.ipynb` in Jupyter Notebook.

4\. Ensure the dataset `LS\_2.0.csv` is in the project directory.

5\. Run the notebook cells sequentially.



Install dependencies:



```bash

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

```



\## Limitations

\- The analysis focuses only on the 2019 Lok Sabha General Election.

\- The dataset is observational; results indicate associations, not causation.

\- Political party and constituency context may strongly influence election outcomes.

\- Class imbalance can affect model performance.



\## Author

\*\*Tejasvi Chaturvedi\*\*  

B.Sc. (Hons.) Computer Science  

Ramanujan College, University of Delhi



\*\*Project:\*\* Machine Learning  

\*\*Supervisor:\*\* Mr. Nikhil Kumar  

\*\*Problem No.:\*\* 49



\---



This project was developed for academic and research purposes.

