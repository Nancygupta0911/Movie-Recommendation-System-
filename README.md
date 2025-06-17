
# 🎬 Movie Recommendation System

A content-based movie recommender system built using **TF-IDF vectorization** and **cosine similarity**, with a clean **Streamlit web interface** for real-time movie suggestions.

## 📌 Features

- Recommend top 5 movies based on the content (plot/overview).
- Uses **NLP techniques** like TF-IDF vectorization.
- Computes movie similarity using **cosine similarity**.
- Built with **Python** and deployed using **Streamlit**.
- Simple and fast UI for real-time recommendations.

---

## 🧠 How It Works

1. Loads movie metadata (title, overview).
2. Converts text data to numerical form using **TF-IDF**.
3. Calculates **cosine similarity** between movies.
4. Based on the selected movie, retrieves top N most similar titles.

---

## 📁 Dataset

- Source: [TMDB 5000 Movie Dataset on Kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Format: CSV files with information about movies including title, genres, keywords, and overview.

---

## 🛠 Tech Stack

| Tool/Library     | Usage                          |
|------------------|--------------------------------|
| Python           | Core programming language      |
| Pandas, NumPy    | Data handling and preprocessing|
| Scikit-learn     | TF-IDF, cosine similarity      |
| Streamlit        | Frontend web interface         |

---



