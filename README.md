# Google-Stock-Price-Movement-Prediction

# Project Overview

This project builds a machine learning–based stock market prediction system to forecast the direction of Google stock price movement (UP/DOWN) using historical market data, technical indicators,
and classification modelling.
In addition to prediction, the project also implements a rule-based trading strategy with backtesting to evaluate real-world profitability.

Project Objectives

Analyse historical stock market data
Engineer meaningful financial features
Build a classification model to predict price direction
Evaluate model performance
Simulate a trading strategy using predictions
Compare strategy returns with actual market returns
Integrate real-time stock data using APIs

Feature Engineering

To improve model performance, several financial indicators were created:
Daily returns
Price range
Moving averages
Momentum indicators
Volatility measures
Volume changes


Machine Learning Model Used: XGBoost Classifier

Chosen because:
Works well on structured/tabular data
Handles nonlinear relationships
Provides strong predictive performance
Widely used in financial modelling


Trading Strategy Implementation

A rule-based trading logic was applied:
BUY when the model predicts a price increase
No trade when the model predicts a decrease

The strategy calculates:
Daily market returns
Strategy returns
Cumulative portfolio growth
This allows evaluation of real-world profitability.


API Integration

The project also integrates livestock data using APIs:
REST API
Fetches real-time stock data from financial data providers
WebSocket API
Enables continuous streaming of live stock price updates
Demonstrates real-time data handling capability
