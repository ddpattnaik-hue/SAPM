# Security Analysis and Portfolio Management (SAPM) – Jupyter Notebooks
This repository contains Jupyter notebooks developed for the **Security Analysis and Portfolio
Management (SAPM)** course at **IMI Bhubaneswar**. The notebooks cover **portfolio
optimisation, asset class analysis, and technical analysis of financial data**.
These notebooks are designed for both academic and practical use, helping learners and
researchers explore modern portfolio theory, asset allocation, technical indicators, and predictive
modelling using Python.

## Repository Contents
1. **Portfolio Analyses and Optimisation of Different Asset Classes - IMI B SAPM 2025.ipynb**
- Focuses on portfolio construction and optimisation across different asset classes.
- Implements portfolio theory concepts such as risk-return trade-offs, efficient frontier, Sharpe ratio,
and diversification.
- Uses data from multiple asset classes (equities, commodities, currencies, etc.) for optimisation.
2. **SAPM Technical Analysis - On Downloaded Data, Technical Indicators, Predictive
Models.ipynb**
- Focuses on technical analysis of financial time-series data.
- Implements commonly used technical indicators (moving averages, RSI, MACD, Bollinger Bands,
etc.).
- Builds and evaluates signal-based trading strategies.

## Configuration and Requirements
The project is built and tested with the following configuration:
- **Python**: 3.10+
- **Jupyter Notebook / Jupyter Lab**
- **pip**: 24.0
### Required Python Libraries
pip install numpy==1.26.4
pip install pandas==2.2.2
pip install matplotlib==3.9.0
pip install seaborn==0.13.2
pip install scikit-learn==1.5.1
pip install statsmodels==0.14.2
pip install scipy==1.13.1
pip install pmdarima==2.0.4
Optional (if you want advanced visualisation or optimisation):
pip install plotly==5.22.0
pip install cvxpy==1.4.2

## How to Run
git clone https://github.com/<your-username>/SAPM-Notebooks.git
cd SAPM-Notebooks
pip install -r requirements.txt
jupyter notebook

## Learning Outcomes
- Understand and implement **portfolio optimization** techniques.
- Apply **technical indicators** for financial analysis.
- Visualize and interpret financial data effectively.

## Notes
- Data for the notebooks is fetched using **Yahoo Finance (yfinance)**. Please ensure an active
internet connection.
- The predictive models are educational and may not guarantee real-world trading profits.

## Citation / Acknowledgment
If you use these notebooks for academic or research purposes, please cite:
**Pattnaik, Debidutta (2025). Security Analysis and Portfolio Management (SAPM) – Jupyter
Notebooks. IMI Bhubaneswar.**
