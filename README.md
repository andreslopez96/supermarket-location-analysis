# 🛒 Supermarket Location Analysis

This project simulates the role of a data analyst for a supermarket chain that wants to decide **where to open a new store**.  
The analysis involves loading a database into a DataFrame, cleaning and preprocessing the data, applying multiple **machine learning models**, and comparing their performance to support the business decision.

---

## 📂 Repository structure
- `supermarket_analysis.ipynb` → Main Jupyter Notebook with the entire workflow.

---

## 🔧 Methodology
1. **Data loading** → Import dataset into a DataFrame.  
2. **Data cleaning & preprocessing** →  
   - Handling missing values and outliers.  
   - Encoding categorical features and scaling numerical ones.  
   - Feature selection to reduce noise and improve accuracy.  
3. **Machine Learning models** → Different algorithms were trained and compared, including:  
   - Linear & Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
   - Support Vector Machines (SVM)  
   - k-Nearest Neighbors (kNN)  
   - Other models tested during the project  
4. **Validation** → Applied **k-fold cross-validation** to estimate model performance.  
5. **Model comparison** → Evaluation based on metrics such as **RMSE, R², Accuracy, Precision, and Recall** (depending on the task).  
6. **Business decision** → The best-performing model was used to recommend the optimal location for the new supermarket.  

---

## 📊 Results
- Identified which algorithm achieved the highest predictive accuracy.  
- Insights about the most important features influencing location decisions.  
- Final recommendation for the optimal store location, supported by data.  

---

## 🛠️ Technologies used
- **Python**: pandas, numpy, scikit-learn  
- **Visualization**: matplotlib, seaborn  
- **Environment**: Jupyter Notebook  

---

## 📌 Key takeaway
This project demonstrates the full **end-to-end data science workflow**:  
from raw data ingestion and cleaning → to machine learning modeling → to actionable **business insights**.

