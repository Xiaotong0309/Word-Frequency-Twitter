# Word-Frequency-Twitter
count word frequency for a specified user's twitter content and webpage content mentioned in tweets

## Environment
python 2.7

## Dependency
To install nltk, uncomment these code in tweet_dump.ipynb
```
import nltk
nltk.download()
```
Add twitter developer certificate to twitter.conf
You can configure number of words in results by:
```
words_num = 30 # number of words to show in frequency figure
word_num_csv = 200 #number of words to save in frequency csv file
```
## How to Run
Open tweet_dump.ipynb with jupyter notebook and run
In the main function, you can add the twitter screen name that you want to analyze by:
```
get_good_language("Lemonade_Inc")
```




