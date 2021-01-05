# Covid Tweet Analysis
A full-scale working end-to-end ready for use by Twitter, which makes use if  NLP techniques to analyze the  COVID-19 tweets, and understand results in terms of meaningful insights from those tweets. These include but are not limited to sentiments of tweets, the demographics of tweets, the major topics which the tweets can be classified into, and a network analysis on mentions and retweets. This can  be implemented by Twitter, and  updated in real-time for live dashboards.

## Background
The rapid number of COVID-19 cases globally has triggered a wave of apprehension among people. This unprecedented condition, naturally, makes topics around COVID-19 a conversation trending around the world. 

## Objective 
Understand how covid tweets relate to covid cases by evaluating entities and topics involved through sentiment and network analysis; enabling users and to see correlation between certain topics and covid cases.

## Data Source
* Coronavirus (COVID-19) Tweets Dataset (IEEE) & COVID19 Tweets with the hashtag #covid19 (Kaggle)
* Extracted from the above for a period of around 36 days in total, spanning from 24th July 2020 to 30th August 2020. The data contains 179k rows spread over 13 different tweet related variables. These  179k rows are those which have a #covid19 (hashtag of covid19).

## Design Choices
1) **Entity Recognition** - 
Information extraction that seeks to locate and classify named entities mentioned in text into predefined categories such as person names, organizations, locations etc. *(Packages: spaCy)*
2) **Topic Modeling** - 
Identify popular topics from tweets. *(Packages: nltk, pyLDAvis, .sklearn, LatentDirichletAllocation)*
3) **Sentiment Analysis** - 
Process the text data for sentiment packages & investigate the relationship with sentiment scores and daily cases. *(Packages: nltk,  spaCy, vaderSentiment, TextBlob, Lexicon)*
4) **Network Analysis** - 
Identify users who are highly connected by examining centrality and node degree & find users that can spread information to many other users. *(Packages: iGraph, NetworkX, or Scikit-network)*


