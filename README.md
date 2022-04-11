# Twitter_NLP_Project_Bridgerton

I have decided to mine tweet about Netflix's Bridgerton TV Series since it's on the TOP 10 again with its second season.


<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/bridgerton.jpg" width="800" height="500" />

I mined almost 100K tweets. I will try two different approaches. I will use half of the tweets on the first approach and half of them on the second approach.

# First Notebook: Bridgerton_Tweet_Analysis.ipynb

## On the first approach:

Used: Python libraries 
* Pandas (for Data Cleaning/Manipulation)
* Tweepy (for Tweets Mining)
* NLTK (Natural Language Toolkit) 
* TextBlob (for Sentiment Analysis) 
* MatPlotlib & Seaborn & WordCloud (for Data Visualization)
* Emot (for Emojis identification)
* Plotly (for some Data Visualization)

Most popular hashtags:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/hashtags.JPG" width="500" height="300" />

Most popular characters:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/movie_characters.JPG" width="500" height="300" />

Most Common Words on the tweets:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/wordcloud.png" width="700" height="500" />

Sentiment Analysis:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/Sentiment_pie.JPG" width="500" height="300" />

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/sentiment_table.JPG" width="400" height="200" />

## On the second approach:

Used: Python libraries 
* Pandas (for Data Cleaning/Manipulation)
* Tweepy (for Tweets Mining)
* NLTK (Natural Language Toolkit) 
* TextBlob (for Sentiment Analysis) 
* MatPlotlib & Seaborn & WordCloud (for Data Visualization)

Preprocessing:
* Remove Punctuation
* Remove Numbers
* Tokenization
* Remove Stopwords
* Stemming


# Second Notebook: Bridgerton_Tweet_NLP_Classification.ipynb

- Sentiment Analysis
- Wordcloud
Most Popular words for all tweets:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/wc.png" width="700" height="500" />

Most Popular Words for negative tweets (According to my sentiment analysis)
<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/wc_negative.png" width="700" height="500" />

Most Popular Words for positive tweets (According to my sentiment analysis)
<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/wc_positive.png" width="700" height="500" />

## NLP Supervised Learning
Methods:
* CountVectorizer
* Ngram
* Logistic Regression
* Naive Bayes
* KNN
* TF-IDF

Results:

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/Results.JPG" width="600" height="500" />

Final Model: (DecisionTreeClassifier)

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/final.JPG" width="500" height="400" />

It is not great but I had to downsize my data to 10K tweet. Because my RAM is not enough for CountVectorizer..

<img src="https://github.com/nuriyeakin/Twitter_NLP_Project_Bridgerton/blob/main/images/final1.JPG" width="200" height="100" />

