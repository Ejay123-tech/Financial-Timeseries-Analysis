# Financial-Timeseries-Analysis
## 📊 Volatility Modeling Using GARCH(1,1)
This project addresses the challenge of modeling time-varying volatility in financial markets, which is critical for risk management, option pricing, and investment decision-making.
Capturing volatility dynamics helps anticipate market shocks and allocate assets more effectively.
Todo this, the volatility dynamics of selected FTSE-listed stocks — **HSBC Holdings (HSBA.L)**, **BP PLC (BP.L)**, and **Shell PLC (SHEL.L)** —  were explored using the **GARCH(1,1)** model.

## 🔍 Summary
- **Data Source:** Historical stock data obtained from `yfinance` and manual download of the inrest rates from Bank of Euroupe website.
- **Preprocessing:** Log returns were computed, and data was cleaned and aligned.
- **Exploratory Analysis:** ACF and PACF plots were used to assess autocorrelation.
- **Modeling Approach:** The GARCH(1,1) model was fitted to capture conditional volatility.
- **Key Insights:** All stocks exhibit high volatility persistence (`α + β ≈ 1`), with varying degrees of shock sensitivity and memory.
- **Reporting:** A comprehensive report was generated using LaTeX, outlining methodology, diagnostics, results, and interpretations.

## 📁 Output Highlights
- 📈 ACF/PACF visualizations
- 🧮 GARCH parameter estimates for all three stocks
- 📄 [LaTeX Report (PDF)](link-to-pdf) 

## 🛠 Tools Used
- Python (`pandas`, `yfinance`, `arch`, `statsmodels`, `matplotlib`)
- Jupyter Notebook
- LaTeX (compiled on Overleaf)

---

📌 **Insight:** The GARCH model effectively captures financial time series volatility, offering valuable insights for risk modeling and forecasting.
