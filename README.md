## Bank Marketing Campaign Prediction

This capstone project focuses on predicting whether a bank customer will subscribe to a **term deposit** as part of a marketing campaign.  
The goal is to help the bank improve its **marketing efficiency**, reduce campaign costs, and focus on **customers with higher conversion potential**.

### Objectives
- Build a predictive model to classify customers who are likely to subscribe to a term deposit.  
- Analyze which factors (like age, job, balance, contact type, or campaign frequency) most affect deposit decisions.  
- Provide business recommendations to improve marketing strategies and customer targeting.  

### Methods and Tools
The analysis follows a structured data science workflow:
1. **Data Cleaning & Preparation** – handled missing values, outliers, and categorical encoding.
2. **Exploratory Data Analysis (EDA)** – visualized patterns between customer attributes and deposit behavior.
3. **Model Development** – tested multiple models:
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
4. **Imbalance Handling** – applied **SMOTENC** to balance class distribution between depositors and non-depositors.
5. **Evaluation Metrics** – focused on **recall**, **accuracy**, and **ROC-AUC**, prioritizing recall to minimize missed potential customers.
6. **Feature Importance & Business Insights** – identified key drivers of deposit decisions and provided actionable recommendations.

### Key Findings
- **Sales volume** and **customer balance** are strong predictors of deposits.  
- **Excessive discounting** or too many contact attempts reduce conversion rates.  
- The **West region** performs best due to efficient cost and discount management.  
- **Random Forest** achieved the most balanced results between performance and interpretability.

### Business Impact
By implementing the model and recommendations:
- The bank can **target marketing efforts** more effectively.  
- Reduce campaign costs by avoiding low-probability leads.  
- Increase deposit subscriptions and overall profitability.

---

> In summary, this project transforms raw marketing data into a practical predictive tool that supports **data-driven decision-making**.  
> The insights gained can guide **future campaigns**, ensuring better customer targeting and higher marketing ROI.
