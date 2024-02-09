# Twitter-Sentiment-Analysis
 Analyzing the Sentiments of Tweets for Airlines on Twitter Platform

## Installation
```
$ git clone https://github.com/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines.git
$ cd Twitter-Sentiment-Analysis-for-Airlines
```

## Project Description: 
   - Topics Covered: 
		- Exploratory Data Analysis 
		- New Features from Text 
			- Word Count
			- Character Count
			- Average Word Length
			- Number of Stopwords
		- Stemming Technique
			- PorterStemmer
			- WordNetLemmatizer
		- TF-IDF (Term Frequency - Inverse Document Frequency)
		- Machine Learning Models 
			- Random Forest Classifier
			- Decision Tree Classifier
			- Linear Discriminant Analysis
			- Grid Search for Model Fine Tuning
      - **Project Code:** [Airline_Sentiment_Analysis](https://nbviewer.org/github/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines/blob/develop/Airline_Sentiment_Analysis.ipynb)
         - We updated our dataset to make it binary classification for better insights. Non-negative and Neutral Sentiments were clubbed together as Non-Negative. So, the two classes for classifications are - Negative and Non-Negative. 
         - Out of the 3 models mentioned above and considering the difference between train and test dataset performance parameters, LDA has performed the best.
         - In terms of sentiments, based on the organisation objective, either positive, negative or neutral metrics could be analysed to define the marketing strategy e.g. based on negative sentiments key words organisation can decide on what they should concertrate for improvement.
           
         - From below graph, we can understand the most important reasons for Negative sentiments for each of the SIX airlines.
           ![Reasons_for_Sentiments](https://github.com/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines/assets/74963600/158647ea-3575-4356-8e7a-d29cc99b4760)

	   ![Reasons_for_Sentiments2](https://github.com/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines/assets/74963600/d2e7ad74-d093-4b27-b36b-265270623e76)
