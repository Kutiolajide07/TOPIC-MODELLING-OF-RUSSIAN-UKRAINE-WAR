Topic Modelling of data scraped from Twitter
Sentiment Analysis of the Russia-Ukraine War
The required data was scraped on Twitter using the TWINT i.e twitter intelligence tools. This helped in scraping the tweets without an API.
The tweets scraped in 3 pre-dominant languages (i.e. English, Russian and Ukrainian) using different hashtags
The data that was scraped from the web was noisy and unstructured, necessitating the need to clean and arrange it for sentiment analysis and topic modeling at different points throughout the project.
The tweet data were scrapped at 3 different times at different intervals to ensure enough tweet data was captured. At this point, over 1.5m tweets were scraped in the 3 languages before selecting a unique number of tweets of around 23,000 for each language.
For the sentiment analysis, the rule-based approach using Vader was adopted which is an ML model used for training data
Polarity, classification, and subjectivity of the Twitter data are to be evaluated in 3 languages
For the topic model part, LDA from SKlearn will be conducted on the tweet data to find the optimal number of topics.
LDA will also be used to get the most coherent topic or latent topic from the dataset of each selected language.
