# movie_recomm-system
hybrid movie recommendation system

# 🎬 Hybrid Movie Recommendation System

This project presents a **Hybrid Movie Recommendation System** that combines multiple recommendation techniques to provide personalized movie suggestions. The goal is to enhance user engagement on streaming platforms by balancing popularity, personalization, and content relevance.

---

## 📌 Project Overview

In today's digital era, recommending relevant content is crucial for user retention and satisfaction on streaming platforms like Netflix or Prime Video. This system integrates **three recommendation techniques**:

1. **Popularity-Based Filtering**
2. **Collaborative Filtering** (using SVD)
3. **Content-Based Filtering** (using genre similarity)

A final **hybrid model** merges these methods to deliver top recommendations for each user.

---

## 🧠 Techniques Used

### 1. Popularity-Based Filtering
- Uses IMDb-style weighted average formula
- Ranks movies based on rating count and average rating

### 2. Collaborative Filtering (SVD)
- Learns latent features from user-item interactions
- Predicts user ratings for unseen movies

### 3. Content-Based Filtering
- Uses one-hot encoding on genres
- Recommends movies similar to those a user has already liked

### 4. Hybrid Recommendation
- Combines the output scores of all three models
- Produces a refined top-N recommendation list per user

---

## 🛠️ Technologies & Tools

- **Python**
- **Pandas, NumPy**
- **Scikit-learn**
- **Surprise (for SVD model)**
- **Matplotlib / Seaborn** (for visualization)
- **Jupyter Notebook**

---

## 📊 Evaluation Metrics

- **Classification F1-score:** 0.6258 (before & after tuning)
- **SVD RMSE:** 0.8803
- **KMeans Clustering Silhouette Score:** 0.2064


