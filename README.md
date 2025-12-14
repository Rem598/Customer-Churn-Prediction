# Customer Churn Prediction System

## 📊 Project Overview
End-to-end machine learning pipeline predicting telecom customer churn with **85%+ accuracy**. This production-ready system identifies at-risk customers and provides actionable retention insights.

## 🎯 Business Problem
Customer churn costs telecom companies billions annually. This project builds a predictive system to:
- Identify customers likely to churn before they leave
- Understand key churn drivers
- Enable proactive retention strategies
- Deliver individual churn probabilities for targeted interventions

## 🔧 Technical Approach

### Data Preprocessing
- Handled missing values and data quality issues
- Created tenure groups for customer lifecycle analysis
- Engineered service indicators (internet, phone, streaming services)
- Encoded categorical variables for model compatibility

### Handling Class Imbalance
- **Challenge:** Only 26.5% of customers churned (imbalanced dataset)
- **Solution:** Implemented SMOTE (Synthetic Minority Over-sampling Technique)
- **Result:** Balanced training data for improved model performance

### Models Trained & Evaluated
| Model | Accuracy | ROC-AUC | Key Strength |
|-------|----------|---------|--------------|
| Logistic Regression | 80.2% | 0.84 | Interpretability |
| Random Forest | 85.3% | 0.89 | Feature importance |
| XGBoost | **86.1%** | **0.91** | Best performance |

### Evaluation Metrics
- **ROC-AUC:** Model's ability to distinguish churners from non-churners
- **Precision/Recall:** Balance between catching churners and avoiding false alarms
- **Confusion Matrix:** Breakdown of prediction accuracy by class

## 📈 Key Results

### Model Performance
- **85%+ accuracy** in predicting customer churn
- **91% ROC-AUC** (XGBoost) - excellent discriminatory power
- Successfully identifies high-risk customers for retention campaigns

### Business Insights
Top churn drivers identified:
- Contract type (month-to-month contracts have highest churn)
- Tenure (customers in first year most at-risk)
- Service usage patterns (internet type, tech support usage)
- Billing method (electronic check users churn more)

## 🛠️ Tech Stack
- **Python** - Core programming language
- **Pandas, NumPy** - Data manipulation and analysis
- **Scikit-learn** - Machine learning models and preprocessing
- **XGBoost** - Gradient boosting framework
- **SMOTE (imbalanced-learn)** - Class imbalance handling
- **Matplotlib, Seaborn** - Data visualization



## 💡 Key Takeaways

### What Makes This Production-Ready?
1. **Robust preprocessing pipeline** - Handles missing data, outliers, encoding
2. **Class imbalance handling** - SMOTE ensures model learns from minority class
3. **Multiple model comparison** - Selected best performer based on business metrics
4. **Interpretable results** - Feature importance and churn drivers clearly identified
5. **Individual predictions** - Generates churn probability for each customer

### Business Applications
- **Retention campaigns:** Target high-risk customers with personalized offers
- **Resource allocation:** Focus retention budget on customers most likely to churn
- **Product insights:** Understand which services/contracts drive churn
- **Revenue protection:** Proactively address churn before it impacts bottom line


## 📫 Contact
**Rehema Kemunto**  
[Portfolio](https://rem598.github.io/Projects/) | [LinkedIn](https://www.linkedin.com/in/rehema-kemunto) | [GitHub](https://github.com/Rem598)

---
