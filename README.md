# stock_trend_prediction_webapp
Building a stock prediction web app using Streamlit in Python. Here's a comprehensive guide to help you create a basic stock prediction web app. I have used libraries such as yfinance for fetching stock data, Scikit-learn for building a simple machine learning model, and Streamlit for the web interface.
Data Loading: The load_data function fetches historical stock data for the given ticker symbol.
Data Preparation: The prepare_data function creates a feature matrix X and target vector y by shifting the 'Close' price column to create the prediction target.
Model Training: The train_model function splits the data into training and testing sets, trains a linear regression model, and evaluates its performance using mean squared error.
Streamlit Interface: The main function builds the Streamlit interface, allowing users to input a stock ticker symbol, view the raw data, see the model's mean squared error, and compare actual vs. predicted prices.
