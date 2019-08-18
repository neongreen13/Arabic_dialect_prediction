# Arabic Dialect Prediction
Two companion notebooks that classify Arabic dialects.

The first classifies Arabic as either Egyptian or Modern Standard Arabic, based on a dataset from Wikipedia articles hosted on Kaggle. The notebook goes into exploratory data analysis on the text, identifying unigrams, bigrams, some stemming, and rare words. Next, it compares several machine learning classifiers to identify the dialects and evaluates their accuracy. Finally, the notebook deploys the model on new text compiled in Arabic Tweets.

The second notebook classifies text based on a collection of 102,000 Arabic tweets, 17,000 each from Cairo-Egypt, Riyadh-Saudi Arabia, Amman-Jordan, Casablanca-Morocco, Baghdad-Iraq, and Modern Standard Arabic news outlets. The notebook cleans the tweets and applies the same group of classifiers from the previous notebook on the data.
