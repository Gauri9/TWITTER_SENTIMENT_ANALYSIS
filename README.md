# TWITTER_SENTIMENT_ANALYSIS
Classfying the tweets into positive , negative and neutral and printing top ten positive and negative comments respectively.


Twitter Sentiment Analysis

Problem Defination :
The problem in sentiment analysis is classifying the polarity of a given text at the document, sentence, or feature/aspect level. Where the expressed opinion is a document, or a sentence is positive or negative.
Objective :
•	To implement an algorithm for automatic classification of text into positive or negative.
•	Sentiment Analysis to determine the attitude of the mass is positiiive or negative towards the subject of interest.

Motivation :

•	An aspect of social media data such as Twitter messages is that it includes rich structures information about the individuals involved in the communication.
•	It can lead to more accurate tools for extracting semantic information.
•	It provides means for empirically studying properties of social interactions.

Proposed System :											

		Input(Keyword)-->Tweets Retrival-->Data Pre-processing-->Classification Algorithm
                                                                     |
                                                                     |
     Sentiments in Graphical Representation<--Classified Tweets<------ 
                 

Implementation Methods :
•	We have used TextBlob method and in-built classifier from NLTK :Naive Bayes.

1.TextBlob : TextBlob is a Python(2 and 3) library for processing textual data. It provides a simple API for dividing into common natural language processing(NLP) tasks such as part-of-speech tagging, noun phrase extraction, sentiment analysis, classification, translation, and more.

2.Naive Byes : Naive Byes is a simple model which works well on text categorization. 
System Requirements, Libraries and Language used :	
•	Python 3.0 or above
•	NLKT Package
•	Google Colab 
•	Twitter API

Applications : 

•	Applications to Review-Related Websites
	-  Movie Reviews, Product Reviews etc.
•	Application as a Sub=Component Technology
	-  Detecting antagonistic, heated language in mails, spam detection, context sensitive information detection etc.
•	Applications in Business and Government Intelligence
 	-  Knowing Consumer attitudes and trends.
•	Applications across Different Domains
	-  Knowing public opinions for political leaders or their notations about rules and regulations in place etc.

Conclusion :
	We conclude that using different NLTK classifier it is easy to classify the tweets and more we improve the training data set more we can get accurate results.

Future Work :
We look forward to use bigger dataset to improve the accuracy, considering the emoticons and internationalization.

