# 🎵 Music Recommendation System

## 📌 Overview
The **Music Recommendation System** is a Machine Learning application designed to suggest songs to users based on their listening preferences. By analyzing the audio features and metadata of songs (such as genre, artist, and lyrics), the system identifies and recommends tracks that are similar to a user's selected song.

This project demonstrates the use of **Content-Based Filtering** and **Cosine Similarity** to build a recommendation engine.

## 🚀 Features
- **Song Selection**: Search and select a song from the dataset.
- **Smart Recommendations**: Get a list of top 5-10 songs similar to your selection.

## 🛠️ Tech Stack
- **Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-learn (CountVectorizer, Cosine Similarity)
- **Web Framework**: Streamlit (or Flask)
- **Dataset**: [tcc_ced_music.csv : https://media.geeksforgeeks.org/wp-content/uploads/20250402152109933965/tcc_ceds_music.csv]

## 📊 How It Works

1.  **Data Preprocessing**: The system cleans the dataset and extracts relevant tags (artist, genre, lyrics).
2.  **Vectorization**: Text data is converted into vectors using `CountVectorizer` or `TF-IDF`.
3.  **Similarity Calculation**: **Cosine Similarity** is used to calculate the angle between the selected song vector and all other song vectors.
4.  **Recommendation**: The songs with the smallest angles (highest similarity scores) are returned.


## 🤝 Contributing

Contributions are welcome\!

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature-branch`).
3.  Commit your changes (`git commit -m 'Add new feature'`).
4.  Push to the branch (`git push origin feature-branch`).
5.  Open a Pull Request.

##  Dataset Link
https://media.geeksforgeeks.org/wp-content/uploads/20250402152109933965/tcc_ceds_music.csv
---

