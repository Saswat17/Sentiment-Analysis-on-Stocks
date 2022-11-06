# Right Stock Selection
Predict which stock is right to buy

## Project description 

The aim of the project is to predict the right stock to buy using "Sentiment Analysis".

## Project Breakdown

1. Collect data by data scraping using Selenium and BeautifulSoup.
2. Pre-process the data like tokenization and lemmatization and then classify using Latent Dirichlet Allocation.
3. Doing Sentiment analysis using the past data form yahoo finance and the data that is scrapped.
4. We use Bert to make the model to imporve the model accuracy.



## Order of Execution of Files

1. Stock_article_data_collection.ipynb
### Output files :- azn_urls_20220105.txt , Sentiment Updated.csv
Use azn_urls_20220105.txt in 2nd Script.

2. TextPreprocessing_and_Classification.ipynb
Use Sentiment Updated.csv in 3rd Script.

3. Sentiment_Analysis.ipynb
Use azn_prices_labels_news_updated.csv in 4th Script

4. Long_Text_Classification_using_BERT_and_PyTorch.ipynb



## Data sources

* [Yahoo! Finance](https://uk.finance.yahoo.com/) for historical stock data.
* [Investing.com ](https://uk.investing.com/) for market news articles.
