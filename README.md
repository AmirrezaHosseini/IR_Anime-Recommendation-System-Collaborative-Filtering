# IR_Anime-Recommendation-System-Collaborative-Filtering
## Information Retrival Course  Project

An anime recommendation system using Cosine similarity

The Dataset

This dataset contains information on user preference data from 73,516 users on 12,294 anime, found on myanimelist.net. Each user is able to add anime to their completed list and give it a rating. This dataset is a compilation of those ratings, using the following features:

Anime.csv

anime_id - myanimelist.net's unique id identifying an anime
name - full name of anime
genre - comma separated list of genres for this anime
type - movie, TV, OVA, etc
episodes - how many episodes in this show. (1 if movie)
rating - average rating out of 10 for this anime
members - number of community members that are in this anime's "group"

Rating.csv

user_id - non identifiable randomly generated user id
anime_id - the anime that this user has rated
rating - rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating)

Goal :
By applying the Collaborative-Filtering model to the ratings that users have registered for the videos, to
User suggest new movies.

