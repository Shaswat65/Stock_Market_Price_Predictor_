Stock Price Prediction using Machine Learning
Overview

This project is a stock price prediction system built using Python and Machine Learning. It fetches real-time stock data and predicts future prices using a Linear Regression model.

The model analyzes historical stock trends and forecasts prices for the upcoming days.

Features
1) Fetch real-time stock data using yfinance
2) Supports NSE and BSE markets
3) Machine Learning model using Linear Regression
4) Displays:
    -Actual prices
    -Predicted trend
    -Future predictions
5) Predicts stock prices for the next 7 days
6) Visualization using Matplotlib

Tech Stack
Python
NumPy
Pandas
yFinance API
Scikit-learn
Matplotlib

Project Structure
📁 Stock-Prediction
│── mini project.py
│── README.md

Installation
1. Clone the repository
git clone https://github.com/your-username/stock-price-prediction.git
cd stock-price-prediction
2. Install dependencies
pip install numpy pandas yfinance matplotlib scikit-learn

 Usage

Run the script:

python "mini project.py"
Input:
Stock ticker (e.g., TCS, RELIANCE)
Market (NSE or BSE)
Output:
Predicted prices for next 7 days
Graph showing trends and predictions
Example Output
Predicted stock prices for the next 1 week:
2026-03-30: ₹3520.45
2026-03-31: ₹3532.10
...
How It Works
1) Fetches stock data using yfinance
2) Converts dates into numerical format (ordinal values)
3) Trains a Linear Regression model

Predicts:
Past trend
Future stock prices
Visualizes results using graphs

(Reference implementation: )

Feel free to fork the repo and submit pull requests!

License
This project is open-source and available under the MIT License.

Author

Shaswat Behera
