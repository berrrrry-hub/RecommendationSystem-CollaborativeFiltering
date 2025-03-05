# 📊 Collaborative Filtering Recommendation System

## 🚀 Project Overview
This project applies **collaborative filtering** to build a recommendation system that predicts user preferences based on past interactions. The goal is to improve personalized recommendations by analyzing user-item relationships.

- **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, Surprise Library
- **Dataset:** Not explicitly mentioned (Please update with dataset name)
- **Methods Used:** User-based & Item-based Collaborative Filtering, Matrix Factorization (SVD, ALS, etc.)
- **Evaluation Metrics:** RMSE, MAE

---

## 📅 Problem Statement
Recommender systems are essential in modern digital platforms, helping users find relevant items based on their interests. This project aims to develop a recommendation system using **collaborative filtering** techniques, allowing:

- Personalized recommendations based on past interactions.
- Improved user engagement and satisfaction.
- Efficient handling of large-scale recommendation datasets.

---

## 📑 Data & Preprocessing
- **Columns:**
- `userId` – Unique identifier for users
- `movieId` – Unique identifier for movies
- `rating` – User-assigned rating for a movie
- `timestamp` – Time of rating (Unix format)
- `title` – Movie title
- `genres` – Genres associated with the movie
- **Data Cleaning:** Handling missing values, filtering inactive users/items
- **Feature Engineering:** Creating a user-item interaction matrix, normalizing ratings

---

## 🔍 Methodology
1. **User-Based Collaborative Filtering** – Recommends items based on user similarity.
2. **Item-Based Collaborative Filtering** – Finds similar items based on past user interactions.
3. **Matrix Factorization (Optional)** – Uses algorithms like SVD or ALS for dimensionality reduction and better generalization.

---

## 📊 Results & Insights
- **Model Performance:**
  - **RMSE:** 0.82
  - **MAE:** 0.59
- **Key Observations:**
  - Popular items tend to be recommended more frequently.
  - User-based filtering works better for dense datasets, while item-based filtering is more scalable.
  - Cold-start problems may exist for new users and items.

📍 **Summary:**
This is a typical way how recommendation system works, The modle performance is decent! 
But it tooks around 20 min to run the code, if the dataset is larger, we need to consider how to fasten the running process and reduce computational requirement.

## 🔮 Challenges & Future Work
**Challenges:**
- Sparse data leading to ineffective recommendations.
- Handling cold-start problems for new users and items.
- Computational efficiency for large datasets.

**Future Improvements:**
- Implementing hybrid models (content-based + collaborative filtering).
- Experimenting with deep learning approaches for recommendations.
- Improving recommendation diversity to avoid popularity bias.

---

## 👤 Contact & Portfolio
👤 **Jiaxin(Berry) Tian**  
📧 berrytian15@gmail.com  
🔗 https://github.com/berrrrry-hub?tab=repositories

