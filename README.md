# IFN580 – Advanced Machine Learning & LLM Project (High Distinction)

## Overview
This repository contains my individual work for the IFN580 Assignment 2 project at the Queensland University of Technology (QUT).  
The assessment explores multiple advanced machine learning techniques across different domains:

- Dimensionality reduction (PCA, t-SNE, UMAP)
- Unsupervised learning & clustering (K-means, Hierarchical, DBSCAN)
- **Time-series forecasting using LSTM**
- **NLP modelling using BERT and T5 (LLM)**

This repository includes only my own contributions, reproduced and cleaned for portfolio use.

---

## My Contribution
While the report and some analysis were completed as a team, **the majority of implementation below was done by me**, and only my individual work is included in this repository.

### 🔹 **LSTM Time-Series Forecasting (Primary Contribution)**
- Time-series preprocessing and restructuring of the dataset  
- Implemented univariate & multivariate LSTM models from scratch  
- Designed training loops, scaling, windowing, and sequence preparation  
- Evaluated models using RMSE, MAE  
- Generated forecasting plots and analysed predictions  
- Compared multiple hyperparameter configurations  

### 🔹 **BERT & T5 NLP Tasks (Shared Contribution, but my technical work included)**
- Fine-tuned **BERT** for text classification  
- Fine-tuned **T5** for Q&A generation  
- Ran training, tokenisation, and inference examples  
- Interpreted outputs and wrote analysis sections

## Repository Structure
```
IFN580-Advanced-ML-and-LLM-Project/
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_dimensionality_reduction.ipynb
│   ├── 03_clustering.ipynb
│   ├── 04_lstm_forecasting.ipynb          # my main contribution
│   ├── 05_bert_t5_nlp.ipynb               # shared contribution (my code only)
├── report/
│   └── IFN580_Assignment2_Report.pdf
├── data/
│   └── README.md                          # dataset not included
└── README.md
```

---
## Dataset Source
The dataset used in this project was provided by Queensland University of Technology (QUT)  
for educational purposes as part of the IFN580 coursework.  
It contains no personal or sensitive information.

*Dataset files are not included in this repository.*

---

## Report
The full written report for this assignment was completed collaboratively as a team.  
This repository includes **only my individual notebooks, code, and analyses**, reproduced for portfolio use.

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- PyTorch / HuggingFace Transformers  
- LSTM, BERT, T5  
- Jupyter Notebook  

---

## Grade
**High Distinction: 36 / 40**
