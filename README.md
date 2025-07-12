# Insurance Fraud Analytics Project

## Overview

This project aims to detect and analyze fraudulent insurance claims using advanced data analytics and machine learning techniques. Insurance fraud causes significant financial losses for insurance companies and raises premiums for honest policyholders. By analyzing structured insurance claims data, this project seeks to identify patterns, risk factors, and anomalies that indicate fraud.

---

## Objectives

- Clean and preprocess insurance claims data for analysis.
- Explore the characteristics of fraudulent vs. non-fraudulent claims.
- Identify key numeric and categorical features correlated with fraud.
- Visualize data distributions, trends, and relationships with fraud.
- Develop predictive models to detect fraudulent claims (planned future step).
- Provide insights to help insurers detect suspicious claims earlier.

---

## Dataset

The dataset contains records of insurance claims with features such as:

- Claim details (claim amount, claim number, incident type).
- Incident information (collision type, police report availability, incident date).
- Policyholder data (policy bind date).
- Fraud labels indicating confirmed fraud cases.

---

## Project Structure

> Please run notebooks in sequence.

- `etl.ipynb` — Extract, transform, and load pipeline for cleaning and preparing data.
- `eda.ipynb` — Exploratory Data Analysis with visualizations and fraud pattern insights.
- `feature_engineering.ipynb` — Create new features and transform variables for modeling.
- `model_training.ipynb` — Train and evaluate Machine learning model development and evaluation.
- `reporting_dashboard` — Generate visualizations and reports for stakeholders.

---

## Extract, Transform and Load CSV Dataset

Data cleaning and transformation were performed through an ETL pipeline to handle missing values, standardize data, and engineer fraud risk scores.

---

## Exploratory Data Analysis (EDA) Highlights

- The dataset exhibits class imbalance with fewer fraudulent claims than non-fraudulent.
- High-value claims and claims occurring during unusual hours often have higher fraud rates.
- Categorical features like collision type and police report availability show varying fraud risk.
- Missing data indicators help identify potential fraud cases where information is intentionally omitted.
- Daily fraud trends highlight potential seasonal or event-driven spikes in fraudulent activity.

---

## Tools and Libraries

- Data Processing: **pandas, numpy**
- Visualization: **matplotlib, seaborn**
- Machine Learning: **scikit-learn**
- Database & Environment: **sqlalchemy, python-dotenv, os, IPython.display**
- Dashboarding: **Plotly, Dash, Streamlit**

---

## Future Steps

- Feature Engineering to improve predictive power.
- Splitting data for training and testing Machine Learning models.
- Model Training using algorithms suited for imbalanced classification.
- Model Evaluation using metrics focused on fraud detection such as precision, recall, F1-score, and ROC-AUC.
- Deploying a fraud scoring system to assist operational fraud detection.

---

## Getting Started and How to Run

1. **Clone this repository:**

```bash
git clone https://github.com/PatZ2346/fraud_analytics_project.git
cd fraud_analytics_project
```

2. **Install dependencies:**
- Make sure you have Python 3.8+ installed. Install required packages using provided requirements.txt: pip install -r requirements.txt

3. **Download and prepare data:**
- Download the dataset from Kaggle: [Auto Insurance Claims Fraud Detection](https://www.kaggle.com/datasets/antopravinjohnbosco/auto-insurance-claims-fraud-detection?resource=download), place it in the data/raw/ folder, and run the etl.ipynb notebook to clean and preprocess the data.
- Place the raw CSV file in the data/raw/ folder.
- Run the ETL notebook to clean and preprocess the data: jupyter notebook etl.ipynb

4. **Run notebooks in order:**
- `Extract, Transform & Load (ETL)`: etl.ipynb
Clean, transform, and prepare data for analysis and modeling.
- `Exploratory Data Analysis (EDA)`: eda.ipynb
Explore data distributions, relationships, and fraud patterns.
- `Feature Engineering`: feature_engineering.ipynb
Create new features and encode variables for modeling.
- `Model Training`: model_training.ipynb
Train, evaluate, and validate fraud detection models.
- `Reporting Dashboard`: reporting_dashboard.ipynb
Generate visual reports and dashboards for insights.

---

## Contributing
Contributions are welcome! Feel free to fork the repo and submit pull requests with improvements or fixes.

---

## License
This project is licensed under the MIT License.

---

## Contact
Created by PatZ.

Email: [patrick.zhou90@gmail.com](mailto:patrick.zhou90@gmail.com)  
GitHub: [@PatZ2346](https://github.com/PatZ2346)  

For issues, feedback or collaborations please open an issue on GitHub.

---