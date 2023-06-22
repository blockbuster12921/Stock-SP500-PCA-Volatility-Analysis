# <b>SP500 STOCK VOLATILITY ANALYSIS WITH GARCH</b>
## <b>Installation</b>
Use pip to install bs4
```bash
pip install bs4
```
Use pip to install pandas
```bash
pip install pandas
```
Use pip to install yfinance
```bash
pip install yfinance
```
Use pip to install requests
```bash
pip install requests
```
Use pip to install polygon
```bash
pip install polygon
```
Use pip to install statsmodels
```bash
pip install statsmodels
```
Use pip to install plotly
```bash
pip install plotly
```
Use pip to install matplotlib
```bash
pip install matplotlib
```
Use pip to install seaborn
```bash
pip install seaborn
```
Use pip to install scikit-learn
```bash
pip install scikit-learn
```
Use pip to install arch
```bash
pip install statsarchmodels
```
## PCA ANALYSIS AND GARCH MODEL ON SP500
Task 1: Use the uploaded SP500 data to carry out the PCA analysis of the PCA notebook for the years 2010 to the present. Your main challenge here is that you need to generate the corresponding SP500 price index yourself. You may use either Yahoo Finance as per the Python code or FRED as per the GARCH notebook. <br>
Task2: Repeat Task 2 for daily stock returns rather than stock prices. Compare the eigen portfolios of prices and returns. <br>
Task 3: To study the stability of the two-year eigen portfolios, conduct a rolling two-year PCA analysis from 2010 until the present. Do so for both daily stock prices and daily stock returns. For analysis consistency, use a one-year overlap between successive periods. Plot the maximum eigenvalues of the two-year covariance matrices year to year. Comment on the stability of the maximum eigenvalues. Comment on the stability of the number of components needed to explain 95% of asset variances. <br>
Task 4: Repeat Task 3, for weekly stock prices and returns. What are your observations in comparison to the daily eigen portfolios? <br>
Task 5: According to the market sector you have been assigned, extract market data for your stock tickers from 2010-01-01 until 2023-03-11. Conduct a two-year rolling PCA analysis on your market sector, comparing the stability of daily and weekly eigen portfolios for both prices and returns. <br>
Task 6: Select a favorite stock from your sector and develop a daily volatility model for its log return using two-year data. Use a GARCH model of the same order as in the GARCH notebook. Study the stability of your stock return GARCH model year-to-year and compare it with the volatility of the SP500 index. <br>
Task 7: Repeat Task 6 for the major eigen portfolio in your market sector.<br>
Task 8 : Repeat Tasks 6 and 7 for weekly log returns and compare the daily and weekly volatility models.
## Run the Jupyter notebook
Run main.ipynb.