# clustering-ML-project_Netflix-movies-tv-shows
this is an unsupervised machine learning project . 
in this we used 3 models and also have done EDA for clear understanding before performing the machine learning models.
business context and conclusion is well explained in the colab . 
The project followed a step-by-step process:
1. Handling null values in the dataset.
2. Managing nested columns (director, cast, listed_in, country) for better visualization.
3. Binning the rating attribute into categories (adult, children's, family-friendly, not rated).
4. Performing Exploratory Data Analysis (EDA) to gain insights for preventing subscriber churn.
5. Creating clusters using attributes like director, cast, country, genre, rating, and description. These attributes were tokenized, preprocessed, and vectorized using TF-IDF vectorizer.**
6. Reducing the dimensionality of the dataset using PCA to improve performance.
7. Employing K-Means Clustering and Agglomerative Hierarchical Clustering algorithms, determining optimal cluster numbers (4 for K-Means, 2 for hierarchical clustering) through various evaluation methods.
8. Developing a content-based recommender system using cosine similarity matrix to provide personalized recommendations to users and reduce subscriber churn for Netflix
