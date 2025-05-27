# 02_Covid19_case_prediction
 COVID-19 Case Prediction Using Polynomial Regression
This project uses historical COVID-19 case data to build a time-series prediction model. Using regression techniques, the model forecasts the number of future cases and visualizes trends to help understand the growth pattern of the pandemic.

📌 Features
📅 Data Preprocessing: Converts raw CSV data into a structured format with global case totals.

📈 Trend Visualization: Histogram of case distribution to understand spread and spikes.

📉 Polynomial Regression Model: Predicts future COVID-19 cases using past trends.

📆 Future Forecasting: Generates predictions for the next 100 days.

📊 Clean Output: Provides an easy-to-read table of predicted dates and cases.

🛠️ Technologies Used
Python

Pandas

NumPy

Matplotlib

Scikit-learn

📁 Dataset
The dataset includes global daily COVID-19 case numbers. You can use publicly available datasets like:

Johns Hopkins University CSSE COVID-19 Dataset

🚀 How to Run
Clone the repository

Install required packages with pip install -r requirements.txt

Run the script (e.g., python predict.py)

View predictions and visualizations

📷 Sample Output
Histogram of case spread

Table of predicted future cases

Graph of predicted growth curve (optional)

💡 Future Improvements
Include country-wise predictions

Compare multiple regression models (e.g., Linear vs. Polynomial vs. LSTM)

Build a dashboard for live updates
