# Movie Recommendation and Rating Analysis

## Project Overview

This project focuses on analyzing movie data to understand movie ratings, user preferences, genre popularity, and movie trends. It also implements a collaborative filtering recommendation system to suggest movies based on similar users' preferences.

## Project Structure

```text
Movie Recommendation and Rating Analysis/
│
├── data/
│   ├── movies.csv
│   ├── ratings.csv
│   ├── tags.csv
│   └── links.csv
│
├── notebooks/
│   └── Movie_Recommendation_Analysis.ipynb
│
└── README.md
```

## Dataset Description

The project uses the MovieLens dataset, which contains four CSV files:

- **movies.csv:** Contains movie IDs, movie titles, release years, and genres.
- **ratings.csv:** Contains user IDs, movie IDs, ratings, and timestamps.
- **tags.csv:** Contains user-generated movie tags and timestamps.
- **links.csv:** Contains movie IDs and their corresponding IMDb and TMDb IDs.

## Notebook Contents

The Jupyter Notebook includes the following analysis:

1. Data Loading and Inspection
2. Data Cleaning and Preparation
3. Exploratory Data Analysis (EDA)
4. Movie Rating Analysis
5. Genre-wise Movie Analysis
6. User Rating Behaviour Analysis
7. Movie Popularity Analysis
8. Collaborative Filtering Recommendation System
9. Recommendation System Evaluation
10. Final Project Insights and Conclusion

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Highlights

- Cleaned and analyzed movie datasets.
- Explored movie ratings and genre distribution.
- Identified popular movies and active users.
- Analyzed user rating behaviour and movie preferences.
- Applied cosine similarity to identify similar users.
- Built a collaborative filtering recommendation system.
- Generated personalized top 10 movie recommendations.

## Recommendation Approach

User-Based Collaborative Filtering was implemented using cosine similarity to identify users with similar movie preferences. Ratings from similar users were used to recommend movies that the selected user had not rated.

## Conclusion

This project demonstrates how Python, data analysis, and machine learning techniques can be used to explore movie trends, understand user preferences, and generate personalized movie recommendations.