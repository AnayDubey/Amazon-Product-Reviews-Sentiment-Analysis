Amazon Product Reviews Sentiment Analysis

Overview
This project performs sentiment analysis on Amazon product reviews to classify them into Positive, Negative, or Neutral categories. It uses VADER (Valence Aware Dictionary and sEntiment Reasoner), a lexicon and rule-based sentiment analysis tool in Python, to assess customer sentiment based on review content. The project includes data preprocessing, sentiment scoring, and visualization to interpret and display the results effectively.

Features
Data Cleaning: Handles missing data and pre-processes review text by removing non-alphabet characters, converting text to lowercase, and stripping whitespace.
Sentiment Analysis: Uses NLTK’s VADER sentiment analysis tool to calculate sentiment scores.
Visualizations: Displays the sentiment distribution through pie charts and optional word cloud generation for most frequent words.
Requirements
Python 3.7+
Libraries: Install the following Python libraries
bash
Copy code
pip install pandas nltk matplotlib wordcloud
If you are using VADER for the first time, download the VADER lexicon as follows:
python
Copy code
import nltk
nltk.download('vader_lexicon')
File Structure
amazon_reviews.csv: Dataset containing Amazon product reviews.
amazon.ipynb: Jupyter Notebook file containing the project code.
README.md: Project documentation.
Setup and Usage
Clone the repository

bash
Copy code
git clone https://github.com/your-username/amazon-sentiment-analysis.git
Navigate to the directory

bash
Copy code
cd amazon-sentiment-analysis
Open the Jupyter Notebook

Run Jupyter Notebook:
bash
Copy code
jupyter notebook amazon.ipynb
Follow the cells step-by-step to run the code.
Project Flow in Jupyter Notebook

Data Loading: Reads the review dataset (amazon_reviews.csv).
Data Cleaning: Drops rows with missing reviews, processes text to remove non-alphabet characters, and standardizes it to lowercase.
Sentiment Scoring: Uses VADER to compute Positive, Negative, and Neutral scores for each review.
Sentiment Summary: Aggregates scores and displays the distribution of sentiments.
Visualization: Generates a pie chart showing the sentiment distribution across the reviews. Optionally, a word cloud is also generated.
Output
Pie Chart: Displays the proportions of Positive, Negative, and Neutral reviews.
Word Cloud (Optional): Visualizes frequently used words in the reviews.
Results
The analysis provides insight into overall customer sentiment, helping to understand customer feedback trends. Positive, negative, and neutral sentiments are summarized and visualized, offering potential applications for business insights and customer feedback analysis.

Future Enhancements
Incorporate additional sentiment analysis models to compare results.
Extend visualization to other review categories or products.
Implement real-time analysis for ongoing reviews.
