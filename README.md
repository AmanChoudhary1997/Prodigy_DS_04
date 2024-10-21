![Screenshot 2024-10-21 195333](https://github.com/user-attachments/assets/b7e7d923-abbb-4e2b-b141-5eb666feab63)

# Twitter Sentiment Analysis

## Project Overview
This project analyzes and visualizes sentiment patterns in social media data (Twitter) to understand public opinion and attitudes towards specific topics and brands. The analysis is based on a dataset that contains tweets with associated topics and sentiment labels.

## Dataset
The dataset used for this analysis is the [Twitter Sentiment Dataset](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis), which consists of tweets categorized into various topics with sentiments labeled as **Positive**, **Negative**, **Neutral**, or **Irrelevant**.

### Columns:
- `ID`: Unique identifier for each tweet.
- `Topic`: The subject or brand discussed in the tweet.
- `Sentiment`: The sentiment associated with the tweet (Positive, Negative, Neutral, Irrelevant).
- `Text`: The actual content of the tweet.

## Project Structure
- **Data Preprocessing**: Handling missing values and duplicates.
- **Exploratory Data Analysis (EDA)**: Analyzing the distribution of topics and sentiments using visualizations.
- **Text Analysis**: Generating a word cloud to show common words, and analyzing message length by sentiment.

## Visualizations
The project contains several visualizations to help understand the data better:
1. **Topic Frequency**: A bar chart showing the frequency of each topic in the dataset.
2. **Sentiment Distribution**: A pie chart showing the distribution of sentiments across the dataset.
3. **Message Length Analysis**: A histogram to visualize the length of tweets and a boxplot to compare message length by sentiment.
4. **Top 10 Topics by Sentiment**: Bar charts to show the top 5 topics associated with positive, negative, and neutral sentiments.
5. **Sentiment by Topic**: Stacked bar chart displaying the count of sentiments for each topic.

## Key Insights
- **Most Frequent Topic**: The topic "TomClancyRainbowSix" is the most frequently discussed.
- **Sentiment Distribution**: The dataset contains more **Negative** sentiments (30.3%) than **Positive** (27.5%) or **Neutral** (24.7%). **Irrelevant** sentiments make up 17.5%.
- **Brand Sentiment**: Topics like **Google** and **Microsoft** show a more balanced or neutral sentiment distribution.
- **Message Length**: Most tweets are short (under 400 characters), and negative messages tend to be slightly longer on average.


