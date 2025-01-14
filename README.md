
# Movie Recommendation System

This project is a **Movie Recommendation System** that utilizes collaborative filtering and cosine similarity to recommend movies based on user preferences and movie similarities. The system supports the following key features:

---

## Features

- **Find Similar Movies**: Get recommendations for movies similar to a selected movie.  
- **User-Based Recommendations**: Suggest movies for a specific user based on their previously rated movies.  
- **Interactive UI**: Use `ipywidgets` for an interactive interface to find similar movies or user-specific recommendations.  
- **Data Insights**: Analyze dataset size, unique users, and movies to understand the data distribution.  

---

## Dataset

The system uses the **MovieLens 20M Dataset** from Kaggle. It contains:  
- **Ratings**: User ratings for movies.  
- **Movies**: Metadata about movies.  

You can download the dataset [here](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset).  

---

## Requirements

Install the required libraries using pip:  

```bash
pip install tensorflow pandas numpy matplotlib scikit-learn opendatasets ipywidgets
