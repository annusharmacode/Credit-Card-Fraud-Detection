# 💳 Credit Card Fraud Detection ✅

## 💼 Business Problem
Banks face significant financial losses due to fraudulent transactions.  
This project aims to build a machine learning model that accurately detects fraud, minimizing false negatives (missed fraud) while keeping false positives (false alarms) low. This reduces manual effort, improves customer trust, and prevents revenue leakage.

## 🎯 Project Aim
- ✅ To develop an efficient, interpretable, and cost-effective fraud detection system.
- 🎯 Focused on achieving high **recall** (to catch more frauds) and high **precision** (to reduce false alarms).
- 📉 Reducing financial losses and enhancing operational efficiency for banking systems.

## ⚖️ Class Imbalance Handling  
The dataset was highly imbalanced with **✅ 99.08% legitimate** and **❗0.16% fraudulent** transactions.  
To address this issue, **🔄 Random UnderSampling** was applied, resulting in a ✔️ balanced dataset that enabled fair learning for all models.

## 📌 Project Highlights

- **🔍 Data Preprocessing**:  
  - Cleaned data and handled missing values  
  - Handled extreme class imbalance via undersampling  
  - Performed feature engineering

- **🤖 Machine Learning Models Applied**:  
  - ✅ Logistic Regression  
  - 🌲 Decision Tree  
  - 🌳 Random Forest  
  - ⚡ XGBoost  

- **🔧 Hyperparameter Tuning**:  
  - Used `GridSearchCV` for each model to optimize performance

- **📊 Evaluation Metrics**:  
  - Compared models based on **Precision**, **Recall**, **F1 Score**, and **ROC AUC**

- 🏆 **Final Model Selected**:  
  - **XGBoost** was chosen for deployment due to its **superior performance** across all key metrics, especially ROC AUC (0.97+) and F1 Score (0.92+)

## 🛠 Technologies Used

- 🐍 **Python**
- ⚙️ **Scikit-learn**
- 📈 **Matplotlib** & **Seaborn** for visualization
- 🧹 **Data Preprocessing** (cleaning, scaling, encoding)
- ⚖️ **Class Balancing** using Random UnderSampling



## 📬 If you have any suggestions, feedback, or queries related to this project, feel free to reach out!
🤝 Contributions, suggestions are welcome!

