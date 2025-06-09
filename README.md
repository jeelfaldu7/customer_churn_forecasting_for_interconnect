# 📈 Customer Churn Prediction
This project aims to build a predictive model to identify customers who are at risk of churning. By analyzing customer behavior and demographics, we hope to provide actionable insights that can help reduce churn and improve customer retention.

## 📄 Project Description
The goal of this project is to predict customer churn using historical data. Churn occurs when a customer stops using a service. Accurately predicting churn allows companies to proactively intervene and retain valuable customers.
Key highlights:
  - Technologies used: Python (Pandas, Scikit-learn, XGBoost, CatBoost, LightGBM), Matplotlib, Seaborn
  - Data: Includes customer account information, demographic data, and service usage metrics
  - Challenges:
      - Handling class imbalance
      - Identifying optimal hyperparameters
      - Comparing different models
  - Future enhancements:
      - Deploying the best model as a web service
      - Incorporating SHAP for model interpretability
      - Exploring feature engineering for improved accuracy

## 🗂️ Table of Contents
  1. Installation
  2. Usage
  3. Results & Visuals
  4. Credits
  5. License

## 🛠️ Installation
To set up the environment locally:
  1️. Clone the repository:
  ```
  git clone https://github.com/your-username/churn-prediction.git
  cd churn-prediction
  ```
  2. Create a virtual environment and activate it:
  ```
  python -m venv venv
  source venv/bin/activate  # on Windows: venv\Scripts\activate
  ```
  3. Install the dependencies:
  ```
  pip install -r requirements.txt
  ```

## 📊 Results & Visuals
| Model                       | Accuracy | AUC-ROC |
| --------------------------- | -------- | ------- |
| Logistic Regression         | 0.736    | 0.832   |
| Random Forest (Tuned)       | 0.839    | 0.878   |
| CatBoost (With Grid Search) | 0.831    | 0.910   |
| XGBoost (With Grid Search)  | 0.883    | 0.921   |
| LightGBM                    | 0.890    | 0.915   |

The LightGBM model achieved the best overall performance, with an AUC-ROC of 0.915.

## 🤝 Credits
This project was created as part of the TripleTen Data Science program. Special thanks to:
  - TripleTen instructors and peers for ongoing support and feedback.

## 📜 License
This project is licensed under the MIT License. 

