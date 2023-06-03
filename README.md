<p align="center"> 
  <img src="images/yes_bank.jpg" alt="YES BANK" width="200px" height="200px">
</p>
<h1 align="center"> Stock Price Predictor</h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p align="center"> 
<img src="images/stock_price.jpg" alt="" height="382px">
</p>


I have explored historical stock price data, applied statistical analysis and machine learning techniques to uncover patterns and correlations, enabling insights into price trends, volatility, and factors influencing stock performance. I also created Triple Exponential Smoothing model for price predictions.

# :floppy_disk: Project Files:
This project contains three directories, one model as follows:
<ul>
 <li><b> notebooks: </b> This Folder contains .ipynb for the project</li>
 
 <li><b> data: </b> This folder contains</li>
 <t>a. data_YesBank_StockPrices.csv : The raw data.</t><br>
 <t>b. intermediate.csv : The data processed to gain insights and performing EDA.</t><br>
 <t>c. final_data.csv : The data used for modelling purposes.</t>
  <li><b> reports: </b> This contains the powerpoint presentation related to the project. 
<li><b> model: </b> The model is joblib file of triple exponential smoothing. </li>
 </ul>
 
<h2> :book: Triple Exponential Smoothing</h2>
Exponential smoothing is a time series forecasting method for univariate data that can be extended to support data with a systematic trend or seasonal component.Exponential smoothing forecasting methods are similar in that a prediction is a weighted sum of past observations, but the model explicitly uses an exponentially decreasing weight for past observations.<br>
<br>
Triple Exponential Smoothing is an extension of Exponential Smoothing that explicitly adds support for trend and seasonality to the univariate time series.

This method is sometimes called Holt-Winters Exponential Smoothing, named for two contributors to the method: Charles Holt and Peter Winters.

It has 3 smoothing factors, alpha, beta and gamma that controls the influence on the level, trend and seasonal component respectively.

The trend, the seasonality may be modeled as either an additive or multiplicative process for a linear or exponential change in the trend as well as seasonality.

<b>Hyperparameters:</b>

<li>Alpha: Smoothing factor for the level.<br></li>
<li>Beta: Smoothing factor for the trend.<br></li>
<li>Gamma: Smoothing factor for the seasonality.<br></li>
<li>Trend Type: Additive or multiplicative.<br></li>
<li>Dampen Type: Additive or multiplicative.<br></li>
<li>Phi: Damping coefficient.<br></li>
<li>Seasonality Type: Additive or multiplicative.<br></li>
<li>Period: Time steps in seasonal period.<br></li>
