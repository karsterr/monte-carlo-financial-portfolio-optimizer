# Monte Carlo Simulation for Financial Portfolio Optimization

## 🚀 Project Overview
This Decision Support System (DSS) project applies **Monte Carlo Simulation** to a financial investment problem. The goal is to forecast the potential future performance (risk and return) of a diversified portfolio and use these forecasts to determine the optimal asset allocation that meets a specific investor's risk tolerance.

This showcases expertise in quantitative modeling, simulation, and building analytical tools for complex business decisions.

## ⚙️ Key Technologies
* **Python, Pandas, NumPy:** Data acquisition and simulation.
* **Matplotlib / Plotly / Streamlit:** Visualization and building the interactive DSS interface.
* **Monte Carlo Simulation:** The core forecasting algorithm.
* **Quantitative Finance Metrics:** Sharpe Ratio, Volatility, Expected Return.

## 📋 Project Scope and Deliverables
1.  **Historical Data Acquisition:** Gathering historical price data for a basket of stocks/assets (e.g., using **yfinance**).
2.  **Simulation Engine:** Implementing the Monte Carlo simulation to project thousands of potential future price paths for the portfolio.
3.  **Optimization:** Using the simulation results to identify the **Efficient Frontier** and locate the portfolio with the maximum Sharpe Ratio (optimal risk-adjusted return).
4.  **DSS Interface:** Building a simple **Streamlit/Dash** web application that allows the user to input their desired risk level and instantly visualize the corresponding optimal asset weights and forecasted returns.

## 📊 Results and Benchmarks
The simulation, run over [NUMBER] iterations, successfully identified the optimal portfolio allocation that maximized the Sharpe Ratio at **[SHARPE RATIO VALUE]**, forecasting a **[RETURN VALUE]%** average annual return with a **[RISK VALUE]%** volatility.

## 🏃 Getting Started
1.  Install the required libraries: `pip install -r requirements.txt`
2.  Run the DSS application: `streamlit run dss_app.py`
3.  Interact with the optimization parameters via the web interface.
