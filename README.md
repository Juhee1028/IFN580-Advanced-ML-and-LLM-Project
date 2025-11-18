# IFN580 – Advanced Machine Learning & LLM Project (High Distinction)

## Overview
This repository contains **my individual work** for IFN580 Assignment 2 at Queensland University of Technology (QUT).

The assessment covers several advanced machine learning topics, but  
**this repository ONLY includes the work that I personally completed**, specifically:

- **LSTM time-series forecasting (primary contribution)**
- **BERT text classification**
- **T5 question–answer generation**

Other components of the assignment (dimensionality reduction, clustering)  
were completed by teammates and are **not** included here.

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
│   ├── 03_lstm_forecasting.ipynb        # my main contribution
│   ├── 04_bert_finetuning.ipynb         # my contribution
│   ├── 05_t5_qna.ipynb                  # my contribution
│
│   # Not included (team work):
│   # 01_dimensionality_reduction.ipynb
│   # 02_clustering.ipynb
│
├── report/
│   └── IFN580_Assignment2_Report.pdf
├── data/
│   └── README.md                        # dataset not included
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
