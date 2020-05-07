The rate at which COVID-19, a pandemic that needs no introduction, is increasing is alarming to everyone who has access to any sort of print, online, or broadcast media.  New data of infection rates of COVID in Timeseria shows the infection rate increasing at exponential rates.  The question everyone has on their mind is how much longer will this go for, and when will infections finally begin to trend down?

The number of infections for the first 66 recorded days in Timeseria is seen below:
![](/covid%20count.jpeg)

After testing a couple of models, I decided on an autoregressive (AR) model to predict future infection rates for COVID.  An autoregressive model uses regression analysis on prior values at earlier times in the series.  The model also uses 2 degrees of differencing, which helps to normalize the average of the data and eliminate and kind of trend.  The model predicts infection count for the next ten days, that is, days 67-76 in Timeseria.  Looking at the plot below, we see that the AR model predicts that infection rates will start decreasing after ~ day 74.  A note: everything after the red line is a prediction.

![](/arima%20pred.jpeg)

Of course, the predictions from the model only depend on an algorithm and fail to take any kind of human behavior into consideration.  We can help to flatten this curve, which means making the infection count stay constant at about 30,000, or perhaps even make the count decrease sooner by staying home and social distancing. 
