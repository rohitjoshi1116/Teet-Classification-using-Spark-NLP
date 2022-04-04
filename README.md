# Text-Classification-using-Spark-NLP
#**Customer churn classification using Verizon Tweets**

Problem Statement:
Telecom network often encounters large number of tweets based on the user experience for a network. This huge amount of raw data can be used for industrial or business purpose by organizing according to our requirement and processing.

Objective:
This project aims to address the social media review challenges for the telecom companies by extracting the tweets, analyzing them and segregating them into various categories to help the company understand the concerns of their customers and thereby, save millions and prevent customer churn.

Approach:
1. Examining Large amount of Verizon page tweets extracted from Twitter for a period of 4 days using various hashtag of #Verizon
2. Classifying the tweets into different labels based on the user experience for the network.
3. Analyzing the tweets based on categories and gaining insights from the data.
4. Performing visualization to better analyze the user experience.
5. Developing Model using PySpark Mllib to classify the tweets automatically.

Tweets Classification Categories:
- Poor Service
- Happy Customer
- Churn/Lost Customer
- Potential New Customer
- Higher Product price

Implementation:
- Scraped the tweets using Twitter API.
- Natural Language processing was used to extract features from the tweets.
- Random Forest from Pyspark Mllib was used to classify the tweets.
For Detailed implementation refer the IPython notebook

Recommendations and Insights:
1. From our analysis we can say that Verizon must focus on their service (which includes customer service and Network issues). By focusing on these issues they can improve their customer satisfaction and avoid churn (which is also visible in the plots)
2. Use Real time tweets to analyze the problem with the Verizon network and can give a quick solution to the problem to avoid network traffic and give a quality service to the customer. 
3. Location based data can be used to offer good deals to customers and design campaigns to combat churn.
