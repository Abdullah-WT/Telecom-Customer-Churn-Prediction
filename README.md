# 📡 Telecom Customer Churn Prediction

## 📌 Project Overview
In the telecom industry, retaining customers is critical as acquiring new ones is far more expensive. This project leverages **Machine Learning (Random Forest Classification)** to predict which customers are likely to churn (cancel their subscription) based on their usage patterns and demographics.

## 💼 Business Value
By identifying at-risk customers early, the company can:
* Target specific customers with retention offers.
* Understand key drivers of dissatisfaction (e.g., Contract Type, Payment Method).
* Reduce revenue loss.

## 🔍 Key Insights from Analysis
* **Contract Type:** Customers with **"Month-to-month"** contracts are significantly more likely to churn compared to 1-year or 2-year contracts.
* **Payment Method:** Electronic check users have a higher churn rate.
* **Fiber Optic:** Users with Fiber Optic internet service showed higher churn rates, indicating potential service quality issues or pricing concerns.

## 🛠️ Methodology
1.  **Data Preprocessing:** * Handled missing values in `TotalCharges`.
    * Performed **One-Hot Encoding** for categorical variables.
    * Removed irrelevant features like `customerID`.
2.  **Modeling:** Trained a **Random Forest Classifier**.
3.  **Evaluation:** Achieved **78.5% Accuracy** on unseen test data.

## 📊 Results
* **Accuracy:** 78.5%
* **Precision/Recall:** The model successfully identified a significant portion of potential churners (True Positives), allowing for proactive intervention.

## 💻 Technologies Used
* Python
* Pandas & NumPy
* Scikit-Learn (Random Forest)
* Seaborn & Matplotlib (Visualization)

## 🚀 How to Run
1.  Clone the repository.
2.  Install dependencies: `pip install pandas scikit-learn seaborn matplotlib`.
3.  Run the Jupyter Notebook.
