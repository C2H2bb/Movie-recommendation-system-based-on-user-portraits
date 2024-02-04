# Movie-recommendation-system-based-on-user-portraits

## Introduction
This project implements a movie recommendation system using the Python Django framework. It combines Collaborative Filtering and User Profiling Clustering algorithms to offer features like movie rating recommendations, user similarity recommendations, a backend for user data management, and a frontend interface for movie recommendations and genre-based search.

## Database Structure
The system utilizes several key database tables:
- `movie`: Contains movie information.
- `genre`: Lists movie genres.
- `movie_genre`: Associates movies with their genres.
- `movie_hot`: Tracks popular movies based on the number of comments.
- `movie_rating`: Stores movie reviews.
- `user`: Manages user login information.
- `user_type`: Predicts user categories based on their information.

## Algorithms
### User Profiling Clustering
- Utilizes the KMeans clustering algorithm for categorizing user data, employing libraries like Faker and pandas for data creation and management.
- Data preprocessing includes converting categorical data into numerical format for analysis.
- The system visualizes multidimensional data using matplotlib and pandas to ensure model efficacy.

### Collaborative Filtering Recommendation
- The system calculates similarity scores between users based on their movie preferences to generate personalized movie recommendations.
- It includes functionalities for pagination, sorting, and setting parameters like the number of recommendations.

## Features
- **Non-Logged-In Users**: Access to the homepage, movie discovery, genre browsing, search, registration, and login.
- **Registration and Login**: Standard user authentication features.
- **Logged-In Users**: Additional features like recommended movies, profile-based recommendations, rating management, and personal information management.
- **Personal User Profile**: Users can fill in personal information like name, age, and gender, which is used for clustering and recommendations.
- **Movie Rating**: Users can rate and review movies, which influences future recommendations.

## Conclusion
This recommendation system aims to provide a tailored movie-watching experience by analyzing user preferences and behaviors. Thank you for your interest in our project.

---
