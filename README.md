
# Telecom Customer Churn Prediction  

**Predicting customer churn using machine learning (Gradient Boosting vs XGBoost)**  

![Churn Analysis](https://img.shields.io/badge/analysis-churn-blue) 
![Python](https://img.shields.io/badge/python-3.8%2B-green) 
 

## 📌 Overview  
This project analyzes customer churn in a telecom dataset, comparing **Gradient Boosting** and **XGBoost** models to predict at-risk customers. Key steps include:  
- Data cleaning & feature engineering  
- Exploratory analysis of churn drivers  
- Model building with class imbalance handling  
- Performance comparison and business insights  

**Key Result**: XGBoost achieved **81% recall** (detected 28% more churners than Gradient Boosting).  

---

## 📊 Results Summary  
| Metric          | Gradient Boosting | XGBoost |  
|-----------------|-------------------|---------|  
| **Accuracy**    | 80%               | 76%     |  
| **Recall (Churn)** | 53%           | **81%** |  
| **Precision (Churn)** | 65%       | 53%     |  

**Best Model**: XGBoost (prioritizes churn detection)  

---

## 🛠️ Installation  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Meghana-thota/telecom-churn-prediction.git  
   ```  

---


## 🔍 Key Findings  
1. **Top Churn Drivers**:  
   - Month-to-month contracts (3× higher churn than annual)  
   - Low tenure (<6 months)  
   - High monthly charges  

2. **Model Insights**:  
   - XGBoost’s higher recall makes it better for **proactive retention**  
   - Gradient Boosting is preferable if **false positives are costly**  

---

## 🤝 Contributing  
Pull requests welcome! For major changes, open an issue first.  



