# Book-Recommender
This project implements a Book Recommender System using dimensionality reduction and clustering techniques. It leverages the TruncatedSVD algorithm for reducing the dimensionality of a book-user rating matrix and KMeans clustering to group similar books together. The system visualizes the clusters and highlights a user-specified book, aiding in understanding book similarities based on user ratings.

Project Overview
The Book Recommender System aims to cluster books based on user ratings and visualize them in a 2D space. By reducing the dimensionality of the data using TruncatedSVD and applying KMeans clustering, the system groups books into clusters of similar preferences. Users can input a book title (e.g., "Zoya") to see its position within the clusters, helping to identify related books.

Features
Dimensionality reduction using TruncatedSVD to transform high-dimensional book-user data into 2D.
Clustering of books into 5 groups using KMeans.
Visualization of book clusters with a highlighted user-specified book using matplotlib and seaborn.
Error handling for invalid book titles.
Requirements
To run this project, you'll need the following Python libraries:

scikit-learn (for TruncatedSVD and KMeans)
matplotlib (for plotting)
seaborn (for enhanced visualizations)
numpy (for numerical operations)
pandas (assumed for handling the book_pivot DataFrame)
