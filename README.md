# Twitter-Sentiment-Analysis
Sentiment Analysis is the process of computationally determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker. It is a direct application of Natural Language Processing (NLP), which is hot topic of research these days.  Thousands of text documents can be processed for sentiment in seconds, compared to the hours it would take a team of people to manually complete the same task.

# Process
The whole process of performing a sentiment analysis can be understood from the following workflow - 

[![8.jpg](https://i.postimg.cc/wv9hqNTR/8.jpg)](https://postimg.cc/rdYdgK4q)

It is easier to use Lexicon Based technique, which works on an assumption that the collective polarity of a document or sentence is the sum of polarities of the individual words or phrases. This includes getting a list of positive words and negative words from well known repositories, preparing and cleaning your data. Then for every tweet, compare the list of words in the tweet with the positive and negative lists and generate a sentiment score: -ve, 0, or +ve.

In this program, we can use Twitter sentiment analysis of tweets related to major airlines and then calculate a Twitter score for each. Then, we can get an airline score from the ACSI website, which gives the satisfaction index for these airlines. 

[![9.jpg](https://i.postimg.cc/SR6jtSML/9.jpg)](https://postimg.cc/JHh1sWKt)

Finally, we can plot both  the scores. 

[![10.jpg](https://i.postimg.cc/VsnSNRVS/10.jpg)](https://postimg.cc/mhZZXQRR)

