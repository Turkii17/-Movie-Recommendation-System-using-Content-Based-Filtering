# -Movie-Recommendation-System-using-Content-Based-Filtering


# Overview
This repository contains a Python implementation of a movie recommendation system based on content-based filtering. The system utilizes the TMDB 5000 Movie Dataset, consisting of information about movies and credits. The recommendation algorithm relies on natural language processing techniques to analyze movie overviews and suggest similar films.

# Data Source
The dataset is sourced from two CSV files: tmdb_5000_credits.csv and tmdb_5000_movies.csv.
# Data Loading and Preprocessing:

Load data from CSV files using Pandas.
Rename columns for consistency.
Merge the credits and movies datasets based on the movie ID.
# Data Cleaning:

Remove unnecessary columns (e.g., homepage, duplicate title columns, status, production countries).
# Text Data Processing:

Tokenize and vectorize movie overviews using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
Handle missing values in overviews.
# Similarity Calculation:

Utilize the sigmoid kernel to calculate the similarity matrix between movies.
# Recommendation Function:

Implement a function to provide movie recommendations based on a given movie title.
# Evaluation Metric:

Evaluate the precision at K as an additional metric for recommendation quality.
