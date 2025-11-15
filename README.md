# Stock Return Explorer

A clean, structured exploration of stock returns using Python and pandas. This project examines price behaviour, daily and log returns, cumulative performance, and rolling volatility, with clear visualisations and explanations to build core quantitative finance skills.

---

## 📈 Features

- Load and clean historical stock price data  
- Calculate simple and log returns  
- Plot cumulative returns and return time series  
- Analyse rolling volatility and other rolling statistics  
- Explore return distributions (histograms, kernel density, summary metrics)  
- Well-organised exploratory Jupyter notebook

---

## 📂 Project Structure

    stock-return-explorer/
    │
    ├── notebooks/
    │   └── 01_exploration.ipynb
    │
    ├── src/
    │   ├── data_loader.py
    │   ├── returns.py
    │   ├── plots.py
    │   └── utils.py
    │
    ├── data/
    │   ├── raw/
    │   └── processed/
    │
    ├── requirements.txt
    ├── .gitignore
    └── LICENSE

---

## 🚀 How to Run

Clone and set up the environment:

    git clone https://github.com/danielthompson0/stock-return-explorer.git
    cd stock-return-explorer

    python -m venv .venv
    source .venv/bin/activate      # Mac / Linux
    .venv\Scripts\activate         # Windows

    pip install -r requirements.txt

Launch Jupyter:

    jupyter notebook

Then open the notebook:

    notebooks/01_exploration.ipynb

---

## 🧠 Concepts Included

- Simple vs log returns  
- Cumulative return curves  
- Rolling windows for time-series analysis  
- Volatility as standard deviation of returns  
- Visual interpretation of market behaviour  

---

## 🔭 Future Enhancements

- Add multi-ticker comparison  
- Weekly and monthly resampling  
- Add Sharpe/Sortino ratio calculations  
- Correlation heatmaps  
- More advanced visualisation options

---

## 📜 Licence

Released under the MIT licence. See the `LICENSE` file for details.
