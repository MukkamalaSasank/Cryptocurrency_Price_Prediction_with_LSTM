# Cryptocurrency Predictor

An AI-powered Flask web application that predicts cryptocurrency prices using historical data and deep learning models. Users can input a cryptocurrency ticker symbol and specify the number of future days for prediction.
> **Disclaimer:**  
> The predictions generated by this application are for educational and informational purposes only. They are not real, reliable, or accurate for financial decision-making. **Do not use these predictions to make investment decisions or risk your money.** The authors of this project are not responsible for any financial losses incurred by using this application.


## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [License](#license)

---

## Features
- **Historical Data Fetching:** Retrieves cryptocurrency data from Yahoo Finance.
- **Price Prediction:** Predicts future prices using a pre-trained Keras model.
- **Visualizations:** Generates plots for:
  - Historical closing prices.
  - Original vs predicted test data.
  - Future price predictions.
- **Interactive UI:** User-friendly interface built with Bootstrap.

---

## Technologies Used
- **Backend:**
  - Flask
  - TensorFlow/Keras
  - Yahoo Finance API (`yfinance`)
  - Pandas, NumPy
- **Frontend:**
  - HTML, CSS (via Bootstrap)
  - JavaScript for interactivity
- **Visualization:**
  - Matplotlib
- **Preprocessing:**
  - Scikit-learn (MinMaxScaler)

---

## Installation

### Prerequisites
- Python 3.8 or later
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crypto-price-predictor.git
   cd crypto-price-predictor
Create a virtual environment (optional but recommended):

bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install dependencies:

bash
pip install -r requirements.txt
Place your pre-trained Keras model file (model.keras) in the project root.

Run the Flask app:

bash
python app.py


Open your browser and navigate to:
http://127.0.0.1:5000/


Usage
Enter the cryptocurrency ticker symbol (e.g., BTC-USD).
Specify the number of future days to predict.
Click "Predict."
View the results, including plots and predicted prices.
