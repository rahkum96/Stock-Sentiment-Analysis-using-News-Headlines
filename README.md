# Stock-Sentiment-Analysis-using-News-Headlines

### About 
1. The data set in consideration is a combination of the world news and stock price shifts.
2. Data ranges from 2008 to 2016 and the data from 2000 to 2008 was scrapped from Yahoo finance.
3. There are 25 columns of top news headlines for each day in the data frame.
4. Used TF-IDF for extracting featues from the headlines. Used machine learning model Random Forest Classifier to predict the model.
 
 Class 1 – The stock price increased.
   
 Class 0 – The stock price stayed the same or decreased

### Approach:
- First import required libraries.
- Read the dataset
- Does some feature engineering on our dataset
- Applied CountVectorizer and RandomForestClassifier
- Predict for the testing dataset
- Finally, checked the accuracy 


### Models with their Accuracy of Prediction
- We got an accuracy of 84% by using NLP(TD-IDF vectorizer) and machine learning model Random Forest


           precision    recall  f1-score   support

           0       0.92      0.73      0.81       186
           1       0.78      0.94      0.85       192


### NOTE
==> Python version 3.6.8 was used for the  project.

==> You can find all the models https://github.com/rahkum96/Stock-Sentiment-Analysis-using-News-Headlines/blob/main/Stock_Sentiments_analysis.ipynb


### Dataset link:
https://www.kaggle.com/rohit0906/stock-sentiment-analysis-using-news-headlines
