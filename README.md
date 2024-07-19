# Anime Recommender System

## Overview
This project is an Anime Recommender System that uses collaborative filtering and content-based filtering techniques to suggest anime titles based on user input and preferences. It features an interactive interface built with Jupyter widgets and employs machine learning algorithms for accurate recommendations.

## Features
- Interactive search interface with autocomplete functionality
- Collaborative filtering for user-based recommendations
- Content-based filtering for genre and feature-based recommendations
- Fuzzy matching for improved partial-text search
- Visualization of recommendation scores and similarities
- Detailed anime information display

## Technologies Used
- Python 3.12
- Pandas for data manipulation
- Scikit-learn for TF-IDF vectorization and cosine similarity
- FuzzyWuzzy for string matching
- Jupyter Notebooks and IPyWidgets for the interactive interface
- Matplotlib and Seaborn for data visualization
  
## Data
The system uses a dataset of anime titles, including information such as genre, type, and user ratings. The dataset is preprocessed to create a user-anime matrix for collaborative filtering.

## How It Works
1. **Search Function**: Utilizes TF-IDF vectorization and cosine similarity, combined with fuzzy matching for flexible search capabilities.
2. **Collaborative Filtering**: Analyzes user-anime interactions to find similar users and recommend anime based on their preferences.
3. **Content-Based Filtering**: Recommends anime based on genre similarities and other features when user data is insufficient.
4. **Hybrid Approach**: Combines both filtering methods for more robust recommendations.

## Visualizations
The system includes several visualizations:
- Bar charts comparing recommendation scores
- Heatmaps showing genre correlations
- Scatter plots of anime popularity vs. ratings

## Acknowledgments
- Data source: [Anime Dataset on Kaggle](https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database)
- Inspired by various recommender system implementations and anime databases
- This is my capstone that I used to graduate with. 
