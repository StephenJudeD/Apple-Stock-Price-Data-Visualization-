# Time-Series-Visualisation

Plotly Visualizations not available in Github, Please see Google Colab below to view

https://colab.research.google.com/drive/1IeBewal6Yuqj-gPkK7j6FRpCF-WojuEe#scrollTo=4b9a0797

Time series analysis. The cleanest setups, even for multiple time series, that I have noticed are plotly: px.line & seaborn: lineplot. 

 
Figure 1: Interactive Value by Month
I created a separate DataFrame for the Y axis to remove ‘Volume’ as its values are not consistent with price. I also chose the colours to be consistent – Open, Close, Adj Close are levels of green, and High and Low levels of red – this is more apparent when you zoom in as seen in the notebook Figure 2.

We can see a big drop around May 2018, why?  the company said it would no longer distribute unit sales data for any of its products – for example the number of iPhone 6’s sold, starting with the current quarter. The news allowed some analysts, and investors, to consider if the actual sales are declining – the stock drops 6.6% the following day. Markets are built on confidence, and we can see that the drop was for a limited time, and we can see below that volume wasn’t affected.

In Figure 3, and another nice element of plotly, we have ‘Time Series of Volume with Range Slider and Selectors’. 

The functionality to visualise time, in relation to volume, and with the ability to break the data down by 1m, 6m, YTD etc. makes this visualisation particularly useful for stock data. 

I chose a black line, with light grey background, as I like the contrast and feel that it makes the visualisation more appealing than the default colour.


