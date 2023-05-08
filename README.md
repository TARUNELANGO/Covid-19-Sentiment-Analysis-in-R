# Covid-19-Sentiment-Analysis-in-R
A classification model to predict the sentiment of Covid-19 tweets. The tweets have been pulled from Twitter and manual tagging has been done. Information like Location, Tweet At, Original Tweet, and Sentiment are given.

## Objective:
To obtain insights from textual data focused on COVID-19. The code involves a sentiment and network analysis of data specific to COVID-19 using R. 
Since there is no specific dataset for this part, I use data from multiple sources including Bing, COVID19 Daily Updates, etc. 
To visualize the primary emotions in the data (trust, fear, anticipation, etc.). 
To have as many visualizations as possible in order to understand the data better. 
Social Network analysis would help visualize the pattern between most frequent set of words with the help of graphs and networks

## Methodology:
An analytical approach to apply multiple visualizations like bar chart, wordclouds, etc. depicting various patterns and hidden information behind the data. 
This also helps to analyse primary emotions within the tweets and identify trends between various attributes spread across the datasets. 
Wordclouds also help to analyse positive and negative words in the tweets further strengthing our analysis. 
This is a lexicon based approach, hence, it relies on manually defining stop words, etc used to clean the dataset to remove ambiguity at multiple instances. 
Also the fundamental concept of tokenization of text into unigrams, bigrams or trigrams would make handling and analysis easier and efficient.

## Algorithms Used:
-> Rule/Lexicon based approach
-> Keyword Stopping

-> Rule/Lexicon based Approach:  This method uses manually created data classification rules to ascertain sentiment. 
This method determines a score by using dictionaries of words with positive or negative values to indicate their polarity and sentiment strength. 
Expressions can also be used to create more functionality. By creating even better rules, rule-based sentiment analysis algorithms can be modified according to context.
How it works? It counts the amount of words in the given text that are both positive and negative. 
It will return a positive sentiment if there are more positives than negatives. It will give a neutral response if both are equal. 

-> Keyword Stopping: Keyword spotting is one of the simplest and most straightforward techniques and widely used by Sentiment Analysis algorithms. 
The input text is thoroughly scanned for the prominent positive and negative words like “sad”, “happy”, “disappoint”, “great”, “satisfied”, and such.
Keyword spotting system detection performance degrades when substitution errors occur during the keyword recognition. 
Therefore, a keyword recovery algorithm was developed to reduce the detection degradation to a low false alarm rate to recover keywords after rejecting acoustic noise. 
Tests show that the detection performance improves from 78.1% to 85.3% for a false alarm rate of 10% with the upper range of the detection performance improved from 85.0% to 92.0%. 
Thus, the system performance is enhanced by the keyword recovery algorithm for both the average and maximum detection performance.

1. Read and explore data in order to find any anomalies 
2. Prepare data for the forthcoming task- this step would involve data manipulation and cleaning
3. Clean the textual data- remove punctuations, extra white space, stopwords, etc.
4. Create N-grams from textual data to enable easier processing.
5. Use lexicon to predict the sentiments of words through semantic orientation.
6. Analyse primary emotions in the data and create word clouds to predict the sentiment.
7. Perform social network analysis to visualize the connection between the most frequent combination of words with the help of graphs and networks.
8. Draw conclusions from obtained results 

## Parameters:
Confirm: Number of confirmed covid cases
Recovered: Number of recovered cases
Death: Number of deaths
User Location: The location of the user when the tweet was posted
Text: The actual tweet posted by the user
Date: Date when tweet was posted
User followers: Number of followers of the user who posted the tweet
User favorites: Number of favorites user had at the time of posting
User friends: Number of friends user had at the time of posting

