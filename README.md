# Databricks-Spark-Streaming
This repo is to test a streaming application on Databricks that performs sentiment analysis on live tweets.

![image](https://user-images.githubusercontent.com/31921089/226050194-cd64b195-60ac-4149-8b04-f20c9fc766eb.png)

## Files Description
* tweetread: Receive Twitter data and write to a directory
* tweet-nb: Pipeline for data processing and model training
* tweet-scoring: Assign sentiment score (positive/negative) to streaming tweets
