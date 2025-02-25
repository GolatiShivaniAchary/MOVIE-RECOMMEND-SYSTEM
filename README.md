# MOVIE-RECOMMEND-SYSTEM
A machine learning-based movie recommendation engine that suggests similar movies based on user input.

# Key Features:

Content-Based Filtering: Uses movie metadata (genres, cast, keywords, overview) to recommend similar movies.

Natural Language Processing (NLP): Processes text data using tokenization, stop-word removal, and feature extraction.

Vectorization & Similarity: Uses CountVectorizer and Cosine Similarity to find the most relevant movies.

Fast & Efficient: Provides recommendations in <1 second with optimized text processing.

# Tech Stack:
Python | Pandas | NumPy | Scikit-Learn | NLP | Cosine Similarity | CountVectorizer

# How It Works

1️-Loads and cleans the TMDB 5000 Movies Dataset

2️-Extracts relevant movie features (genres, cast, crew, keywords, overview)

3️-Converts text data into numerical vectors using CountVectorizer

4️-Calculates cosine similarity to rank and recommend top 5 similar movies
