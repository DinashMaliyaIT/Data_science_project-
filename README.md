 KSE 100 Index Forecasting
This project uses machine learning techniques to forecast the KSE 100 index based on historical data and external factors like crude oil prices, foreign exchange rates, and trading volumes. The project leverages linear regression to predict future stock prices and evaluates the model's performance using common metrics such as MSE, MAE, RMSE, and R².

 Project Overview
The goal of this project is to predict the closing prices of the KSE 100 index using historical stock data and external market data such as crude oil prices and foreign exchange rates. By integrating these external factors, the model aims to improve stock price prediction accuracy.

 Data Sources
•	KSE 100 Index Data: Contains historical data for KSE 100 index prices and trading volumes.
•	Crude Oil Prices: Contains global crude oil price data.
•	Foreign Exchange Rates: Contains data on the exchange rate of the Australian Dollar (AUD) to USD.

 Key Features
•	Data Preprocessing: Cleans and processes the raw data for model training. This includes removing commas, converting date formats, and handling missing values.
•	Feature Engineering: New features like `Prev_Close` (previous day's closing price) are created to improve model prediction accuracy.
•	Machine Learning Model: Uses Linear Regression to predict the future KSE 100 closing prices.
•	Evaluation Metrics: The model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R².
•	Visualization: Provides graphical analysis such as correlation heatmaps, residual plots, and distribution comparisons of actual vs. predicted values.
 Installation
•	To run this project, follow the steps below:
•	Clone the repository:
•	git clone https://github.com/DinashMaliyaIT/Data_science_project.git
•	cd Data_science_project

Install dependencies:
•	pip install pandas numpy scikitlearn matplotlib seaborn
•	pip install r requirements.txt

Usage
1.	Prepare the data: Load and clean the datasets. Merge the KSE 100 index data with external factors such as crude oil prices and forex rates.
2.	Feature Engineering: Create new features like Prev_Close to provide the model with useful insights.
3.	Train the Model: Use linear regression to train the model on the prepared data.
4.	Evaluate: Assess the model's performance using MSE, MAE, RMSE, and R² to gauge its accuracy.
5.	Visualize: Generate various plots such as heatmaps, residual plots, and comparison histograms to visualize the results.

Example Output
Once the model is trained and predictions are made, the following results will be displayed:
•	Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
•	Mean Absolute Error (MAE): Measures the average absolute difference between actual and predicted values.
•	Root Mean Squared Error (RMSE): Measures the square root of the average squared differences between actual and predicted values.
•	R² (RSquared): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

GUI link 🔗 Authtoken saved to configuration file: /root/.config/ngrok/ngrok.yml
Streamlit app is live at: NgrokTunnel: "https://5d30-34-57-3-172.ngrok-free.app" -> "http://localhost:8501"
To view the GUI:
1. Add Auth token from Ngrok
2. Run Colab Notebook
3. Access the link generated to view GUI 

Additionally, visualizations such as:
•	Correlation Heatmap: Shows the relationships between features.
•	Residual Plot: Displays the residuals (errors) of the predictions.
•	Histogram of Actual vs Predicted: Compares the distribution of actual and predicted values.

Contributors
Minhal Manjee 
Dinash Maliya 
 Key Updates:  The repository link is now set to: `https://github.com/DinashMaliyaIT/Data_science_project`.  

