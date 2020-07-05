# Twitter-Sentiment-Analysis-using-Python

The aim is to extract the tweets and perform analysis on it.
The code should do the following:
1. Capture all streaming tweets that contain one or more specified keywords.
2. While capturing tweets, all retweets should be ignored.
3. Clean streaming tweets.
4. Save tweets and some of their properties into a csv file.
5. Perform data analysis on saved clean tweets.

## Cleaning and Preprocessing:
Code will clean tweets and prepare them for data analysis. 
The cleaning code should do the following:
(1) delete mentions and links; 
(2) make everything lowercase; 
(3) remove numbers;
(4) remove stopwords; 
(5) remove elongated words; 
(6) stemming; 
(7) remove punctuation, special characters, emoticons/emojis

## Save Tweets into a CSV
The code would save the streaming tweets and some of their properties into a csv file. CSV file should contain columns for the following: (i) number of streaming tweet saved; (ii) raw tweet text; (iii) user name; (iv) number of tweets the account has posted; (v) how many times the saved tweet has been favored; (vi) how many times the tweet has been retweeted; (vii) time the tweet was posted; (viii) clean text of tweet; and (ix) sentiment polarity using TextBlob (positive, negative, or neutral)

## Data analysis
This code will use as input the clean data and it will perform data analysis.It would do the following:
(1)to tell which are the most frequently occurring terms in the entire body of tweets, 
(2)the most frequent n-grams (cooccurrences of words),
(3)finally using word embedding, will find what words are most similar to some specified words.
