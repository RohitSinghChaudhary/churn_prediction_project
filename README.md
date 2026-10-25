<div align="center">



\# 📉 Telco Customer Churn Prediction



\*An end-to-end machine learning project that predicts customer churn in the telecommunications industry, featuring exploratory data analysis, model evaluation, and an interactive Streamlit application.\*



!\[Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square\&logo=python\&logoColor=white)

!\[Machine Learning](https://img.shields.io/badge/Machine\_Learning-scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white)

!\[Streamlit](https://img.shields.io/badge/Interface-Streamlit-FF4B4B?style=flat-square\&logo=streamlit\&logoColor=white)

\[!\[Dataset](https://img.shields.io/badge/Dataset-Kaggle-20BEFF?style=flat-square\&logo=kaggle\&logoColor=white)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

!\[Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)



</div>



\## 📖 Project Overview



\*\*Customer churn\*\* occurs when customers stop using a company's services. Identifying customers who may leave can help businesses understand customer behavior and plan retention strategies.



This project follows an \*\*end-to-end machine learning workflow\*\*, from data exploration and preprocessing to model training, evaluation, and interactive prediction through Streamlit.



\## ✨ Features



\- 🔍 Exploratory Data Analysis (EDA)

\- 🧹 Data cleaning and preprocessing

\- 🤖 Machine learning model comparison

\- 📈 Logistic Regression model for churn prediction

\- 🎯 Model evaluation using classification metrics

\- 📊 Confusion matrix and ROC curve visualizations

\- 🌐 Interactive Streamlit application for churn prediction



\## 🧰 Tech Stack



| Category | Technologies |

| :-- | :-- |

| \*\*Language\*\* | !\[Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white) |

| \*\*Data Processing\*\* | !\[Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white) !\[NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square\&logo=numpy\&logoColor=white) |

| \*\*Machine Learning\*\* | !\[Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square\&logo=scikitlearn\&logoColor=white) |

| \*\*Visualization\*\* | !\[Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square\&logo=matplotlib\&logoColor=white) !\[Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) |

| \*\*Web Application\*\* | !\[Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square\&logo=streamlit\&logoColor=white) |

| \*\*Development\*\* | !\[Jupyter Notebook](https://img.shields.io/badge/Jupyter\_Notebook-F37626?style=flat-square\&logo=jupyter\&logoColor=white) |

| \*\*Model Persistence\*\* | !\[Pickle](https://img.shields.io/badge/Pickle-6C757D?style=flat-square) |



\## 💾 Dataset



\- \*\*Source:\*\* \[Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

\- \*\*Purpose:\*\* Analyze customer information and predict potential churn.



The dataset contains customer demographics, subscribed services, account information, contract details, and billing information.



\## 📂 Project Structure



<details>

<summary><b>Click to view the repository tree</b></summary>



```text

churn\_prediction\_project/

├── app.py

├── data/

│   └── telco\_comm\_churn.csv

├── models/

│   ├── best\_model\_logistic\_regression.pkl

│   └── preprocessor.pkl

├── notebooks/

│   ├── 01\_eda.ipynb

│   ├── 02\_data\_preprocessing.ipynb

│   └── 03\_model\_training.ipynb

├── other/

│   └── test.py

├── reports/

│   ├── categorical\_analysis.png

│   ├── churn\_distribution.png

│   ├── confusion\_matrix.png

│   ├── correlation\_heatmap.png

│   ├── model\_comparison.csv

│   ├── model\_comparison\_graph.png

│   ├── numerical\_analysis.png

│   └── roc\_curves.png

├── src/

│   └── data\_preprocessing.py

├── requirements.txt

├── .gitignore

└── README.md

```



</details>



\## 🚀 Getting Started



\### Prerequisites



\- Python installed on your system

\- pip package manager



\### 1. Clone the repository



```bash

git clone https://github.com/RohitSinghChaudhary/churn\_prediction\_project.git

cd churn\_prediction\_project

```



\### 2. Create a virtual environment



\*\*Windows\*\*



```cmd

python -m venv .venv

.venv\\Scripts\\activate

```



\*\*macOS / Linux\*\*



```bash

python3 -m venv .venv

source .venv/bin/activate

```



\### 3. Install dependencies



```cmd

python -m pip install -r requirements.txt

```



\### 4. Run the Streamlit application



```cmd

streamlit run app.py

```



Open the local URL displayed in your terminal to interact with the application.



\## 🧠 Machine Learning Workflow



```mermaid

flowchart LR

&#x20;   A\["📊 Exploratory<br/>Data Analysis"] --> B\["🧹 Data<br/>Preprocessing"]

&#x20;   B --> C\["🤖 Model Training<br/>and Comparison"]

&#x20;   C --> D\["🎯 Model<br/>Evaluation"]

&#x20;   D --> E\["🌐 Interactive<br/>Prediction"]

```



\### 1. Exploratory Data Analysis



Explore customer data to understand feature distributions, relationships, and patterns associated with churn.



\### 2. Data Preprocessing



Prepare the dataset for machine learning. Refer to `notebooks/02\_data\_preprocessing.ipynb` and `src/data\_preprocessing.py` for the implemented steps.



\### 3. Model Training and Comparison



Train and compare machine learning models using the model-training notebook. The selected Logistic Regression model and its preprocessor are saved in the `models/` directory.



\### 4. Model Evaluation



The project includes model comparison results and visualizations such as:



\- Confusion matrix

\- ROC curves

\- Model comparison graph



See `reports/model\_comparison.csv` for the recorded evaluation results.



\### 5. Interactive Prediction



The Streamlit application provides an interface for entering customer information and obtaining churn predictions from the trained model.



\## 📈 Visualizations



<table>

&#x20; <tr>

&#x20;   <td align="center" width="50%">

&#x20;     <b>Model Comparison</b><br>

&#x20;     <img src="reports/model\_comparison\_graph.png" alt="Model comparison graph">

&#x20;   </td>

&#x20;   <td align="center" width="50%">

&#x20;     <b>ROC Curves</b><br>

&#x20;     <img src="reports/roc\_curves.png" alt="ROC curves">

&#x20;   </td>

&#x20; </tr>

&#x20; <tr>

&#x20;   <td align="center" colspan="2">

&#x20;     <b>Confusion Matrix</b><br>

&#x20;     <img src="reports/confusion\_matrix.png" alt="Confusion matrix" width="420">

&#x20;   </td>

&#x20; </tr>

</table>



\## 💼 Business Use Case



The model demonstrates how customer data can be used to identify potential churn risk. Businesses could use such predictions to investigate customer concerns and develop targeted retention strategies.



> \[!NOTE]

> Predictions indicate estimated risk and do not guarantee future customer behavior.



\## 🔮 Future Improvements



\- \[ ] Deploy the Streamlit application online

\- \[ ] Improve model explainability

\- \[ ] Explore additional model-tuning techniques

\- \[ ] Add customer-retention recommendations



\## 👤 Author



\*\*Rohit Singh Chaudhary\*\*



\[!\[GitHub](https://img.shields.io/badge/GitHub-RohitSinghChaudhary-2B3137?style=flat-square\&logo=github\&logoColor=white)](https://github.com/RohitSinghChaudhary)

\[!\[LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/rohitsinghchaudhary/)

