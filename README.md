# 🎬 Movie Recommender System

This project builds a Movie Recommender System using collaborative filtering techniques to suggest movies based on user preferences. It leverages both K-Nearest Neighbors (KNN) and matrix factorization via Truncated SVD to provide personalized movie recommendations.

---

## 📌 Project Overview

The primary goal is to build a recommender that works without any content-based metadata, relying solely on user rating behavior. The dataset comprises user-generated movie ratings and metadata for a wide range of films, commonly used for recommender systems research and analysis.


Dataset Reference: https://www.kaggle.com/datasets/gargmanas/movierecommenderdataset/data

---

## 📂 Datasets

- **movies.csv**: Contains movie titles and genres
- **ratings.csv**: Contains user ratings for movies

---

## 🛠️ Features & Techniques

- 📊 **Exploratory Data Analysis (EDA)** to understand rating patterns and movie popularity
- 🧩 **User-Item Matrix** construction
- 🤖 **Collaborative Filtering** using:
  - **KNN** (cosine similarity)
  - **Matrix Factorization** using **TruncatedSVD**
- 🧠 **Latent Feature Extraction** for efficient similarity search
- 📈 **Recommendation Functions** to return top-k similar movies

---

## 🔍 Key Insights

- KNN captures surface-level similarities based on user behavior
- SVD performs better on scalability and captures deeper patterns
- Cold-start remains a challenge for new users/movies
- Hybrid models could enhance performance further

---

## 💡 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ugbovoyoma/movie-recommender-system.git
   cd movie-recommender-system
