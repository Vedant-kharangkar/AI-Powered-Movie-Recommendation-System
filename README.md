# 🎬 AI-Powered Movie Recommendation Engine

A modern **Movie Recommendation System** built using **Python, Streamlit, and Machine Learning** that recommends movies based on similarity using content-based filtering.

---

## 🚀 Features

- 🎥 Recommend similar movies instantly  
- 🔍 Search and explore movies  
- 🖼️ Fetch movie posters using TMDB API  
- ⚡ Fast and interactive UI using Streamlit  
- 📊 Uses TF-IDF and cosine similarity  

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- Pandas  
- Scikit-learn  
- TMDB API  
- Pickle  

---

## 📂 Project Structure
├── app.py # Streamlit frontend
├── main.py # Backend logic
├── movies_metadata.csv # Dataset
├── tfidf.pkl # TF-IDF model
├── tfidf_matrix.pkl # Similarity matrix
├── df.pkl # Processed dataframe
├── indices.pkl # Index mapping
├── requirements.txt # Dependencies
├── .env # API keys (not uploaded)


## ⚙️ Installation & Setup

### 1. Clone Repository
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
---

### 🧠 How It Works

TF-IDF converts movie data into vectors
Cosine similarity finds similar movies
Top similar movies are recommended
TMDB API fetches posters
