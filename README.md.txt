# US Election Sentiment Analysis

This project analyzes public sentiment on Reddit regarding the U.S. 2024 election. It focuses on extracting, processing, and analyzing Reddit posts from election-related subreddits to observe public opinion trends surrounding key candidates.

## Project Overview
- **Data Collection**: Uses PRAW to fetch Reddit data from specific subreddits related to the U.S. election.
- **Data Processing**: Cleans and preprocesses text data by removing stop words, punctuation, and other irrelevant terms.
- **Sentiment Analysis**: Applies TextBlob to determine the sentiment polarity of each post, categorizing them as positive, neutral, or negative.
- **Keyword Analysis**: Identifies common keywords within positive and negative sentiment posts to understand themes and topics.
- **Visualization**: Creates visualizations to show sentiment distribution over time and compare sentiment across different candidates.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your_username/reddit_sentiment_analysis_us_elections.git
   cd reddit_sentiment_analysis_us_elections

2. **Install Dependencies**: 
Ensure you have Python 3.8 or later. Install required packages by running:
```bash
pip install -r requirements.txt

3. **Configure Reddit API Access**:
- Go to Reddit's App Preferences and create a new application to get your client_id, client_secret, and user_agent.
- Create a config.py file in the scripts folder 

4. **Run the Notebook**:
- Ensure that all paths and configurations are correctly set for smooth execution.

## Dependencies

- Python 3.8 or later
- Required Libraries: PRAW, TextBlob, NLTK, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- Install dependencies from requirements.txt

## Analysis Summary

- Sentiment Distribution: Visualizes the daily sentiment trend for Reddit posts in 2024, highlighting key events like Election Day.
- Keyword Analysis: Extracts the most frequent keywords within positive and negative sentiment posts to uncover key themes for each candidate.
- Candidate Sentiment Comparison: Analyzes sentiment trends specific to major candidates to show how public opinion varies.

## Key Insights

This analysis provides valuable insights into public sentiment toward the U.S. 2024 election based on Reddit discussions. The project reveals common themes, shifts in sentiment over time, and public opinion regarding different candidates. This approach can be useful for understanding broader trends in public opinion and identifying major topics of interest or concern during the election cycle.