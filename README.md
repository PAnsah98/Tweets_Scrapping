# Tweets Sentiments Analysis

The purpose of this project is to demonstrate data scrapping and sentiments analysis using Twitter's API and python.

# Key Takeaways
* Using tweepy to access the Twitter API.

* Using pandas to be able to put the data scrapped into a dataframe.

* A function was created using regex expression's re.sub, to substitute whatever pattern we find in the tweet with an empty string. sub() function is used to replace occurrences of a particular sub-string with another sub-string. 


* TextBlob was used to get the subjectivity and polarity of the tweets.
Polarity simply tells the sentiments of the tweets; which tweets are negative, positive or neutral whereas subjectivity tells how subjective or opinionated the tweets are.

* How well are the Sentiments distributed?
To know more about the sentiments, you would have to create a wordcloud.
A wordcloud is a visualization where the more specific words appears in the text, the bigger and bolder it appears in the wordcloud.

* Finally, the sentiments of the data was visualized using matplotlib.pyplot's imshow function.

# Installation
* Clone this repository
* Install python jupyter notebook or any IDE of your choice
* Install
1. tweepy, 
2. re, 
3. pandas, 
4. matplotlib, 
5. textblob
6. wordcloud.
 
