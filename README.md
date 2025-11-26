# Credit-Risk-Prediction-Explainability-System
This project builds a complete, production-style credit risk scoring pipeline that predicts whether a customer is likely to default on a loan and provides a natural-language explanation using an LLM.

It combines machine learning, financial risk analytics, and lightweight LLM reasoning, making it suitable for real-world fintech workflows such as loan underwriting, credit scoring, and automated decision support.

✨ Business Overview

Banks and lending institutions need fast, accurate, and transparent credit decisions.
This system:

Predicts default probability using ML

Calculates key underwriting metrics (DTI, Loan-to-Income)

Generates auditable explanations using an LLM

Helps reduce manual analyst review time

Supports fair, data-driven loan decisioning

⚙️ Technical Highlights

Random Forest & Logistic Regression models for binary classification

98% AUC on credit default prediction

Feature engineering:

Debt-to-Income (DTI)

Loan-to-Income ratio

Standardized continuous variables

Model pipeline saved using Joblib

LLM agent built using HuggingFace InferenceClient for free text generation

Modular structure for training, inference, and explainability

Reproducible notebook with EDA, ROC curves, feature importance, and evaluation
