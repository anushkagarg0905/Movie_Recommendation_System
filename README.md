# 🎬  CineWatch – Movie Recommendation System

This project is a simple movie recommendation system built using machine learning. It suggests similar movies based on the one selected by the user.

# About the Project

The system uses a content-based filtering approach. It looks at different features like genres, cast, keywords, and overview to find similarities between movies and recommend the most relevant ones.

# Features

- Recommends top 5 similar movies
- Uses movie metadata for better suggestions
- Shows movie posters using TMDB API
- Simple and interactive UI built with Streamlit


# Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Streamlit

  
# Dataset

- TMDB 5000 Movies Dataset
- TMDB 5000 Credits Dataset

# Procedure

- Cleaned and merged the datasets
- Extracted useful features (genres, cast, crew, keywords, overview)
- Converted text data into vectors using CountVectorizer
- Calculated similarity using cosine similarity
- Returned top 5 similar movies
