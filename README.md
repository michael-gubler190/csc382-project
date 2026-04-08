# S&P 500 Stock Analysis & Prediction (2015–2025)

## Overview
This project analyzes S&P 500 stock data from 2015 to 2025 to identify trends in stock value over time,
explore the influence of external factors (political and environmental), and attempt to predict stock
growth levels for 2026 using the daily closing price as our target variable.

## Hypothesis
Stock values have generally trended upward over the past decade, despite shifts in global climate and politics.

## Dataset
**Source:** [Kaggle – S&P 500 Stocks: 25 Years of Data](https://www.kaggle.com/datasets/darkmatternet/s-and-p-500-stocks-25-years-of-data-updated-daily)

**Download via Kaggle API:**
```bash
kaggle datasets download darkmatternet/s-and-p-500-stocks-25-years-of-data-updated-daily
```

**Target Variable:** `close` — the final stock price at the end of each trading day.

## Setup

### 1. Clone the repository
```bash
git clone https://github.com/michael-gubler190/csc382-project.git
cd https://github.com/michael-gubler190/csc382-project.git
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

## Contributors
- Michael Gubler
- Haley Hart