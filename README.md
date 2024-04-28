# Stress Detection Prediction Model

## Overview

This project aims to develop a machine learning model for predicting stress levels in text data using the Stress Detection Dataset. It serves also as a project assignment for the course Introduction to Data Mining and Machine Learning at FAMNIT.

## Dataset

The Stress Detection Dataset provides a collection of posts from various subreddits related to mental health. Each entry in the dataset includes information such as subreddit, post ID, sentence range, text, label (indicating stress (1) or no stress (0)), confidence, and social timestamp. 

### Dataset Details

- **File:** Stress.csv
- **Columns:**
  - `subreddit`: Name of the subreddit where the post was made
  - `post_id`: ID of the post
  - `sentence_range`: Range of sentences in the post
  - `text`: Text content of the post
  - `label`: Binary label indicating stress (1) or no stress (0)
  - `confidence`: Confidence score associated with the label
  - `social_timestamp`: Timestamp of the post

## Project Components

1. **Data Preprocessing:** Performing data cleaning and preprocessing (removing punctuation, stopwords, lemmatizing using Spacy).
2. **Data Visualization:** A little bit of visualization to provide context for the dataset.
3. **Text Representation:** Exploring different text representations like Bag of Words, Bag of N-Grams, and Gensim Glove.
4. **Model Exploration:** Explore different machine learning algorithms including Naive Bayes and LSTM.
5. **Model Evaluation:** Evaluating the models and measuring accuracy.

## Possible Future Improvements 
I would love to explore the 'confidence' column of the dataset as it potentially influences the 'weight' of the users' posts, but for simplicity I decided not to tackle it yet. Also I would find great interest in exploring Transformer architecture for an NLP task, let it be this one or some other future project.

## Contribution Guidelines

Contributions to the project are welcome! If you have any suggestions, bug fixes, or feature enhancements, please feel free to submit a pull request or open an issue on the GitHub repository.
