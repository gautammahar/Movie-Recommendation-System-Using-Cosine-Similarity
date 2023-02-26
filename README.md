# Movie-Recommendation-System-Using-Cosine-Similarity
## Overview -
In this project, we have built a movie recommendation system using cosine similarity. The dataset used for this project is movies.csv which contains various features related to movies such as title, genres, keywords, tagline, cast, and director. We have preprocessed the data by replacing the null values with a null string and combining the selected features to create a feature vector using TfidfVectorizer. Cosine similarity is then used to calculate the similarity score between the movies.

## Description -
The first step of the project is to import the required libraries including numpy, pandas, difflib, TfidfVectorizer, and cosine_similarity. We have then loaded the movie dataset (movies.csv) using pandas and selected relevant features such as genres, keywords, tagline, cast, and director.

Next, we have replaced the null values with a null string and combined the selected features to create a feature vector using TfidfVectorizer. We have then used cosine similarity to calculate the similarity score between the movies.

The user can enter the name of their favorite movie, and the system will suggest similar movies based on the cosine similarity score. The system uses difflib library to find the closest match for the user's input if there is a typo or incorrect spelling.

Overall, this project demonstrates the implementation of cosine similarity to build a movie recommendation system and can be further improved by incorporating additional features or algorithms.




