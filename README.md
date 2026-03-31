# Movie-Recommendor
Project Overview
This project is a Content-Based Movie Recommendation System built using Python, Pandas, and Scikit-learn. It suggests movies based on similarity in genres using Cosine Similarity.
⚙️ Technologies Used
Python
Pandas
Scikit-learn
CountVectorizer
Cosine Similarity
📂 Dataset
A small dataset of movies is created manually (MovieLens-style).
Each movie contains:
Title
Genres
🚀 How It Works
1. Data Preparation
Movie titles and genres are stored in a Pandas DataFrame.
2. Feature Extraction
CountVectorizer converts genre text into numerical vectors.
3. Similarity Calculation
Cosine Similarity is used to measure similarity between movies.
4. Recommendation System
Based on input movie, the system:
Finds similarity scores
Sorts them
Returns top 5 similar movies
🧠 Features
Case-insensitive movie search
Displays similarity score
Interactive mode for user input
Demo mode for quick testing
Clean tabular output
