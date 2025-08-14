# Twitter-Sentiment-analysis
                                  

This project looks at tweets, cleans them, and finds out if they are Positive, Negative, or Neutral.
It works like a mood checker for Twitter using Python, text processing, and some simple data cleaning.

What This Project Does

⦁	Reads tweets from a CSV file
⦁	Cleans the tweets:
⦁	Removes @mentions
⦁	Removes punctuation, numbers, and unwanted characters
⦁	Removes very short words that don’t add meaning

Processes the text:

⦁	Splits tweets into words (tokenization)
⦁	Changes words to their root form (stemming)

Shows the results:

⦁	Word clouds that display the most common words
⦁	A chart showing how many tweets are positive, negative, or neutral

Tools and Libraries Used

⦁	pandas and numpy — to handle and work with data
⦁	nltk — for text processing
⦁	matplotlib and seaborn — for making charts
⦁	wordcloud — to create word clouds
⦁	re — for cleaning text using patterns

Project Files

⦁	twitter-sentiment-analysis
⦁	tw_sentiment_analysis.ipynb – main notebook with all the code
⦁	Twitter Sentiments.csv – the dataset with tweets
⦁	README.md – project description
⦁	requirements.txt – list of needed Python libraries
