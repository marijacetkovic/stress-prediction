# Stress Detection Dataset

## Overview

The Stress Detection Dataset provides a collection of posts from various subreddits related to mental health. Each entry in the dataset includes information such as subreddit, post ID, sentence range, text, label, confidence, and social timestamp. The dataset is labeled with binary values, where 0 indicates no stress and 1 indicates stress.

Stress detection presents a significant challenge in natural language processing and machine learning due to the diverse range of words and expressions people use to convey their mental states. This dataset serves as a valuable resource for training machine learning models to identify signs of psychological stress in text data.

## Dataset Details

- **File:** Stress.csv
- **Columns:**
  - `subreddit`: Name of the subreddit where the post was made
  - `post_id`: ID of the post
  - `sentence_range`: Range of sentences in the post
  - `text`: Text content of the post
  - `label`: Binary label indicating stress (1) or no stress (0)
  - `confidence`: Confidence score associated with the label
  - `social_timestamp`: Timestamp of the post


## Tags

- Naive Bayes
- LSTM
- Bag of Words
- Ngrams
- Gensim Word2Vec

