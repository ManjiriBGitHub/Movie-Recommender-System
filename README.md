﻿# Movie Recommender System 
![TMDB](https://github.com/user-attachments/assets/c152cd36-d819-436f-95d9-88704e53a042)

## Introduction 

A Movie Recommender System is an application designed to suggest films to users based on their preferences, behaviors, and interactions. It leverages data from various sources—such as user ratings, reviews, watch history, and even social media activity—to provide personalized recommendations. These systems are widely used by streaming platforms like Netflix, Hulu, and Amazon Prime to enhance user experience and keep viewers engaged.


## Objective 
To develop a content-based movie recommender system using TMDB data, which provides personalized movie suggestions by analyzing the features of movies that users have already enjoyed. The system will utilize key attributes such as genres, cast, directors, and keywords to recommend films with similar content, ensuring that users discover new movies that align with their individual tastes and preferences.


## Data Overview

The TMDB 5000 Movie Dataset comprises two primary datasets: 

tmdb_5000_movies and tmdb_5000_credits. The tmdb_5000_movies dataset includes information such as budget, genres, homepage, id, keywords, original language, original title, overview, popularity, production companies, production countries, release date, revenue, runtime, spoken languages, status, tagline, title, vote average, and vote count. 

The tmdb_5000_credits dataset provides details on movie_id, title, cast, and crew. This comprehensive dataset offers insights into various aspects of films, including their production details, financial performance, and popularity.


Dataset Link : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

## Dependencies

Make sure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- PyCharm
- Pandas
- NumPy
- Scikit-Learn
- nltk
- streamlit 

## Project Workflow 

### [1] Data Preprocessing: 
Cleans and tokenizes movie descriptions and genres.

### [2] Feature Extraction:
 Extracts key features using Bag of Words Technique.

### [3] Similarity Calculation:
 Computes similarities between the movies and the user profile using Cosine Similarity 

### [4] Recommendation Algorithm :
 Create a recommendation function 

### [5]  Website Building using streamlit :
 Install and configure Streamlit to build an interactive web interface.
