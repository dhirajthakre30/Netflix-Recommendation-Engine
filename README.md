# Netflix-Recommendation-Engine

# Problem Statement

Customer Behaviour and it’s prediction lies at the core of every Business Model. From Stock Exchange, e Commerce and Automobile to even Presidential Elections, predictions serve a great purpose. Most of these predictions are based on the data available about a person’s activity either online or in person.Recommendation Engines are the much needed manifestations of the desired Predictability of User Activity. Recommendation Engines move one step further and not only give information but put forth strategies to further increase users interaction with the platform.In today’s world OTT platform and Streaming Services have taken up a big chunk in the Retail and Entertainment industry. Organizations like Netflix, Amazon etc. analyse User Activity Pattern’s and suggest products that better suit the user needs and choices.For the purpose of this Project we will be creating one such Recommendation Engine from the ground up, where every single user, based on there area of interest and ratings, would be recommended a list of movies that are best suited for them.

# Dataset Information

1.ID- Contains the separate keys for customer and movies.

2.Rating-A section contains the user ratings for all the movies.

3.Genre- Highlights the category of the movie.

4.Movie Name- Name of the movie with respect to the movie id.

# Objective

1.Find out the list of most popular and liked genre

2.Create Model that finds the best suited Movie for one user in every genre.

3.Find what Genre Movies have received the best and worst ratings based on User Rating.

# Data Pre-processing Steps

1.Load the Customer id and Rating dataset

2.Cheking the information of the data such as datatype of the column, number of columns and rows

3.Handling missing values

4.Handling duplicated values

5.Get the movie count

6.Get getting how many unique customers are in our dataset

7.Finding the different ratings of the movies

8.Removing all the users that have rated less movies

9.Also all those movies that has been rated less in numbers

10.Creating a benchmark and dropping the movies which do not fall under that benchmark

11.Removing all the users that are in-active

12.Loading the movies title dataset and performing the data cleaning

# Choosing the Algorithm for the Project

# SVD- Singular Value Decomposition

SVD is used for Netflix recommendations because it efficiently handles large, sparse rating matrices, captures latent user-movie preferences, and generalizes well to unseen data. It scales better than KNN, performs better than basic collaborative filtering, and was a key approach in the Netflix Prize competition. Optimized versions like SVD++ also handle biases and missing data effectively. While deep learning models exist, SVD remains a strong choice for its balance of accuracy, scalability, and interpretability.

# Conclusion

In this project, we built a Netflix recommendation engine using collaborative filtering and matrix factorization (SVD) to predict user preferences. Our model effectively analyzes past user interactions to suggest relevant movies, improving user engagement and personalization
