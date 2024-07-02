#AlmaBetter Verfied Project - AlmaBetter School

Yes Bank Stock Closing Price Prediction

Table of Contents
1.	Introduction
2.	Models Used
3.	Evaluation Metrics
4.	How to Execute
5.	Dataset
6.	Conclusion and Future Considerations

Introduction
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.
A Stock or share (also known as a company’s 'equity') is a financial instrument that represents ownership in a company. Units of stock are called "shares." Stocks are bought and sold predominantly on stock exchanges, though there can be private sales as well, and are the foundation of many individual investors' portfolios.

Dataset
The dataset used in this project is stored in the "data" folder. You can access it by clicking here.

Objective:
The objective of this project is to analyze the impact of a fraud case involving Rana Kapoor on the stock prices of Yes Bank, a prominent bank in the Indian financial domain. The dataset used in this project consisted of monthly stock prices of Yes Bank since its inception, including closing, starting, highest, and lowest stock prices.

Prediction Models:
To predict the stock's closing price, I developed three models: Ridge Regression, Random Forest, and XGBoost Regressor. These models were trained using historical stock price data and various features, including the mean of Open, High, and Low prices. Additionally, lag features were engineered to capture temporal trends in the data. The XGBoost Regressor model performed exceptionally well both on training and test datasets.
1.	Ridge Regression:
o	Type: Linear regression with regularization.
o	Explanation: Ridge Regression adds a penalty to feature coefficients, reducing overfitting in linear regression models.
o	Usage: Effective for balancing model complexity and performance, especially when dealing with multicollinearity.

2.	Random Forest:
o	Type: Ensemble learning model based on decision trees.
o	Explanation: Random Forest creates multiple decision trees, each trained on different data subsets, and combines their predictions for robust and accurate results.
o	Usage: Versatile model suitable for both classification and regression tasks, known for handling high-dimensional data and capturing complex patterns.

3.	XGBoost Regressor:
o	Type: Ensemble learning model using gradient boosting.
o	Explanation: XGBoost builds an ensemble of decision trees sequentially, correcting errors from previous trees using gradient-based optimization, resulting in high predictive accuracy.
o	Usage: Widely used in competitions and real-world applications for its exceptional predictive performance and adaptability to various data types.

Evaluation Metrics:
The performance of the models was evaluated using the following metrics: Certainly, here are concise explanations of each evaluation metric in 2-3 lines:
1.	RMSE (Root Mean Squared Error):
o	Explanation: RMSE quantifies the average magnitude of prediction errors by taking the square root of the mean of squared differences between predicted and actual values. Lower RMSE indicates better prediction accuracy, with 0 being a perfect fit.
o	Usage: RMSE helps assess how closely a regression model's predictions align with actual data points, making it a widely used measure of prediction quality.

2.	Adjusted R2 (Adjusted R-squared):
o	Explanation: Adjusted R2 adjusts the traditional R-squared metric for the number of predictors in a model. It penalizes excessive predictors and provides a more realistic measure of model fit. Higher values signify better model fit.
o	Usage: Adjusted R2 helps evaluate whether adding more features to a model improves its explanatory power or merely adds noise, aiding in the selection of relevant predictors.

3.	R2 Score (Coefficient of Determination):
o	Explanation: R2 score quantifies the proportion of variance in the dependent variable explained by the model's independent variables. It ranges from 0 to 1, with higher values indicating a better fit. A score of 1 implies perfect fit.
o	Usage: R2 score provides an overall measure of how well a regression model captures the relationships between predictors and the target variable, aiding in model assessment and comparison.

How to Execute:
To execute this project and make predictions on Yes Bank's closing stock prices, follow these steps:
1.	Open the Jupyter Notebook file named Yes_Bank_Stock_Price_Prediction.ipynb:
2.	Execute the notebook cell by cell to load and preprocess the data, train the machine learning models, and make predictions.
3.	The notebook provides detailed insights into data analysis, feature engineering, model training, and evaluation.

Conclusion and Future Considerations
The main goal of the project is to create a machine learning model capable of predicting the closing price of Yes Bank stock, taking into account the impact of the fraud case involving Rana Kapoor. The XGBoost Regressor model performed exceptionally well, achieving a high R2 score.
Future considerations for enhancing this project include:
•	Exploring daily-level stock price data for finer predictions.
•	Incorporating additional features such as holidays, political decisions, events, and volume data.
•	Evaluating time series models like ARIMA and LSTM for more precise stock price predictions.
With the current dataset and features, the model performs well on all data points.
I believe that this detailed README provides you with all the necessary insights to delve into the world of "Yes Bank Stock Closing Price Prediction. May your predictions be accurate, and your financial decisions be informed! 📈💰

