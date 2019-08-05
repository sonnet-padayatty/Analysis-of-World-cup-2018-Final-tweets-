# Analysis-of-World-cup-2018-Final-tweets-
Random 5000 tweets were imported from twitter after the World Cup Final match and created a "Word Cloud" using python packages. In the Word cloud, Most occuerent words from the tweets are shown in large fonts. In this way we can easily figure out the influential players of the match. As per the generated word cloud, it is found that Mbappe is the player name which has occured mostly.

# Python libraries
SentimentIntensityAnalyzer, NaiveBayesAnalyzer, stopwords, WordCloud, textmining, matplotlib.pyplot

# Sentiment Analysis
By checking the polarity of each tweets, we can classify all tweets into 3 categories as below:
1. Happy
2. Sad 
3. Neutral

Polarity Ranges between -1 and 1.
Polarity of the status Happy is between >0.5 and < 1
Polarity of the status Sad is between <-0.5 and > -1
Polarity of the status Neutral is between >-0.5 and < 0.5

# Conclusions
From the analysis, following conclusions are made
1. 55.94 % of people are happy with the final results of WC.
2. 6.42 % of people are not happy with the final results of WC, who are really critic.
3. 37.64 % of people are considered as neutral.
4. Mbappe is the most influential player in the Wc final.
