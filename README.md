# Analyzing-The-Effect-of-Social-Media-Activity-on-The-Performance-of-Cryptocurrencies

- Scraped 90000 tweets related to Bitcoin and Ethereum using the Snscrape module, further performed preprocessing operations on the Twitter data to tokenize and lemmatize the data using NLTK.
- Performed sentiment analysis on the preprocessed data using VADER, Harvard, and LM (Loughran and McDonald) dictionaries.
- Further, created time series for each cryptocurrency by aggregating the data by day using resampling.
- Analyzed both time series and used Vector Auto Regression (VAR) model to find whether a correlation between tweet sentiments and cryptocurrency prices and volume exists.
