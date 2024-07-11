# ML-Netflix-Movie-Recommendation-System

Case-Study-ML-Netflix-Movie-Recommendation-System
A Machine Learning Case Study for Recommendation System of movies based on collaborative filtering and content based filtering.

Business Problem
Netflix is all about connecting people to the movies they love. To help customers find those movies, they developed a world-class movie recommendation system: CinematchSM. Its job is to predict whether someone will enjoy a movie based on how much they liked or disliked other movies. Netflix uses those predictions to make personal movie recommendations based on each customer’s unique tastes. And while Cinematch is doing pretty well, it can always be improved. Now there are a lot of interesting alternative approaches to how Cinematch works that Netflix hasn’t tried. Some are described in the literature, some aren’t. We’re curious whether any of these can beat Cinematch by making better predictions. Because, frankly, if there is a much better approach it could make a big difference to our customers and our business. Credits: https://www.netflixprize.com/rules.html

Problem Statement
Netflix provided a lot of anonymous rating data and a prediction accuracy bar that is 10% better than what Cinematch can do on the same training data set. (Accuracy is a measurement of how closely predicted ratings of movies match subsequent actual ratings.)

Real-world/Business Objectives and constraints
Objectives:
Predict the rating a user would give a movie he has not yet rated.
Minimize the difference between predicted and actual rating (RMSE and MAPE)
Constraints:
Some form of interpretability.
There is no low latency requirement as the recommended movies can be precomputed earlier.
