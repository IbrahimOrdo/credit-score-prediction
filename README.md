# Credit Score Prediction with Limited Data

## 📌 Overview
This project explores the relationship between **income and credit score** using a small dataset (100 samples).  
The goal was to build a simple **linear regression model** to predict credit scores based on income.  

## 📊 Data Summary
- **Total samples:** 100  
- **Columns:** `application_id`, `age`, `income`, `credit_score`  
- **No missing values**  

## 🔍 Exploratory Data Analysis (EDA)
- **Correlation:**  
  - `income` and `credit_score` have a **weak correlation (~0.07)**  
  - This suggests that income alone **does not strongly determine** credit scores.  
- **Scatter Plot Insights:**  
  - The data is **spread out without a clear pattern**.  
  - There are **no strong clusters or trends**.  

## 📈 Regression Model Results
We trained a **simple linear regression model** to predict `credit_score` using `income`.  

**Model Performance:**  
- **Mean Absolute Error (MAE):** `95.78`  
- **R² Score:** `-0.02` (indicates poor predictive power)  

### 🚨 **Key Takeaways**
1. **Poor Model Fit:**  
   - The negative R² score means that our model performs **worse than just predicting the average credit score**.  
2. **Missing Important Features:**  
   - Credit score is influenced by **many factors beyond income** (e.g., debt, payment history).  
3. **Real-World Insight:**  
   - If this were a real financial model, we'd need **more features & a larger dataset** for reliable predictions.  

## 📝 Future Improvements
- Collect more data with additional features (e.g., debt, payment history).  
- Try different models like **Decision Tree or Random Forest** for better results.  
- Experiment with **feature engineering & normalization techniques**.  

📢 **Conclusion:**  
This project highlights the importance of **feature selection & data quality** in predictive modeling. Even though our model performed poorly, this is a valuable learning experience! 🚀  

---
