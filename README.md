**Collaborative Filtering**

- Collaborative Filtering simply put uses the "wisdom of the crowd" to recommend items.
- Item based collaborative filtering uses the patterns of users who liked the same movie as me to recommend me a movie (users who liked the movie that I like, also liked these other movies).
- Recommendation based on user's input of any movie present in the dataset.

**Data Pre-processing**
- Dropping columns that are not required
- Merging dataframes

**Cosine Similarity**

Also known as vector-based similarity, this formulation views two items and their ratings as vectors, and defines the similarity between them as the angle between these vectors:

<img align="left" width="250" height="75" src="https://github.com/abhilampard/Movie_Recommendation_Engine/raw/master/itembased-cosine.png">
