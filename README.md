# News-Aggregator

In this project I extracted news about differnt topics such as India, Sports, Business from 'Times Of India' newspaper, which is widely read by Indian people. Webpage link for the same - https://timesofindia.indiatimes.com/ and made topic classification and sentiment analysis of this news. For topic classification I trained classifier to predict topic of differnt news. For sentiment analysis I just used already pre-trained model to classify news on positive and negative and neutral ones. 

Complete Data science Lifecycle is followed for this project

## News data Collection :  

In this step, Data is collected by web scraping of news articles with the help of selenium from the TimesOfIndia News and . The data such as  "Category", "Title", "Published Date", "Author", "Content" is scraped from the website and stored into a CSV file.
The is extracted from different categories such as 'India', 'World', 'Business', 'Sports', 'Entertainment'.

## Web Scraping the Times of India news using selenium and newspaper3k library
Used selenium and newpaper3k library to scrape the data

## Data Cleaning

I have extracted the place names from the beginning of the content, cleaned text by removing special characters and whitespace, handled missing values, removed duplicates, and normalized text by converting it to lowercase. 

## Sentiment Analysis and Distribution
Sentiment analysis was performed to classify news articles into positive, negative, and neutral categories. A pre-trained sentiment analysis model was used for this task, and the results were analyzed for distribution across different categories.

## Word cloud
A word cloud was generated to visualize the most common words in the dataset. This provided insights into the dominant terms used across news categories.  

Choosing the ML Algorithm
Several machine learning algorithms were tested, I used SVM depending on the various metrics.
Prediction
The final model was used to predict the topics of unseen news articles and analyze their sentiments. Predictions were evaluated to ensure the accuracy and reliability of the system.

