# Stock-Price-Prediction
 INTRODUCTION
The stock market is one of the most interesting places for a data scientist to play. There is a lot of data, and the possibilities for analysis and prediction are unlimited. It is also one of the hot topics students love to use when they start to learn Machine Learning, after all, who doesn’t want to know if a share will have a higher or lower price?
However, work with this kind of data can be a little bit tricky, especially out of the comfort zone of Kaggle datasets, when you want to select the stocks that interest you to analyze. Also, what is the correct price we should use to make visualizations and predictions? And how to make a simple yet effective visualization?

 FRAMEWORKS 
Let’s get started with the data. It will come from yahoo finance, where we can look for any company listed on different stock markets by searching its name or symbol:
Besides the historical data, you can find useful information about the company in the other tabs. Source.
I have highlighted two tools that are really useful for us: we can select the time frame we want to see for that stock, and we can also download that data. Pretty cool, isn’t it? What if I show you that there’s something even better: we can access this data straight from our python notebook!
Load the libraries we need, including pandas_datareader_, the one which will retrieve the information we need to collect;
We define the date range for the data (remember to use the format YYYY-MM-DD);
Extracting info from yahoo finance and loading it into a data frame Source.
Simple and easy, right? This way, you can get data from any share you want, selecting the dates you wish to analyze, all that without downloading NOTHING AT ALL! I don’t know you, but I love when I don’t need to add another file to my already messy computer.
A common approach is to use the close value for analysis and prediction, but which one to choose, as we have “close” and “adjusted close”? Well, according to some sources, like this one and this one, the adjusted price is the most indicated, as it represents a fair picture of the share price, including factors like payment of dividends, stock splits,
We construct the plots with multiple layers of code. It is literally a game of try and test, until we got something that doesn’t scare us (or an error). 
To finalize, now it comes the importance of knowing how to interpreter a graph, one of the most important skills for a data analyst/scientist. With this simple plots, we can already produce interesting insights about our stocks.

Problem statement
 Predict the stock price after a 90day study of Apple , Google, and Samsung’s stock price.
