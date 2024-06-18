# Unsupervised-ML-Netflix-Movies-and-TV-Shows-Clustering
The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset, which includes movies and TV shows as of 2019, will be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.


    There were approximately 7787 records and 12 attributes in the dataset.

    We started by working on the missing values in the dataset and conducting exploratory data analysis (EDA).

    Using the following attributes to create a cluster: cast, country, genre, director, rating, and description The TFIDF vectorizer was used to tokenize, preprocess, and vectorize the values in these attributes.

    The problem of dimensionality was dealt with through the use of Principal Component Analysis (PCA).

    Using a variety of methods, including the elbow method, silhouette score, and others, we constructed cluster with the K-Means Clustering algorithms, and determined the optimal number of clusters

