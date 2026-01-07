# CAR3E-Project
# Still currently working on this project

Python Components (3 files)

data_loader.py - Data pipeline that fetches FX rates, volatility indices, equity data, and generates synthetic interest rates
carry_return_model.py - Calculates carry trade profitability with volatility adjustments, Sharpe ratios, and drawdown analysis
ml_unwind_predictor.py - Machine learning models (Logistic Regression + Random Forest) to predict carry trade unwind events

R Components (1 file)

markov_regime_model.R - Markov regime-switching model that classifies markets into risk-on, transitional and crisis regimes


Java Components (1 file)

StressTestEngine.java - High-performance Monte Carlo stress testing engine with parallel execution (10,000+ simulations)

Key Features Implemented
Data Pipeline

Automatic data fetching from Yahoo Finance
Synthetic interest rate generation (placeholder for real APIs)
Data merging and cleaning

Carry Trade Analysis

Interest rate differential calculation
FX return tracking
Volatility-adjusted returns
Maximum drawdown analysis
Sharpe ratio calculation

ML Risk Prediction

15+ engineered features
Binary classification (unwind vs. no unwind)
Model comparison (Logistic Regression vs Random Forest)
Feature importance visualization
ROC-AUC evaluation

Regime Detection

3-regime Markov-switching model
Automatic regime classification
Transition detection
Early warning signals

Stress Testing

4 pre-built stress scenarios
Parallel Monte Carlo simulation
VaR and CVaR calculation
Margin call probability
Risk assessment dashboard
