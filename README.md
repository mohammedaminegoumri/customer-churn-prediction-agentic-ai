# Customer Churn Prediction & Agentic AI Retention Strategy

End-to-end analysis and predictive modeling for customer churn using the IBM Telco Customer Churn dataset. The project combines exploratory data analysis, feature engineering, XGBoost modeling, SHAP explainability, business impact simulation, and a forward-looking perspective on **agentic AI** for proactive retention in 2026.



## 📋 Project Overview

- **Dataset**: IBM Telco Customer Churn (7,043 records)
- **Churn Rate**: 26.54%
- **Model**: XGBoost Classifier
- **Performance**: ROC-AUC **0.8389**
- **Explainability**: SHAP values
- **Business Impact**: Estimated $269K annual revenue loss; $40K+ potential savings with 15% relative churn reduction

This repository demonstrates a complete, production-minded workflow — from raw data to actionable business insights and emerging AI trends.

## 🎯 Objectives

- Identify key drivers of customer churn through EDA and feature engineering
- Build and evaluate a robust churn prediction model
- Provide model interpretability using SHAP
- Quantify financial impact of churn and retention improvements
- Explore how **agentic AI** can transform retention from reactive to autonomous in 2026

## 📁 Repository Structure
customer-churn-prediction-agentic-ai/
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv          # Raw dataset
├── notebooks/
│   └── 01_eda_and_modeling.ipynb                     # Main Jupyter notebook
├── src/                                              # (Optional) Python scripts for reusable code
├── images/                                           # Charts and visualizations for README
├── requirements.txt
├── README.md
└── LICENSE

## 🔍 Key Insights

- **Month-to-month contracts** churn ~4× higher than 2-year contracts
- Low **tenure** (especially first 6–12 months) is a major risk factor
- **Fiber optic** users and high **MonthlyCharges** show elevated churn
- Electronic check payment method correlates with higher churn
- Senior citizens and customers without partners/dependents are higher-risk segments

## 🛠️ Technologies Used

- **Language**: Python 3
- **Data Manipulation**: pandas, numpy
- **Visualization**: matplotlib, seaborn, plotly
- **Modeling**: scikit-learn, XGBoost
- **Explainability**: SHAP
- **Environment**: Google Colab / Jupyter Notebook

## 📊 Results

- **Model Performance**:  
  - ROC-AUC: 0.8389  
  - Accuracy: ~79%  
  - Churn class (Recall): 0.53 (can be improved with threshold tuning or class weighting)

- **Top Churn Drivers** (from XGBoost + SHAP):  
  1. Month-to-month contract  
  2. Low tenure  
  3. High MonthlyCharges  
  4. Fiber optic service  
  5. AvgMonthlyCharge

- **Business Simulation**:  
  - Estimated annual revenue loss from churn: **$269,136 USD**  
  - With 15% relative reduction on high-risk segments: **$40,320 USD** potential savings (~280 customers retained)

## 🚀 2026 Perspective: Agentic AI for Retention

In 2026, static churn models evolve into **agentic AI systems** — autonomous agents that:
- Monitor real-time signals (usage drop, support tickets, contract milestones)
- Reason and plan personalized interventions
- Execute actions (dynamic discounts, upgrades, proactive outreach) with minimal human oversight

This project lays the foundation for integrating predictive models with agentic workflows to move from churn **prediction** to autonomous **prevention**.

## 📈 Recommendations

1. Incentivize longer-term contracts at signup
2. Improve value perception for high-spend Fiber users
3. Focus retention efforts on early customer lifecycle (first 6–12 months)
4. Pilot agentic AI agents for scalable, real-time personalized retention

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction-agentic-ai.git
   cd customer-churn-prediction-agentic-ai
## Install dependencies:
   pip install -r requirements.txt

   ## Open the notebook:
   jupyter notebook notebooks/01_eda_and_modeling.ipynb
   ## Requirements
   pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
xgboost
shap
jupyter
## License
MIT License — feel free to use and adapt for learning or portfolio purposes.
## Connect
Built as part of a hands-on data science project in Casablanca, Morocco.
Open to collaborations on retention analytics and agentic AI applications.


