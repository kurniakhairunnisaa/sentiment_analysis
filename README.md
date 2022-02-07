# Sentiment Analysis on News Headlines
This program will predict sentiment analysis from news headlines on given dataset and classify it as positive, negative, or neutral. 
## Requirements 
There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.
-	pandas
-	numpy
-	seaborn
-	matplotlib
-	sklearn

The library requirements specific to some methods are:
-	simpletransformers for pre-trained NLP
-	torch for building models using bert

To install the libraries: 
```bash
pip install simpletransformers
pip install torch
```
Note: It is recommended to use Jupyter Notebook

The code was run on Python ver 3.9.7
## How to run the code
1. Put the file financial_news_data.csv, data_for_test_the_model.csv in the "data" folder
2. Assignment result documents are stored in "Assignment Results" folder

After the above steps, you should have 1 file "test prediction.csv" containing the prediction model of the test data.
## Files information
- The financial_news_data.csv used as a train data. It contains the sentiments for financial news headlines. 
- The data_for_test_the_model.csv used as a test data. It contains the news headlines to be predicted.
