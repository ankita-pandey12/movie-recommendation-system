# 🎬 Content-Based Movie Recommendation System

This project is a content-based movie recommendation system that suggests similar movies using TF-IDF vectorization and cosine similarity.

## 🔧 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn

## 🧠 How It Works
1. Movie metadata (genres, keywords, cast, director, overview) is combined.
2. Text is converted into vectors using TF-IDF.
3. Cosine similarity is computed between movies.
4. Top 5 most similar movies are recommended.

## ❓ Why No Accuracy?
This is not a supervised learning problem. Hence accuracy metrics are not applicable.

## 🚀 Example
Input: Avatar  
Output: John Carter, Guardians of the Galaxy, Star Trek
