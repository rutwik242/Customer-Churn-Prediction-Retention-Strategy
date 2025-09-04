 Customer Churn Prediction & Retention Strategy

Overview
Built a churn prediction system for NovaTel Communications to address an estimated ₹5K loss per churner.  
The project prioritizes recall to reduce false negatives (missed churners) and includes a **cost–benefit analysis** for strategy recommendations.

Tech Stack
- Languages: Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Visualization: Matplotlib, Seaborn, Power BI


Key Features
- Applied VIF for multicollinearity handling.  
- Used WoE/IV (IV > 0.02) for feature selection.  
- Built models: Logistic Regression, Random Forest, XGBoost.  
- Evaluated with Precision, Recall, F1-score, and AUC.  
  Cost–Benefit Analysis:
  - Logistic Regression: Threshold = 0.20 → ₹2.43M profit, Recall = 0.88, AUC = 0.93  
  - XGBoost: Threshold = 0.15 → ₹2.37M profit, Recall = 0.89, AUC = 0.93  

Insights
Key churn drivers: contract type, tenure, internet service, tech support.  
Recommended long-term contracts and improved technical support to boost retention.

 How to Run
```bash
git clone https://github.com/<your-username>/customer-churn-prediction.git
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook notebooks/churn_analysis.ipynb
