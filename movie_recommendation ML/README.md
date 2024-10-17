# Movie Recommendation System - Machine Learning Project

This project builds a **Movie Recommendation System** using machine learning. It helps users find movies they might like based on their preferences and ratings of other movies. The project uses Python for data processing, analysis, and modeling.

## Overview
We create a recommendation system that suggests movies based on user ratings and similarities between movies. This project demonstrates how machine learning can be applied to provide personalized recommendations.

## Tools and Libraries Used
- **Python**: The programming language used
- **Jupyter Notebook**: To write and run the analysis
- **pandas**: For data manipulation and analysis
- **numpy**: For numerical computations
- **scikit-learn**: For machine learning models
- **matplotlib & seaborn**: For visualizing data insights

## Dataset
We used a dataset named `movies.csv` that contains information about various movies, including:
- **MovieID**: Unique identifier for each movie
- **Title**: The name of the movie
- **Genre**: Categories the movie belongs to

## Project Steps
1. **Data Loading**: We start by loading the movie data using `pandas`.
2. **Exploratory Data Analysis (EDA)**: We explore the dataset to understand movie genres, ratings, and how movies are related.
3. **Data Preprocessing**: Clean the data by removing duplicates and handling missing values.
4. **Building the Recommendation Model**: 
   - We use machine learning techniques like **Collaborative Filtering** to recommend movies based on user preferences and movie similarities.
5. **Interactive Recommendations**: The model suggests movies based on the user's input or previously watched movies.

## Example Usage
Here’s how you can load the data, build the recommendation model, and display movie suggestions all together:

```python
import pandas as pd

# Step 1: Load the dataset
movies = pd.read_csv('movies.csv')
print("Movies Dataset: \n", movies.head())

# Step 2: Simple recommendation function
def recommend_movies(movie_title):
    # Dummy recommendations based on the input movie (this logic can be replaced with actual model)
    recommendations = ['Movie 1', 'Movie 2', 'Movie 3']  
    print(f"Recommendations for '{movie_title}': {recommendations}")
    return recommendations

# Step 3: Get recommendations for a specific movie
recommend_movies('Inception')

# Conclusion: Enjoy exploring the Movie Recommendation System, experiment with movie inputs, and build your own recommendation logic!




