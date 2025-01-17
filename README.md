# Sentiment_Analysis-Big-data-Project-
Sentiment Analysis of Covid-19 Tweets of Louisiana and Washington and Topic Modeling Using Apache Spark
Big Data Framework: Apache Spark

Libraries: pyspark, matplotlib, Mllib, seaborn, pandas, numpy,sql

exploratory_data_analysis.ipynb: contains the process of importing Data,
data characteristics, visualization, data exploration related coding

topic_modeling.ipynb: Applied LDA using MLlib library of apache apark 
for topic_modeling. It works on only Covid-19 related Tweets.(314534)

topic_modeling_all_tweets.ipynb: Applied LDA using MLlib library of apache apark  for topic_modeling upon all tweets. (2769978)
It includes all data of 48 hours before the announcement ( Stay-at-home order, mask_mandate) and 48 hours after the announcemnt.

Sentiment_analysis.ipynb: Sentiment based on gender and age related coding

Time_series.ipnyb: Contains sentiment over time (during stay-at-home order and mask-mandate order in LA and WA)

Main DB File: Under COVID19MisinformationPaper folder, themes_of_misinfo_project_tweets,
sqlite_db and the file in db format (tweets_db_2023-03-12_17-57-49.db)

Main csv file: Needed to covert the db file to 'tweets.csv' (related to Covid-19) file for further analysis.
All_tweets.csv: It includes all twitter data. 


