# Yes-Bank-Stock-Closing-Price-Prediction-main

This project focuses on predicting the monthly closing stock price of Yes Bank using Machine Learning techniques.
The stock market is highly dynamic and influenced by financial performance, public sentiment, and major events. Since 2018, Yes Bank has been significantly affected due to the fraud case involving Rana Kapoor. This project analyzes historical stock data and builds predictive models to estimate future closing prices.

🎯 Objective

* Analyze historical stock price data of Yes Bank
* Perform Exploratory Data Analysis (EDA)
* Handle multicollinearity and skewness
* Build regression models for stock price prediction
* Compare model performance
* Select the best performing model

📂 Dataset Description

The dataset contains 185 rows and 5 features:

# Feature	Description
* Date	Month and Year of stock trading
* Open	Opening price of the stock
* High	Highest price during the month
* Low	Lowest price during the month
* Close	Closing price of the stock (Target Variable)
  
🛠️ Technologies Used

Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-learn

🔍 Project Workflow

1. Data Preprocessing
* Converted Date column to datetime format
* Checked and handled missing values
* Applied log transformation to reduce skewness

2️. Exploratory Data Analysis (EDA)
* Univariate and bivariate analysis
* Correlation heatmap
* Trend analysis before and after 2018

3️. Model Building
--The following regression models were implemented:
* Linear Regression
* Lasso Regression (with Cross-validation)
* Ridge Regression (with Cross-validation)
* Elastic Net Regression (with Cross-validation)

4. Model Evaluation
* Evaluation metrics used:
* RMSE (Root Mean Square Error)
* R² Score
  
5. Best Performing Model:
* Elastic Net Regression
* RMSE ≈ 8.37
* R² ≈ 0.9938

5. Key Insights

* Stock prices increased steadily until 2018.
* A sharp decline is observed after the fraud case.
* Strong correlation exists between Open, High, Low, and Close prices.
* Regularization techniques helped reduce multicollinearity.

All models achieved over 99% accuracy (R² score).

6. Conclusion

Elastic Net Regression performed the best among all models. The project demonstrates how machine learning techniques can effectively predict stock closing prices using historical data.
The trained model can be further improved by:
* Adding more external financial indicators
* Using daily stock data
* Implementing advanced models like XGBoost or LSTM

👨‍💻 Author

Sudarshan Vinod Mhatre
