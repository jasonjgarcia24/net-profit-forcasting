# Welcome to the Net Profit Forcasting Project!
#### Forecasting with Facebook Prophet
***
## Cotents<a id="Contents">
[Project Description](#Project-Description)<br>
[Technologies and Resources](#Technologies-Resources)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
[Bottom of Page](#Bottom-of-Page)<br>

***
## <a id="Project-Description">Project Description</a>
This project applies time series analysis for forecasting, using Facebook Prophet, to identify trends and build predictions for both stock price and sales growth of the popular Latin American e-commerce giant <a href="https://mercadolibre.com/" title="https://mercadolibre.com/" target="_blank">MercadoLibre</a>. It also identifies MercadoLibre's online presence by analyzing related Google traffic over a period of time. Together this data can be compared to gte a better understanding of hourly, daily, monthly, and seasonal impacts on MercadoLibre's customer activity.<br>

By using Facebook Prophet, we are able to build a story of where the sales growth is currently at and where we believe it will be by identifying both short- and long-term trends. This project allows us to build this story by providing daily, weekly, monthly, and yearly visualizations to quickly understand and conclude high and low activity periods. This constructive information can aid in actionable, targeted responses for improved sales growth on all levels.<br>

Following the translation and predictions of the time series data, this project also presents an overall summary.<br> 

#### Project layout:
The layout of this project is show below.<br>
.<br>
├── crypto_investments.ipynb<br>
├── data<br>
│   └── crypto_market_data.csv<br>
├── img<br>
│   ├── crypto-performance-clustering.png<br>
│   └── elbow-plot.png<br>
│   └── project_tree.png<br>
├── LICENSE<br>
├── README.md<br>
├── requirements.txt<br>
└── tree.txt<br>

***
## <a id="Technologies-Resources">Technologies and Resources</a>
#### Technologies:
<a href="https://docs.python.org/release/3.8.0/" title="https://docs.python.org/release/3.8.0/"><img src="https://img.shields.io/badge/python-3.8%2B-red">
<a href="https://pandas.pydata.org/docs/" title="https://pandas.pydata.org/docs/"><img src="https://img.shields.io/badge/pandas-1.3.1-green"></a>
<a href="https://jupyter-notebook.readthedocs.io/en/stable/" title="https://jupyter-notebook.readthedocs.io/en/stable/"><img src="https://img.shields.io/badge/jupyter--notebook-5.7.11-blue"></a>
<a href="https://pystan.readthedocs.io/en/latest/" title="https://pystan.readthedocs.io/en/latest/"><img src="https://img.shields.io/badge/pystan-3.2.0-yellow"></a>
<a href="https://facebook.github.io/prophet/" title="https://facebook.github.io/prophet/"><img src="https://img.shields.io/badge/fbprophet-0.7.1-red"></a>
<a href="https://hvplot.holoviz.org/user_guide/Introduction.html" title="https://hvplot.holoviz.org/user_guide/Introduction.html"><img src="https://img.shields.io/badge/hvplot-0.7.3-green"></a>
<a href="https://holoviews.org/" title="https://holoviews.org/"><img src="https://img.shields.io/badge/holoviews-1.14.5-green"></a>

***
## <a id="Installation-Guide">Installation Guide</a>
### Project Installation
To install <a href="https://github.com/jasonjgarcia24/net-profit-forcasting.git" title="https://github.com/jasonjgarcia24/net-profit-forcasting.git">net-profit-forcasting</a>, type <code>git clone https://github.com/jasonjgarcia24/net-profit-forcasting.git</code> into bash in your prefered local directory.<br><br>
Alternatively, you can navigate to the same address (<code>https://github.com/jasonjgarcia24/net-profit-forcasting.git</code>) and download the full <code>main</code> branch's contents as a zip file to your prefered local directory.<br>

## <a id="Usage">Usage</a>
Observe net-profit-forcasting with <code>forecasting_net_prophet.ipynb</code>. No input variables are required.<br>

### Outputs
This tool provides several visualizations for both MercadoLibre Google traffic and sales performance analysis:
1. Hourly Google traffic trends by day of week and hour:<br>
<img src="img/mercadolibre-hourly-trends-day-of-week.png" title="MercadoLibre Hourly Trends by Day of Week"><br>
This heatmap allows us to measure the distribution of Google traffic trends for MercadoLibre.<br>

2. Hourly Google traffic trends by week of year:<br>
<img src="img/mercadolibre-hourly-trends-week-of-year.png" title="MercadoLibre Hourly Trends by Week of Year"><br>
This plot allows us to identify periods throughout the year of high and low traffic for MercadoLibre.<br>
    
3. Hourly stock price for the past five years:<br>
<img src="img/mercadolibre-hourly-stock-price.png" title="MercadoLibre Hourly Stock Price"><br>
This plot allows us to view the overall trend in MercadoLibre's stock prices over the past five years.<br>
    
4. Predicted stock price:<br>
<img src="img/mercadolibre-predicted-stock-price.png" title="MercadoLibre Predicted Stock Price"><br>
This plot reflects the Facebook Prophet prediction of MercadoLibre's expected stock price with both best and worst case ranges.<br>
    
5. Hourly, daily, weekly, and monthly treding MercadoLibre stock prices:<br>
<img src="img/mercadolibre-trends-stock-price.png" title="MercadoLibre Trending Stock Price"><br>
This plot provides an overall short- and long-term trends of MercadoLibre's stock price.<br>
    
6. Total daily revenue:<br>
<img src="img/mercadolibre-daily-revenue.png" title="MercadoLibre Daily Revenue"><br>
This plot is a general review of MercadoLibre's overall daily revenue for the past year and a half.<br>
    
7. Daily, weekly, and monthly trending daily revenue:<br>
<img src="img/mercadolibre-trends-daily-revenue.png" title="MercadoLibre Trending Daily Revenue"><br>
This plot is allows us to view the short- and long-term trends of MercadoLibre's daily revenue.<br>
    
8. Predicted daily revenue:<br>
<img src="img/mercadolibre-predicted-daily-revenue.png" title="MercadoLibre Trending Daily Revenue"><br>
This plot reflects the Facebook Prophet prediction of MercadoLibre's expected daily revenue for 2020 Q3.<br>

***
## <a id="Contributors">Contributors</a>
Currently just me :)<br>

***
## <a id="License">License</a>
Each file included in this repository is licensed under the <a href="https://github.com/jasonjgarcia24/net-profit-forcasting/blob/c95b7c4ebcb37ac7e5f2f91505f7e796137f99eb/LICENSE" title="LICENSE">MIT License.</a>

***
[Top of Page](#Top-of-Page)<br>
[Contents](#Contents)<br>
[Project Description](#Project-Description)<br>
[Technologies and Resources](#Technologies-Resources)<br>
[Installation Guide](#Installation-Guide)<br>
[Usage](#Usage)<br>
[Contributors](#Contributors)<br>
[License](#License)<br>
<a id="Bottom-of-Page"></a>
