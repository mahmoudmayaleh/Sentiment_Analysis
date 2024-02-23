# Sentiment Analysis on Social Media Comments

Overview:
This Python project conducts sentiment analysis on social media comments using the NLTK library. The analysis involves detecting sentiment in textual data extracted from a social media dataset (Twitter_Data.csv). The project utilizes the SentimentIntensityAnalyzer, part of the NLTK library, to generate sentiment scores for each comment.

![proj-sentiment](https://github.com/mahmoudmayaleh/Sentiment_Analysis/assets/124529384/d00209b6-322d-4b03-a860-aa1bd71582b8)

# Key Steps:
Data Encoding Detection:

Automatically detects the encoding of the provided CSV file ('Twitter_Data.csv') using the chardet library.
Loading Data:

Loads the social media data with the detected encoding, preparing it for sentiment analysis.
Text Preprocessing:

Defines a preprocessing function to clean and prepare textual data for sentiment analysis.
Applies the preprocessing function to the 'comments' column, creating a new 'processed_comments' column.
Sentiment Analysis:

Utilizes the SentimentIntensityAnalyzer to calculate sentiment scores for each processed comment.
Presents a histogram visualization of sentiment scores for a comprehensive overview.
Average Sentiment Calculation:

Computes the average sentiment score of all social media comments.
Prints and provides insights into the overall sentiment of the dataset.
# Dependencies:
Python
pandas
nltk (Natural Language Toolkit)
matplotlib
seaborn
chardet
# How to Use:
Ensure you have the necessary dependencies installed.
Run the provided Python script to execute the sentiment analysis on the 'Twitter_Data.csv' dataset.
Explore the generated histogram to understand the distribution of sentiment scores.
Review the calculated average sentiment score for a summary of the overall sentiment.
Note:
The project provides a valuable tool for analyzing sentiments in social media comments, offering insights into the emotional tone of the dataset.
Feel free to customize and extend the code to suit your specific requirements or integrate it into your data analysis pipeline.
