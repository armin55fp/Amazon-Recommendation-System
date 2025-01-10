# Amazon Product Recommendation System

This repository contains the implementation of a recommendation system for Amazon products using collaborative filtering techniques. The dataset includes user ratings for electronic products, and the project explores various algorithms to recommend products based on user preferences.

## Project Overview

Recommendation systems help online businesses provide personalized product suggestions to users. In this project, we build and compare three types of recommendation models:
1. Rank-based recommendation system.
2. Collaborative filtering models (user-user and item-item).
3. Model-based collaborative filtering using matrix factorization (SVD).

## Key Features
- Analyze user-product interactions to identify trends.
- Build baseline and optimized recommendation models.
- Evaluate model performance using precision@k, recall@k, and F1 score metrics.

## Dataset
The dataset includes:
- **user_id**: Unique identifier for users.
- **prod_id**: Unique identifier for products.
- **rating**: Product rating by the user (1–5).

### Note
The dataset used in this project is not included due to size and privacy considerations. Please refer to [Amazon Review Dataset](https://nijianmo.github.io/amazon/index.html) for access.

## Project Files
- **notebooks/Amazon_Recommendation_System.ipynb**: Jupyter Notebook with the code and analysis.

