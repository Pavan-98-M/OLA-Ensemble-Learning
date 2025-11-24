Ola Driver Attrition Prediction (Machine Learning Project)

This project aims to predict driver churn for Ola using machine learning techniques. By identifying at-risk drivers early, the business can improve retention efforts and reduce high acquisition costs. The solution uses feature engineering, model optimization, and insights extraction to support data-driven decision-making.

Objectives

Predict whether a driver is likely to leave the platform

Understand key factors influencing driver churn

Provide insights to support proactive retention strategies

Dataset

19,000+ driver records containing demographic, rating, income and trip performance data

Tech Stack

Python, Pandas, NumPy, Scikit-Learn, XGBoost, Matplotlib, Seaborn, SMOTE

Machine Learning Workflow

Data cleaning and preprocessing

Feature engineering (service months, income growth, ratings change, etc.)

Model training: Random Forest, Gradient Boosting, XGBoost

Handling imbalance using SMOTE

Model evaluation using accuracy, ROC-AUC and confusion matrix

Best model performance: Approximately 79% test accuracy

Key Insights

Service duration and income growth are strong churn indicators

Drivers with low performance improvements are more likely to leave

Business value and grading trends help predict attrition risk

Business Impact

Supports early churn detection and cost-effective retention planning for Ola through targeted driver engagement.

Project Structure
data/
notebooks/
src/
README.md
requirements.txt

Future Enhancements

Add explainability using SHAP

Deploy using Streamlit or Flask

Build real-time monitoring dashboard

Author

Pavan Meti
Data Analyst | Machine Learning Enthusiast
