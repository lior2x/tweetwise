# Tweetwise #

Tweetwise is my attempt to create an automated system for Bitcoin trading, implementing the techniques described in Colianni et al. to build a predictive model based on Twitter sentiment analysis [1].


## Twitter + Bitcoin data ##
I spent ~4 months collecting data, based on the methods described in the paper. You can download the data [here](https://drive.google.com/open?id=0BzqCBdvJ6j-nUzRZckRJUVJwY00).

To help you save time, I have included the processed tweet data, which is formatted according to the methods described in the paper (stop words, duplicate tweets, non-english words, etc).

(*Update September 19th, 2017*)
I took the liberty of creating features.csv, which includes sentiment values derived from NLTK. Each line in features.csv represents one hour of twitter data. Each hour includes the average sentiment, the corresponding Bitcoin volume, and the Bitcoin price change from the previous hour.


## References ##
[1] Colianni, Rosales, Signorotti. *Algorithmic Trading of Cryptocurrency Based on Twitter Sentiment Analysis* http://cs229.stanford.edu/proj2015/029_report.pdf. Web. 20 September 2016.
