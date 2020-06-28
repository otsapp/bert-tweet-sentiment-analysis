# DistilBert sentiment analysis of tweets
Sentiment analysis of tweets using pre-trained DistilBert and SVM

- This project is just a quick first look at Bert as a tool.
- Credit to `https://github.com/jalammar/jalammar.github.io/blob/master/notebooks/bert/A_Visual_Notebook_to_Using_BERT_for_the_First_Time.ipynb` for th intro.

# Data

`http://help.sentiment140.com/for-students/`

1600000 tweets
The data is a CSV with emoticons removed. Data file format has 6 fields:
0 - the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
1 - the id of the tweet (2087)
2 - the date of the tweet (Sat May 16 23:58:44 UTC 2009)
3 - the query (lyx). If there is no query, then this value is NO_QUERY.
4 - the user that tweeted (robotickilldozr)
5 - the text of the tweet (Lyx is cool)


# Metrics

~.76 f1-score with minimal svm tuning.
