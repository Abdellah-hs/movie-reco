# 🎬 Movie Recommender System using Machine Learning

This is a **Streamlit web application** that recommends movies based on user interests. It uses **content-based filtering** with **cosine similarity** to suggest similar movies. This project demonstrates how machine learning can help people make decisions in a world full of options.

## 🧠 Why Recommendation Systems Matter

In today's fast-paced world, people are overwhelmed by choices and short on time. Recommendation systems solve this problem by providing **personalized suggestions** based on user preferences, saving both time and effort.

They are powered by **AI-based algorithms** that analyze user profiles, browsing history, and behavior patterns to find relevant content.

---

## 📚 Types of Recommendation Systems

### 1. Content-Based Filtering

- Uses item features (e.g., genre, actors, singers) to recommend similar items.
- Example platforms: **YouTube**, **Spotify**.
- Relies on user’s past interactions.
- Drawback: may lead to **over-specialization**, where users see only similar items.

### 2. Collaborative Filtering

- Based on user-item interactions (ratings, comments).
- Forms clusters of users with similar preferences.
- Recommends items that similar users liked.
- Challenges:
  - Computationally heavy (large user-item matrix).
  - **Cold-start problem** for new users/items.
  - **Popularity bias** (only famous items get recommended).

### 3. Hybrid Filtering

- Combines content-based and collaborative methods.
- Reduces limitations of both.
- Modern platforms (like Netflix) often use this approach.
- Can integrate **deep learning**, **embeddings**, and **word2vec**.

---

## 📂 Dataset Used

- [TMDB Movie Metadata (Kaggle)](https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)

---

## 🔍 Core Concept: Cosine Similarity

Cosine similarity is used to measure how similar two items are by calculating the cosine of the angle between their feature vectors.

### Properties:

- Output ranges between `0` and `1`:
  - `1` means completely similar.
  - `0` means completely different.
- Useful in text and recommendation systems.

📘 Learn more: [Cosine Similarity – LearnDataSci](https://www.learndatasci.com/glossary/cosine-similarity/)



## 🛠️ How to Run the Project Locally

### Step 1: Clone the repository

```bash
streamlit run app.py

