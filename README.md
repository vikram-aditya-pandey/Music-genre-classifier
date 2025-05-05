# 🎶 Music Recommendation System

This project is a basic **music recommendation system** implemented in Python. It analyzes song features such as **tempo**, **energy**, **valence**, and **genre** to suggest similar songs based on a selected track using content-based filtering techniques.

---

## 🧠 Overview

The system reads a dataset of songs with various audio features and recommends tracks that are most similar to the user's input song using **cosine similarity**.

---

## 🧰 Features

* 📚 Loads and processes a music dataset (`music.csv`)
* 🎼 Recommends similar songs based on audio features
* 🧠 Uses `scikit-learn`'s `cosine_similarity` for feature comparison
* 💡 Simple, interpretable content-based filtering

---

## 📁 Dataset

The dataset (`music.csv`) should contain columns like:

```
['name', 'artists', 'genre', 'danceability', 'energy', 'loudness', 'speechiness', 'acousticness', 'instrumentalness', 'liveness', 'valence', 'tempo']
```


## 🔮 Future Enhancements

* Add collaborative filtering or hybrid models
* Integrate with Spotify API for real-time data
* Build a web interface using Streamlit or Flask

