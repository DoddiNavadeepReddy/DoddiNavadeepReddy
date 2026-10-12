# 🪙 Gold Oracle

> A Python data pipeline that tracks global gold futures and USD/INR rates, applies Indian tax logic (GST and import duty), and forecasts 2026 price trends with machine learning.

Built for **Road to Devfest: Opensource Edition** · GDG Cloud Bengaluru
📍 Google Ananta, Bengaluru · 📅 October 24, 2026

## Problem
International gold prices are quoted in USD, but buyers in India pay in INR after GST and import duty. It is hard to see what a price move abroad means for the price you actually pay at home.

## Solution
Gold Oracle fetches market data, converts it to INR, adds domestic tax and duty, and forecasts the trend. It also shows volatility visually.

## Key Features
- **Market data integration:** pulls historical and live gold futures and USD/INR data with `yfinance` and `requests`
- **Tax and cost adjustment:** applies GST, import duty and handling fees to get the Indian price
- **Automated data cleaning:** prepares the raw data for modeling
- **Predictive modeling:** Scikit-Learn Linear Regression with a momentum-based bullish signal
- **Visualization:** trend charts and Seaborn volatility heatmaps

## Tech Stack
- Python 3.10+
- pandas, NumPy, scikit-learn
- yfinance, requests
- matplotlib, seaborn

## Getting Started

### Installation
git clone https://github.com/DoddiNavadeepReddy/Gold-oracle.git
cd Gold-oracle
pip install -r requirements.txt

### Run
python gold_analytics.py

## Sample Output
<!-- Add a trend chart and heatmap screenshot here -->

## Built During the Sprint
- [x] Describe what you added at the event
- [x] e.g. new feature, cleanup, or an open-source tool integration
- [ ] Planned: next improvement

## Contributing
Contributions are welcome. Fork the repo, create a branch, and open a pull request.

## Disclaimer
This project is for learning and analysis only. It is not financial advice.

## License
MIT License

## Author
**Doddi Navadeep Reddy** · [GitHub](https://github.com/DoddiNavadeepReddy)
