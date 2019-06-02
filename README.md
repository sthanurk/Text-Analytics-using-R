# Text Analytics for National Institutes of Health

### _Word Clouds, Sentiment Analysis and Topic Modeling on Counseling data_

Text Analytics on problems (grievance) and answers(support) of online forum for mental health - https://forums.psychcentral.com

__Libraries used:__ dplyr, tidytext, ggplot2, SnowballC, wordcloud, reshape2, RTextTools, tm, wordcloud, topicmodels, slam, ldatuning

__Work done:__
* Stemming - stripping affixes such as 'ed', 'ing', 'tion' etc. Ex. stemming 'walked' returns walk.
* Lemmatization - a more intelligent way of cleaning text data where words are converted to its root words using a dictionary. Ex. lemmatizing 'is' returns 'be'.
* Word Tokenization
* Top words in the questions and answers before removing stop words
* Top words in the questions and answers after removing stop words
* World cloud of the words in the questions and answers
* Sentiment Analysis - Identifying the positive and negative words
* Topic Modeling
Arriving at the best number of topics is determined by the metrics obtained from the principles of : 
	* Griffiths2004
	* CaoJuan2009
	* Arun2010
	* Deveaud2014
	
Number of topics identified in questions = 4
Number of topics identified in answers = 9

From the topics identified from q_contents, which talks about people expressing their mental difficulties, it is found that anxiety, depression, work related problems, school related problems (maybe bullying from friends), relationship problems, less support from parents, family problems etc. can be the top reasons for mental disorder in the society.