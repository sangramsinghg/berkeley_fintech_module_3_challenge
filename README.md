# Project Title
Analyze Bitcoin/Cryptocurrency Arbitrage opportunities.

Bitcoin/Cryptocurrency arbitrage opportunity occurs when Bitcoin/Cryptocurrency is available at a cheaper price at 
one exchange compared to another exchange. So, we can take advantage of this opportunity by purchasing the cryptocurrency
at the lower priced exchange and selling it as the higher priced exchange. The two exchanges that we analyze are bitstamp
and coinbase. During a given day, at different times, Bitcoin can be purchased at a cheaper price on bitstamp and sold at coinbase
or purchased at a cheaper price on coinbase and sold at bitstamp. We analyse all such opportunities and figure out the potential
profit in doing so. 

Looking at the entire period, it appears that there are potential arbitrage oppotunities when we see the Bitstamp plot deviate
from the Coinbase plot. 

![Bitstamp vs Coinbase Entire Period](images/bitstamp_vs_coinbase_entire_period.png)

Analyzing the earlier period vs later period, we find that there appear to be more arbitrage opportunities in the 
earlier period as compared to the later period. This is true in any arbitrage situation. Once people figure out the 
potential to profit from price difference, the gap closes very quickly. 

![Bitstamp vs Coinbase Earlier Period](images/bitstamp_vs_coinbase_earlier_period.png)
![Bitstamp vs Coinbase Later Period](images/bitstamp_vs_coinbase_later_period.png)

Analyzing specific dates in the early, middle and later periods show that there are more opportunities in the early part
of the day and even later part of the day (when the Asia market is starting to get active). During the working hours,
major arbitrage opportunities are non existent. The specific date analysis also confirms that the arbitrage opportunities
diminish in the later period as more people discover price discrepencies. 

![Bitstamp vs Coinbase Jan 16, 2018](images/bitstamp_vs_coinbase_jan_16_2018.png)
![Bitstamp vs Coinbase Feb 24, 2018](images/bitstamp_vs_coinbase_feb_24_2018.png)
![Bitstamp vs Coinbase Mar 26, 2018](images/bitstamp_vs_coinbase_mar_26_2018.png)

Analyzing the profit opportunities, it confirms that profits can be made in the earlier period but no profit in the later period.
During the earlier period, profit can be made in the early part of the day before the working hours and after working hours.

* Jan 16, 2018 - total arbitrage profits
![Cumulative Profit Jan 16, 2018](images/cumulative_profit_sum_1_16_2018.png)

* NOTE: We analyze both possibilities - bitstamp to coinbase and coinbase to bitstamp because during the day both possibilities can exist. Bitcoin can be trading lower at Coinbase at certain times and trading lower at Bitstamp at other times.

* Jan 16, 2018 - arbitrage profits from buying low at bitstamp and selling high at coinbase
![Cumulative Profit Jan 16, 2018 - bitstamp to coinbase](images/cumulative_profit_sum_1_16_2018_bitstamp_to_coinbase.png) 
* Jan 16, 2018 - arbitrage profits from buying low at coinbase and selling high at bitstamp 
![Cumulative Profit Jan 16, 2018 - coinbase to bitstamp](images/cumulative_profit_sum_1_16_2018_coinbase_to_bitstamp.png)

* Feb 24, 2018
![Cumulative Profit Feb 24, 2018](images/cumulative_profit_sum_2_24_2018.png)

---

## Technologies

This project uses python 3.7 along with the following packages:

* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - Web based user interface for data analysis.

* [pandas](https://github.com/pandas-dev/pandas) - Data analysis and manipulation library.

* [matplotlib](https://github.com/matplotlib/matplotlib) - Library for creating visualization in Python.

---

## Installation Guide

Please install the following before starting the application

```python
  pip install jupyterlab
  pip install pandas
  pip install matplotlib
```
In case of issues, please see the requirements.txt for a complete list of packages with versions needed to run this application

---

## Usage

To use the crypto arbitrage analysis, please download and open the **crypto_arbitrage.ipynb** in juypter lab after executing
the following on the command line:

```python
jupyter lab
```
Jupytper Lab should open automatically in a browser. 
If it does not, please follow the instructions on the command line.

---

## Contributors

Sangram Singh (sangramsinghg@yahoo.com)

---

## License

MIT

