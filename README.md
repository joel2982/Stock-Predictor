# Stock-Predictor

Stock: https://finance.yahoo.com/quote/%5EBSESN?p=^BSESN&.tsrc=fin-srch

News Headlines: https://drive.google.com/drive/folders/1Kc5I6ksq5QoV_O_oaEaE96HPVjx5mcCo?usp=sharing

By combining sentimental analysis of news headlines with numerical analysis of past stock prices, a hybrid model for predicting stock price and performance is created. In this, I used sentiment analysis to predict whether a company's stock will rise or fall based on news headlines. Using Python and machine learning, this model will predict whether the price of a stock will rise or fall based on the sentiment of the day's most popular news item headlines.

## Data Cleaning
1. Checking and Removing the *NULL Values* in the Dataset.
2. Checking and Removing the *Duplicate Values* in the Dataset.

## EDA and Pre-processing
1. Renaming the columns and Removing unwanted columns
2. Changing type of 'Date' from object to datetime64[ns]

### Time series analysis is performed on the Stock data
1. Analysing the rolling mean and rolling standard deviation for the *Closing Price*
2. Perform the *Dickey Fuller Test* to check if the *Train Closing Price* is *Stationary*.
3. Create an *ARIMA Model* using 'train_log' and find predictions and analyse it with the 'test dataset'
4. 

### Sentiment analysis is performed on the News data.
1. Remove special characters from the text.
2. Group  all the 'News' together having the same 'Date'
3. Find the Subjectivity and Polarity of a particular day by assessing the News
4. Find Sentiment Scores like Compound Score, Negative Score, Positive Score and Neutral Score of each day's News.

## An analysis is performed by merging both the data to predict if the Close price of the stock will increase or decrease.


