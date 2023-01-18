# GA-Capstone-Project

# Problem Statement
The dataset contains metadata for all 45,000 movies listed in the full MovieLens dataset released on or before July 2017. Movie features includes cast, plot keywords and vote counts/averages obtained via the TMDB Open API. It also contains 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.<br>

[Source of dataset: Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

# Background

Recommender systems are used widely these days. It is used to provide better suggestions to customers which in turn drive sales and reduce churn rate to allow customer retention. <br>

Netflix is one of the top movie streaming services in the world. About 80% of what their users watches come from their recommendation algorithms ([Source](https://recoai.net/netflix-recommendation-system-how-it-works/)). This shows that recommendator systems and algorithms are largely relied upon these days to recommend movies to users. <br>

The aim of this project is to build various movie recommender systems and study how the different unsupervised learning algorithms/models make predictions before determining which might be a better system to rely on in production.

# Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|adult|object|movies_metadata.csv|Indicates if movie is for Adults|
|belongs_to_collection|object|movies_metadata.csv|Movie Series a movie belongs to|
|budget|object|movies_metadata.csv|Budget of the movie in dollars|
|genres|object|movies_metadata.csv|Genres associated with the movie|
|homepage|object|movies_metadata.csv|Official homepage of the movie|
|id|object|movies_metadata.csv|ID of movie|
|imdb_id|object|movies_metadata.csv|IMDB ID of movie|
|original_language|object|movies_metadata.csv|Language which the movie was shot in|
|original_title|object|movies_metadata.csv|Original Title of movie|
|overview|object|movies_metadata.csv|Brief Description of the movie|
|popularity|object|movies_metadata.csv|Popularity score assigned by TMDB|
|poster_path|object|movies_metadata.csv|URL of the poster image|
|production_companies|object|movies_metadata.csv|Production Companies involved with making of the movie|
|production_countries|object|movies_metadata.csv|Countries where the movie was shot/produced in|
|release_date|object|movies_metadata.csv|Theatrical Release Date of the movie|
|revenue|float|movies_metadata.csv|Total Revenue of the movie in dollars|
|runtime|float|movies_metadata.csv|Runtime of the movie in minutes|
|spoken_languages|object|movies_metadata.csv|Spoken Languages in the movie|
|status|object|movies_metadata.csv|Status of the movie|
|tagline|object|movies_metadata.csv|Tagline of the movie|
|title|object|movies_metadata.csv|Official Title of the movie|
|video|object|movies_metadata.csv|Indicates if there is a video present of the movie with IMDB|
|vote_average|float|movies_metadata.csv|Average Rating of the movie|
|vote_count|float|movies_metadata.csv|Number of votes by users, as counted by TMDB|
|id|integer|keywords.csv|ID of movie|
|keywords|object|keywords.csv|Movie Plot Keywords|
|cast|object|credits.csv|Cast information|
|crew|object|credits.csv|Crew information|
|id|integer|credits.csv|ID of movie|
|userId|integer|ratings.csv|userID|
|movieId|integer|ratings.csv|ID of movie|
|rating|float|ratings.csv|user rating of movie|
|timestamp|integer|ratings.csv|timestamp of rating|
|userId|integer|ratings_small.csv|userID|
|movieId|integer|ratings_small.csv|ID of movie|
|rating|float|ratings_small.csv|user rating of movie|
|timestamp|integer|ratings_small.csv|timestamp of rating|

*Note: ratings_small.csv is the subset of ratings.csv which contains 100,000 ratings from 700 users on 9,000 movies.

# Summary of Analysis

# Conclusion/Recommendations

Limitations: <br>
- 

Recommendations: <br>
1. 
