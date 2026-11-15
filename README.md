# customer-churn-prediction-nsga2


# Customer Churn Prediction Using NSGA-II

## Project Overview
This project predicts customer churn using machine learning and NSGA-II-based multi-objective feature selection.

## Dataset
IBM Telco Customer Churn Dataset.

- Total records: 7,043
- Original input features: 20
- Selected features: 11

## Methodology
1. Data preprocessing
2. Exploratory data analysis
3. NSGA-II feature selection
4. Logistic Regression model training
5. Model evaluation
6. Gradio dashboard

## Final Model Results

| Metric | Score |
|---|---:|
| Accuracy | 74.45% |
| Precision | 51.23% |
| Recall | 78.07% |
| F1-score | 61.86% |
| ROC-AUC | 84.86% |
| PR-AUC | 65.46% |

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- PyMOO (NSGA-II)
- Gradio

## Author
Add your name and team details here.


customer-churn-prediction-nsga2/
│
├── notebooks/
│   └── customer_churn_nsga2.ipynb
│
├── README.md
├── requirements.txt
├── selected_features.json
└── results/
    └── model_evaluation.png
