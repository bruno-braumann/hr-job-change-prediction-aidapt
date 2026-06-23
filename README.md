# HR Analytics — Job Change Prediction

A group project developed as part of the **AiDAPT course at Cegid Academy**, building predictive models to estimate the probability of a professional accepting a job change.

The project follows the **CRISP-DM** methodology and is organised in five notebooks, one per development phase.

---

## Context

A company wants to understand which factors influence the likelihood of a professional accepting a new job opportunity. A dataset containing demographic, academic, and professional information about candidates was provided, along with an indication of whether they are looking for a new job or not.

---

## Repository Structure

```
hr-job-change-prediction-aidapt/
├── data/
│   └── Dados_RH_Mudanca_Emprego_in_.csv
├── notebooks/
│   ├── 01_Business_Understanding.ipynb
│   ├── 02_Data_Understanding.ipynb
│   ├── 03_Data_Preparation.ipynb
│   ├── 04_Modelling.ipynb
│   └── 05_Evaluation.ipynb
├── outputs/
│   ├── figures/
│   └── data/
└── README.md
```

---

## Dataset

File: `Dados_RH_Mudanca_Emprego_in_.csv`
Source: provided by the course instructor.

The dataset includes numerical and categorical variables related to:

- Candidate identification
- City of residence and urban development index
- Total professional experience
- Existence of relevant professional experience
- Academic or training status
- Education level
- Main area of study
- Type and size of current or most recent employer
- Time elapsed since last job change
- Number of training hours attended
- Whether the candidate is looking for a job change (target variable)

---

## Methodology — CRISP-DM

| Notebook | Phase | Description |
|---|---|---|
| `01_Business_Understanding.ipynb` | Business Understanding | Problem framing, objective definition, and success criteria |
| `02_Data_Understanding.ipynb` | Data Understanding | Dataset exploration, data quality, and target variable analysis |
| `03_Data_Preparation.ipynb` | Data Preparation | Cleaning, transformation, and dataset construction for modelling |
| `04_Modelling.ipynb` | Modelling | Training and comparison of predictive models |
| `05_Evaluation.ipynb` | Evaluation | Model evaluation, results interpretation, and conclusions |

---

## Success Criteria

For the model to be considered useful in this project, the following minimum performance criteria were defined:

- **F1-Score of 0.70 or above**
- **AUC of 0.80 or above**
- **Recall of 0.65 or above**

---

## Technologies

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat&logo=scikitlearn&logoColor=white)

Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`

---

*AiDAPT Course — Cegid Academy | Group Project*
