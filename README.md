# Predictive Analytics

Welcome to my repository of predictive analytics techniques. This repository showcases two distinct machine learning techniques applied to real-world datasets. Each notebook demonstrates a core method for solving specific problems, such as customer segmentation and building a recommender system.

## Repository Structure
This repository contains the following notebooks:

- PCA + Clustering\
In this notebook, I perform clustering analysis on nightclub customers based on their perceptions of pricing fairness, intent to revisit, and demographic variables. The goal is to identify distinct customer segments that can provide valuable insights into customer behavior. The notebook includes:
  - Data Preprocessing: Handling missing values, normalizing variables, and encoding categorical variables.
  - Clustering: Experimentation with different clustering methods, such as K-Means, to group customers into segments.
  - Interpretation & Insights: Analyzing the clusters to understand key traits and provide actionable insights to nightclub management, such as tailoring pricing strategies to different customer segments.

- DNN for Recommender System\
This notebook demonstrates the creation of a Deep Neural Network (DNN) for building a recommendation system using the MovieLens 100k dataset. The goal is to predict movie ratings for a given user based on their previous ratings. The notebook includes:
  - Data Preprocessing: Loading and preparing the MovieLens dataset, which includes user, movie, and ratings data.
  - Matrix Factorization: Implementing unweighted regularized matrix factorization for collaborative filtering.
  - Deep Neural Network: Building a DNN-based recommender system, where the architecture, number of layers, embeddings, and loss functions are carefully selected and explained.
  - Recommendation Function: The notebook includes a function to generate movie recommendations for any given user based on the trained model.
 
## How to Use
1. Clone the repository to your local machine or open the individual Google Colab notebooks for execution:
'''
bash
git clone https://github.com/your-username/Predictive-Analytics.git
'''
2. Each file contains a Jupyter Notebook for the respective technique. Open the notebooks in Google Colab or your preferred Jupyter environment.
3. Follow the markdown cells for explanations and a breakdown of the methods used.

## Requirements
To run the code, make sure you have the following libraries installed:
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- TensorFlow (for the DNN notebook)
