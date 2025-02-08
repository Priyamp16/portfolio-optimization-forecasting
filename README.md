# portfolio-optimization-forecasting
This project focuses on portfolio optimization using Mean-Variance, Black-Litterman models, Monte Carlo simulations, and ARIMA/LSTM forecasting to enhance investment strategies. Implemented in Python &amp; Quarto, it improved risk-adjusted returns by 15% over benchmark performance.

📌 Overview

This project explores portfolio optimization and return forecasting using financial models. It applies Mean-Variance Optimization, Black-Litterman Model, Monte Carlo Simulations, and Risk Parity to optimize asset allocation. Additionally, ARIMA and LSTM models are used for stock return forecasting.

📊 Key Results

Mean-Variance Optimization: Sharpe Ratio 0.578, Expected Return 15.3%
Black-Litterman Model: Expected Return 10.71%, Volatility 27.26%
Monte Carlo Simulation: Best Sharpe Ratio 0.92, Expected Return 28.20%
Risk Parity Portfolio: Balanced allocation with Sharpe Ratio of 0.63
Grey Wolf vs. Particle Swarm Optimization: Grey Wolf achieved higher Sharpe (1.05) & return (25%)
ARIMA & LSTM Forecasting: Predicts future stock returns based on historical trends

📂 Project Structure

portfolio-optimization-forecasting/
│── README.md  # Project Documentation  
│── Project-code.ipynb  # Jupyter Notebook with full analysis  
│── Project Report.pdf  # Detailed report on methodologies & results   

🛠️ Technologies & Libraries Used

Python: Pandas, NumPy, SciPy, Matplotlib, Seaborn
Portfolio Optimization: PyPortfolioOpt, CVXPY, SciPy Optimization
Forecasting Models: ARIMA (Statsmodels), LSTM (TensorFlow/Keras)
Monte Carlo Simulation & Risk Models: Pyswarms, YFinance API

⚡ How to Run the Project

1. Install Dependencies

pip install numpy pandas scipy matplotlib seaborn yfinance pypfopt pyswarms cvxpy statsmodels tensorflow keras

2. Run Jupyter Notebook

jupyter notebook

3. Open and Execute Project-code.ipynb
