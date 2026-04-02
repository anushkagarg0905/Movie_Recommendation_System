# 🎬  Movie_Recommendation_System
Designed an end-to-end ML pipeline for movie recommendation including preprocessing, feature engineering and similarity-based retrieval. Deployed a user-interactive system with real-time recommendations and visual analytics using Streamlit.
---

## 🚀 Features

- 🔎 Search movies and get similar recommendations
- 🎭 Filter movies by genre
- 🖼️ Poster-based UI using TMDB API
- 🎯 Click on any movie to get recommendations
- 🔥 Trending movies section
- 📊 Basic analytics and insights

---

## 🧠 How It Works

The system uses **Content-Based Filtering**:
- Movie genres are converted into vectors using **TF-IDF**
- Similarity between movies is calculated using **Cosine Similarity**
- Movies with highest similarity scores are recommended

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn  
- **ML Techniques:** TF-IDF, Cosine Similarity  
- **Frontend:** Streamlit  
- **API:** TMDB (for movie posters)  
- **Deployment:** Colab + Ngrok  

---

## 📊 Dataset

- MovieLens
