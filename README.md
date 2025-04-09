# Fintech AI Agent

**Fintech AI Agent** is an interactive Streamlit web application designed to help users make informed financial decisions. It features tools for calculating compound interest, fetching live stock prices, and explaining complex financial terms using AI. This app is built using Python, Streamlit, Yahoo Finance API, and Groq's AI model.

## Features

### 📈 Compound Interest Calculator
- Calculate the future value of an investment based on the principal amount, annual interest rate, and duration in years.
- Get quick insights into how investments grow over time with compound interest.

### 💹 Live Stock Price Checker
- Fetch real-time stock prices from Yahoo Finance by entering stock ticker symbols (e.g., AAPL, TSLA, GOOG).
- Stay updated on the latest market trends and stock prices.

### 🧠 Explain Financial Terms
- Get clear and simple explanations of financial terms such as inflation, mutual funds, and more using Groq's AI model.
- Ideal for beginners looking to understand finance jargon.

## Installation
# Clone the repository
git clone https://github.com/fahadqureshi0/fintech-ai-agent.git
cd fintech-ai-agent

# Create a virtual environment

python -m venv venv

# Activate the virtual environment

# For Windows:

# .\venv\Scripts\activate

# For macOS/Linux:

source venv/bin/activate

# Install the required dependencies

pip install -r requirements.txt

# Replace the API key in the code (Manually add Groq API key in the app.py file)

# Run the application
streamlit run app.py

