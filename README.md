Robust Multi-Agent Stock Analyst 📈🤖
An autonomous financial analysis system developed during the Google & Kaggle 5-Day AI Intensive. This project leverages Gemini 2.5 Flash-Lite and the modern Google Gen AI SDK to orchestrate a team of specialized agents that synthesize Machine Learning predictions with real-time financial data.

🚀 Overview
Unlike standard chatbots, this system uses Agentic Workflows and Function Calling to act as a Hedge Fund Manager. It doesn't just "chat"; it executes code, trains models, and retrieves live market data to provide a data-driven investment verdict.

🧠 The Agent Architecture
The system orchestrates three specialized "Agents" via Gemini:
Quant Agent (ML): Uses a RandomForestRegressor (Scikit-Learn) to analyze historical price action and predict the next day's closing price.
Technical Agent: Utilizes Pandas and yfinance to compute RSI (Relative Strength Index) and identify trend momentum (Bullish/Bearish).
Fundamental Agent: Scrapes real-time P/E ratios, Market Capitalization, and analyst recommendations to assess company health.

🛠️ Tech Stack
LLM Engine: Google Gemini 2.5 Flash-Lite
Orchestration: Google Gen AI SDK (Function Calling & Tool Use)
Machine Learning: Scikit-Learn (Random Forest)
Data Science: Pandas, NumPy
Finance API: yfinance
Environment: Kaggle (utilizing Kaggle Secrets for API security)

📋 Features
Autonomous Tool Use: The LLM decides which tool to call based on the user's query.
Predictive Analysis: Combines Generative AI reasoning with traditional Quantitative ML.
Resilience Engineering: Includes automated backoff and retry logic for 429 (Rate Limit) errors.
Live Data Pipeline: Real-time fetching of global stock tickers.

🎓 Credit
This project was completed as part of the Google & Kaggle 5-Day AI Intensive (Late 2025 Edition).
