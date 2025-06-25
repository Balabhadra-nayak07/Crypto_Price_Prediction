# 🪙Crypto Price Prediction Using LSTM

This project aims to predict Bitcoin (BTC-USD) prices using a deep learning approach with Long Short-Term Memory (LSTM) networks. Built as a part of the MCA program at Chaitanya Deemed to be University (2023–2025), this project helps understand and forecast cryptocurrency trends using historical data.

📌 Project Overview

Bitcoin and other cryptocurrencies experience high price volatility due to factors like market speculation, regulations, and technological changes. Accurate price forecasting is valuable for investors and analysts.

This project uses:

LSTM neural networks for time-series prediction

10+ years of BTC-USD historical data from Yahoo Finance

A Flask web app interface for user input and visualization



---

🧠 Key Features

📈 Forecast Bitcoin prices using historical data

🧮 Built using LSTM model (128 + 64 units)

📊 Interactive plots: price trends, predictions, and forecasts

🔧 Data preprocessing with normalization and sliding windows

💻 Easy-to-use Flask-based web UI for predictions



---

🧰 Tech Stack

Frontend/UI: HTML (via Flask)

Backend: Python, Flask

Libraries:

yfinance

pandas

numpy

matplotlib

keras / tensorflow

sklearn




---

🏗️ System Architecture

1. Data Collection: Historical BTC data from Yahoo Finance using yfinance.


2. Preprocessing: Clean, normalize, handle missing data, and create time windows.


3. Model Building: Deep LSTM network to learn and predict price patterns.


4. Prediction Module: Uses last 100 days to forecast N future days.


5. Visualization: Display price charts using Matplotlib.


6. Web App: Flask UI to enter crypto symbol and prediction days.




---

📸 Screenshots

Historical vs. Predicted Graphs

Future Price Forecasts

Interactive Charts on Flask Web App


(Screenshots available in the project repo or /screenshots folder)


---

🖥️ Requirements

Hardware

Minimum: Dual Core CPU, 4 GB RAM

Recommended: Quad Core CPU, 8 GB RAM, SSD


Software

Python 3.7+

Flask

Chrome/Firefox for accessing UI



---

🚀 How to Run

git clone https://github.com/your-username/crypto-price-prediction.git
cd crypto-price-prediction
pip install -r requirements.txt
python app.py

Then open your browser and go to:
http://localhost:5000


---

📚 Future Enhancements

Add support for other cryptocurrencies (ETH, DOGE, etc.)

Integrate real-time data

Include sentiment analysis and news-based features

Improve model accuracy with hybrid ML techniques



---

👥 Team

G Shankar (123164413)

Balabhadra Nayak (123164403)

MCA, Department of Computer Science

Chaitanya Deemed to be University



---

📄 License

This project is for academic and learning purposes only.ce_Prediction
