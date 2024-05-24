# Movie-Recommendation

This notebook demonstrates a simple movie recommendation system using the TF-IDF vectorizer and sigmoid kernel from the sci-kit-learn library. The dataset used is a collection of 5000 movies from TMDB (The Movie Database).

The main steps involved are:
* Load the movie and credit data from CSV files.
* Merge the two datasets based on the movie ID.
* Clean and preprocess the data by dropping unnecessary columns and handling missing values.
* Use TF-IDF vectorizer to convert the movie overviews (plot summaries) into a matrix of TF-IDF features.
* Compute the sigmoid kernel to calculate the pairwise similarity scores between movies based on their TF-IDF vectors.
* Implement a function to provide movie recommendations based on the similarity scores.

The notebook demonstrates how to use the recommendation function to get the top 10 most similar movies for a given movie title.
