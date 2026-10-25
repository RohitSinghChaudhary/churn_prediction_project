# 📉 Telco Customer Churn Prediction

**An end-to-end machine learning project to predict customer churn in the telecommunications industry, featuring exploratory data analysis, model comparison, and an interactive Streamlit application.**

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
</p>

<p align="center">
  <a href="https://github.com/RohitSinghChaudhary/churn_prediction_project">
    <img src="https://img.shields.io/badge/Project-Repository-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Repository">
  </a>
  <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn">
    <img src="https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle Dataset">
  </a>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" alt="Project Status">
</p>

---

## 📖 Project Overview

Customer churn occurs when customers stop using a company's products or services. Predicting which customers are likely to leave can help businesses understand customer behavior and develop better retention strategies.

This project implements an end-to-end machine learning workflow, covering data exploration, preprocessing, model training and comparison, evaluation, and interactive churn prediction using Streamlit.

## ✨ Key Features

- 🔍 **Exploratory Data Analysis:** Explore customer demographics, services, contracts, and billing patterns.
- 🧹 **Data Preprocessing:** Prepare data for machine learning.
- 🤖 **Model Comparison:** Compare trained classification models.
- 📈 **Churn Prediction:** Use the selected Logistic Regression model to predict customer churn.
- 📊 **Model Evaluation:** Review classification results, confusion matrix, and ROC curves.
- 🌐 **Interactive Web App:** Enter customer information and obtain a prediction through Streamlit.
- 💾 **Saved Model Artifacts:** Load the trained model and preprocessing pipeline for predictions.

## 🧰 Tech Stack

| Category | Technologies |
| :-- | :-- |
| **Language** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| **Data Processing** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Machine Learning** | ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| **Visualization** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=matplotlib&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) |
| **Web Application** | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) |
| **Development** | ![Jupyter Notebook](https://img.shields.io/badge/Jupyter_Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| **Model Persistence** | ![Pickle](https://img.shields.io/badge/Pickle-6C757D?style=flat-square) |

## 💾 Dataset

**Source:** [Telco Customer Churn Dataset — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset contains customer information, subscribed services, contract details, payment methods, billing information, and churn labels.

It is used to explore factors associated with churn and train machine learning models to predict whether a customer may leave.

## 📂 Project Structure

```text
churn_prediction_project/
├── app.py
├── data/
│   └── telco_comm_churn.csv
├── models/
│   ├── best_model_logistic_regression.pkl
│   └── preprocessor.pkl
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_data_preprocessing.ipynb
│   └── 03_model_training.ipynb
├── other/
│   └── test.py
├── reports/
│   ├── categorical_analysis.png
│   ├── churn_distribution.png
│   ├── confusion_matrix.png
│   ├── correlation_heatmap.png
│   ├── model_comparison.csv
│   ├── model_comparison_graph.png
│   ├── numerical_analysis.png
│   └── roc_curves.png
├── src/
│   └── data_preprocessing.py
├── requirements.txt
├── .gitignore
└── README.md
```

## 🚀 Getting Started

Follow these steps to run the project on your computer.

### Prerequisites

- Python installed on your system
- Git installed on your system
- pip package manager

### 1. Clone the repository

```bash
git clone https://github.com/RohitSinghChaudhary/churn_prediction_project.git
cd churn_prediction_project
```

### 2. Create and activate a virtual environment

**Windows — Command Prompt**

```cmd
python -m venv .venv
.venv\Scripts\activate
```

**Windows — Git Bash**

```bash
python -m venv .venv
source .venv/Scripts/activate
```

**macOS / Linux**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the Streamlit application

```bash
streamlit run app.py
```

Open the local URL displayed in your terminal to use the application.

## 🧠 Machine Learning Workflow

```mermaid
flowchart TD
    A["Telco Customer Churn Dataset"] --> B["Exploratory Data Analysis"]
    B --> C["Data Cleaning and Preprocessing"]
    C --> D["Model Training and Comparison"]
    D --> E["Model Evaluation"]
    E --> F["Selected Logistic Regression Model"]
    F --> G["Streamlit Web Application"]
    G --> H["Customer Churn Prediction"]
```

### 1. Exploratory Data Analysis

Analyze customer characteristics, feature distributions, and relationships between customer attributes and churn.

### 2. Data Preprocessing

Prepare the dataset for model training using the preprocessing steps implemented in the notebooks and source code.

### 3. Model Training and Comparison

Train and compare classification models. The selected Logistic Regression model and its associated preprocessor are saved in the `models/` directory.

### 4. Model Evaluation

Evaluate the trained models and review the generated reports, including classification visualizations and model comparison results.

See `reports/model_comparison.csv` for the recorded model comparison results.

### 5. Interactive Prediction

The Streamlit application provides an interface for entering customer information and generating churn predictions using the saved model artifacts.

## 📊 Project Visualizations

The following visualizations are generated during the analysis and model evaluation stages.

### Churn Distribution

![Churn Distribution](reports/churn_distribution.png)

### Correlation Heatmap

![Correlation Heatmap](reports/correlation_heatmap.png)

### Model Comparison

![Model Comparison](reports/model_comparison_graph.png)

### ROC Curves

![ROC Curves](reports/roc_curves.png)

### Confusion Matrix

![Confusion Matrix](reports/confusion_matrix.png)

### Categorical Feature Analysis

![Categorical Feature Analysis](reports/categorical_analysis.png)

### Numerical Feature Analysis

![Numerical Feature Analysis](reports/numerical_analysis.png)

## 💼 Business Use Case

Customer churn prediction can help telecommunications businesses:

- Identify customers who may be at risk of leaving.
- Understand customer behavior and service usage patterns.
- Prioritize customer retention efforts.
- Support data-driven customer relationship management.

**Note:** Model predictions estimate churn risk and do not guarantee future customer behavior.

## 🔮 Future Improvements

- [ ] Deploy the Streamlit application online.
- [ ] Improve model explainability using feature importance or SHAP.
- [ ] Explore additional hyperparameter-tuning techniques.
- [ ] Develop personalized customer-retention recommendations.
- [ ] Monitor model performance on new customer data.

## 👤 Author

**Rohit Singh Chaudhary**

[![GitHub](https://img.shields.io/badge/GitHub-RohitSinghChaudhary-2B3137?style=flat-square&logo=github&logoColor=white)](https://github.com/RohitSinghChaudhary)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rohitsinghchaudhary/)
