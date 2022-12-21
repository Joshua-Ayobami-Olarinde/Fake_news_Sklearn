# Hamoye_Premier_Kmeans

##CONTENT
Abstract
Introduction
Aim and Objective
Methodology
Data Processing
EDA
Modelling
Challenges
Conclusion & Recommendation
Summary
Workflow Summary
Future Improvement


#Abstract
With the increasing popularity and ease of access to information available on various internet and social media platforms, it has become a key source of news today. Although it is appropriate for an increasing number of Smartphone users, the simplicity of publication and lack of accurate editorials have caused us to question the credibility of such sources. 
* data sets generation is important in this study. 
* the data is categorized into two major categories using binary classification: genuine and false dataset. 
* In this study, we deploy a Machine Learning model on news stories and thereby verify their legitimacy.

**Key words: fake news, preprocessing, classifier algorithms, feature extraction, Machine learning Algorithms e.t.c																	4

#Introduction
Fake news has increased recently in relation to a number of important topics, such as the CoVid-19 pandemic, political events, or utterances, which could ultimately cause widespread unrest and even riots.
With the new age of social media, it has become increasingly challenging to identify and differentiate between authentic and fake news that abound all over the space. This is complicated by the volume, and variety characteristics of news that makes it difficult to detect fake news.

The term fake news means “news articles that are intentionally and verifiably false” designed to manipulate people's perceptions of real facts, events, and statements. News is a part of our daily lives, and therefore it is pertinent to be able to detect inauthentic news amidst the mountain of news we consume daily.																	   	 	        5

#Aim and Objective

Leveraging on computational tools and the power of machine learning, we hope to present methods that can be used to clearly detect fake news, and compare the performance of the models.

The main objective of this project is to build machine learning models capable of predicting whether some news is fake or not, based on text with an accuracy of 95%
																																																

#Other content can be found in the notebook

#Eda conclusion and summary
The data is about the US Politics and revolved around the past president Donald Trump.
From the Unigram Analysis, we could see that the top fake word used was ‘said’ whereas in the true news it didn’t appear in the top 20 words. This is most likely due to false news misquoting people or taking what the speaker said out of context.
Also, looking at the bigram of fake news, we can see that Donald trump was mostly referred to as ‘mr trump’ and same could be seen with ‘mrs Clinton’ and ‘mr Obama’. This is most likely a means of disrespect or sarcasm to the discussion.
The New York Times published more fake news than true news.                 	     14      

#Summary
The dataset for this study contained news on US politics around the time of Donald Trump been President.
Different Classifications models were used to predict a fake/true news and the SVM model gave the highest accuracy of 96%.
A neural network was further used and it gave a better accuracy.
The Model was deployed to a local flask app to help predict if a news is fake/ true.


