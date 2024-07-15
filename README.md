# netflix_movies_clustering_unsupervisedML

The aim of project is to analyze the Netflix Dataset and TV shows untill 2019, sourced from the third-party search engine Fixable. The goal is to group the content into relevant clusters using NLP techniques to improve the user experience through a recommendation system. This will help prevent subscriber churn for Netflix, which country has over 220 million subscribers.

Additionally, the dataset will be analyzed to uncover insights and trends in the streaming entertainment industry.

The project followed a step-by-step process:

Handling null values in the dataset.
Managing nested columns (director, cast, listed_in, country) for better visualization.
Binning the rating attribute into categories (adult, children's, family-friendly, not-rated).
Performing Exploratory Data Analysis (EDA) to gain insights for preventing subscriber churn.
Creating clusters using attributes like director, cast, country, genre, rating and description. These attributes were tokenized, preprocessed and vectorized using TF-IDF vectorizer.
Reducing the dimensionality of the dataset using PCA to improve performance.
Employing K-means Clustering and Agglomerative Hierarchical Clustering algorithms, determining optimal cluster numbers (4 for K-means, 2 for hierarchical clustering) through various evaluation methods.
Developing a content-based recommender system using cosine similarity matrix to provide personalized recommendations to users and reduce subscriber churn for Netflix.
This comprehensive analysis and recommendation system are expected to enhance user satisfaction, leading to improved retentation rates for Netflix.
