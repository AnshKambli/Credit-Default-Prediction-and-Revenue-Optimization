# Credit-Default-Prediction-and-Revenue-Optimization
Project Overview
This project focuses on analyzing credit card customer data to predict the likelihood of defaulting on payments. Using machine learning techniques, especially Random Forest, the project identifies key risk factors and provides business insights to optimize revenue and manage customer risk.

📊 Key Objectives
Predict if a customer will default on their payment next month.

Analyze high credit limit customers and their default rates.

Provide actionable business insights for customer segmentation and revenue optimization.

🛠️ Technologies Used
Python (Pandas, NumPy)

Seaborn, Matplotlib (for visualization)

Scikit-learn (Random Forest, Logistic Regression)

Jupyter Notebook

🔎 Data Source
Dataset contains 30,001 customer records with features like:

Credit Limit (LIMIT_BAL)

Demographics (SEX, EDUCATION, MARRIAGE, AGE)

Payment history (PAY_0 to PAY_6)

Bill amounts (BILL_AMT1 to BILL_AMT6)

Payment amounts (PAY_AMT1 to PAY_AMT6)

Default status (default.payment.next.month)

📈 Model Performance

Model	Accuracy	Recall
Logistic Regression	80.80%	24.11%
Random Forest (Recommended)	81.70%	35.49%
➡️ Random Forest was selected as the best-performing model, offering higher recall and accuracy in identifying defaulters.

🔥 Key Findings
Default Rate among High Credit Limit Customers:

Customers with a credit limit above 240,000 had a default rate of 13.98%.

Business Insights:

Random Forest model helps better identify potential defaulters.

High credit limit customers are relatively low-risk but still need monitoring.

Revenue optimization strategies can be designed based on customer segmentation.

🚀 Future Improvements
Enhance feature engineering by including more behavioral data.

Explore ensemble methods and advanced hyperparameter tuning.

Implement a live dashboard for real-time risk tracking.

📣 Conclusion
By leveraging machine learning, businesses can predict customer default risk, optimize revenue, and launch targeted marketing campaigns towards low-risk, high-revenue customer segments
