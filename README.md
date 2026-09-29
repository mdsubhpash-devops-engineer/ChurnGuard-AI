# 🛡️ ChurnGuard-AI

> Predict. Analyze. Retain.

ChurnGuard-AI is an end-to-end customer churn prediction system using XGBoost + Kaplan-Meier Survival Analysis + Automated Retention Engine.

### 🚀 Project Flow
1. RAW DATA -> Preprocessing
2. XGBoost Model -> Churn Risk (0-100%)
3. Survival Analysis (km_df)
4. Explainability (feature_importances_)
5. Retention Engine -> Auto Actions
6. Dashboard Ready

### 📊 Key Outputs
- `churn_risk` - 0 to 100% score
- `km_df` - Survival probability
- `final_output` - Top 20 high-risk customers
- `retention_action` - DISCOUNT_25_PCT / PRIORITY_CALL / ONBOARDING_ASSIST

### 🛠️ Tech Stack
Python, Pandas, Scikit-Learn, XGBoost, Matplotlib

### 📈 Results
Accuracy: 89% | AUC: 0.92

### 👨‍💻 Author
[Your Name] - Data Science Project 2026
