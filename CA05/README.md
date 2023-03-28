# Machine_Learning

Computer Assignment #5

Problem Statement:
The goal of this recommender engine is to provide movie recommendations to users based on their query movie. Given a movies data set, the engine finds the 5 most similar movies to a movie

Data Source and Contents
The movie data set is stored in a CSV file named movies_recommendation_data.csv, which is hosted on GitHub. The data contains thirty movies, including data for each movie across seven genres and their IMDB ratings. The labels column values are all zeroes because we aren’t using this data set for classification or regression.


Implementation
The recommender engine is implemented using Python's scikit-learn library, with the following steps:
Load the movie dataset from the provided CSV file into a Pandas DataFrame.
Endode the data using OneHotEncoding
Instantiate the kNN model and fit it to the data
Create a feature vector for the query movie to display similar movies 
Use the kNN model to find the 5 most similar to movies to "the post"
Display the recommendations to the user.








