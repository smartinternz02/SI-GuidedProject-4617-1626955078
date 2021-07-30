# SI-GuidedProject-4617-1626955078
Project Title: 
   Sentiment Analysis of Customer feedback on Restaurant using NLP

Project ID:  SI-GuidedProject-4617-1626955078
Team Name: Chiran


Done by,
V.CHIRANJEEVI, 19BCE2166

G.PUSHWANTH, 19BCI0015

S. Sai Nikhil, 19BCI0010

Aadil Mohammed, 19BCI7052









Contents:
S.NO	Title	Page. No
1.	Introduction:
1.1 Introduction to the Problem/ Overview
1.2 Solution / Purpose	3
2.	Literature Survey	4
3.	Experimental Analysis	5
4.	Flowchart	6
5.	Conclusion	7
6.	Future Scope	8
7.	Bibliography	9


Introduction:

1.1 Overview:
	The most impactful marketing strategies of the recent times is by propagating general user consensus and feedback to new users to lure them into the product. This feedback is often is in terms of a product review which sums up the experience of the user. To give a review we usually use text to explain something that we experience with an item, place, or event that we normally experience.
	Sentiment analysis, is that field of study people's opinions, sentiments, evaluations, judgments, attitudes, and emotions towards entities such as products, services, tourism, movies, organizations, political issues, individuals, problems, events, topics, etc. It is a type of data mining that measures the inclination of people's opinions through natural language processing (NLP), computational linguistics and text analysis, which are used to extract and analyse subjective information from the Web, mostly social media and similar sources. 
1.2 Purpose
	Performing such analysis helps the organisations to maximize the customer satisfaction, which in turn increase the mass appeal of the product in e-commerce/ e-sites. Customer satisfaction is the opinion between expectation and reality obtained by consumers. Giving a review is also a useful activity so that other customer on the internet can find out something else and see opinions about things and its satisfaction.
	Commonly, most people express their opinion through social media like Facebook and Twitter or review platform like Zomato, Google My Business, Yelp, etc. Customer reviews on online media like Zomato become important as it might increase the popularity of something. Zomato is a site where someone can give a review of a restaurant, how the restaurant is and someone's opinion about the restaurant. Review on Zomato is still in the form of text and can be classified with positive, negative, or neutral with their ratings. Zomato doesn’t have an analysis of how users interact with the reviews and what words will indicate they like or not it. We need to extract the words in review and analysis it so we can know how users interact in Zomato and get customers satisfaction by their review.

2. Literature Survey:

2.1 Existing problem:
	One of the fundamental problem in performing Sentiment analysis is categorization of sentiment polarity. Given a piece of written text, the problem is to categorize the text into one specific sentiment polarity, positive or negative. In this application the reviews are categorized as Positive, Average, Negative.
	
2.2 Proposed Solution:
	 Sentiment categorization is essentially a classification problem, where features that contain opinions or sentiment information should be identified before the classification. Every word of a sentence has its syntactic role that defines how the word is used. The syntactic roles are also known as the parts of speech. 
	There are 8 parts of speech in English: the verb, the noun, the pronoun, the adjective, the adverb, the preposition, the conjunction, and the interjection. In natural language processing, part-of-speech (POS) taggers have been developed to classify words based on their parts of speech. For sentiment analysis, a POS tagger is very useful because of the following two reasons: 
1) Words like nouns and pronouns usually do not contain any sentiment. It is able to filter out such words with the help of a POS tagger.
 2) A POS tagger can also be used to distinguish words that can be used in different parts of speech.

3. Experimental Investigations:

While working on the project, we got an in-hand experience of the basic of Model building:
•	Handling huge datasets and stem them accordingly for root words to analyse.
•	Initially for the collected data it trained for few epochs with only one hidden layer. Then while adding more hidden layers through which the model processed huge data set in less time we need to use more hidden layers and we also increased epochs.
•	Due to increase in hidden layers and epochs our model accuracy is high.





4. Flow Chart:
5. Conclusion:
	After training the model for 100 epochs and accuracy of 95% was achieved and thus Sentiment analysis of customer reviews for Zomato using the concept of Natural Language Processing model implemented successfully and the model was ready for the local deployment using FLASK libraries, which is shown below as follows:



Thus, a user-friendly website has been developed in order to get the customer reviews of Zomato and predict them as good, average or bad.

6. Future Scope:

•	Customer Churn predictions,
•	Tone Detectors,
•	Similar implementation of the model for different platforms, which record user feedback.




7. Bibliography:


•	https://www.analyticsvidhya.com/blog/2020/11/create-a-pipeline-to-perform-sentiment-analysis-using-nlp/
•	https://www.analyticsvidhya.com/blog/2021/06/nlp-sentiment-analysis/
•	https://towardsdatascience.com/real-time-sentiment-analysis-on-social-media-with-open-source-tools-f864ca239afe
•	https://ieeexplore.ieee.org/abstract/document/7219856/
