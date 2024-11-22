Amazon Product Reviews Sentiment Analysis

<br/>Overview: 
<br/>This project performs sentiment analysis on Amazon product reviews to classify them into Positive, Negative, or Neutral categories. It uses VADER (Valence Aware Dictionary and sEntiment Reasoner), a lexicon and rule-based sentiment analysis tool in Python, to assess customer sentiment based on review content. The project includes data preprocessing, sentiment scoring, and visualization to interpret and display the results effectively.

Features: 
<br/>Data Cleaning: Handles missing data and pre-processes review text by removing non-alphabet characters, converting text to lowercase, and stripping whitespace.
<br/>Sentiment Analysis: Uses NLTK’s VADER sentiment analysis tool to calculate sentiment scores.
<br/>Visualizations: Displays the sentiment distribution through pie charts and optional word cloud generation for most frequent words.

<br/>Requirements:
<br/>Python 3.7+
<br/>Libraries: Install the following Python libraries
<br/>pip install pandas nltk matplotlib wordcloud
<br/>If you are using VADER for the first time, download the VADER lexicon as follows:
<br/>import nltk
<br/>nltk.download('vader_lexicon')

<br/>File Structure
<br/>amazon_reviews.csv: Dataset containing Amazon product reviews.
<br/>amazon.ipynb: Jupyter Notebook file containing the project code.
<br/>README.md: Project documentation.

<br/>Setup and Usage
<br/>Clone the repository, Navigate to the directory, Open the Jupyter Notebook, Run Jupyter Notebook:

<br/>Data Loading: Reads the review dataset (amazon_reviews.csv).
<br/>Data Cleaning: Drops rows with missing reviews, processes text to remove non-alphabet characters, and standardizes it to lowercase.
<br/>Sentiment Scoring: Uses VADER to compute Positive, Negative, and Neutral scores for each review.
<br/>Sentiment Summary: Aggregates scores and displays the distribution of sentiments.
<br/>Visualization: Generates a pie chart showing the sentiment distribution across the reviews. Optionally, a word cloud is also generated.

<br/>Output
<br/>Pie Chart: Displays the proportions of Positive, Negative, and Neutral reviews.
<br/>Word Cloud: Visualizes frequently used words in the reviews.

<br/>Results: The analysis provides insight into overall customer sentiment, helping to understand customer feedback trends. Positive, negative, and neutral sentiments are summarized and visualized, offering potential applications for business insights and customer feedback analysis.
