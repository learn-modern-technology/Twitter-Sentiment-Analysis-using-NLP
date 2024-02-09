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
         - Dataset was simplified and updated to make it binary classification. Non-negative and Neutral Sentiments were clubbed together as Non-Negative. So, the two classes for classifications are - Negative and Non-Negative. 
         - Out of the 3 models mentioned above and considering the difference between train and test dataset performance parameters, LDA has performed the best.
         - In terms of sentiments, based on the organisation objective, either positive, negative or neutral metrics could be analysed to define the marketing strategy e.g. based on negative sentiments key words organisation can decide on what they should concertrate for improvement.
           
         - From below graph, we can understand the most important reasons for Negative sentiments for each of the SIX airlines.
		 
		 
           ![Reasons_for_Sentiments](https://github.com/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines/blob/develop/images/Reasons_for_Sentiments.png)
        - Customer Service Issue is the most important Reasons for Negative Sentiments for 5 Airlines ((United, US Airways, American, Southwest and Virgin America)
		   
			![Reasons_for_Sentiments2](https://github.com/sudhanshusinghaiml/Twitter-Sentiment-Analysis-for-Airlines/blob/develop/images/Reasons_for_Sentiments2.png)
			
		- Late flight is the most important Reasons for Negative Sentiments for Delta Airlines 
