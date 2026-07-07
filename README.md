# 🎵 Spotify Song Intelligence Dashboard

An end-to-end Machine Learning project built using the Spotify Tracks dataset to explore song characteristics, perform data analysis, and predict song popularity.

This project was created as part of my AI/ML learning journey to gain hands-on experience with real-world datasets and the complete machine learning workflow.

---

## 📌 Project Overview

The project focuses on understanding how different audio features influence a song's popularity.

The workflow includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Data Preprocessing
- Machine Learning Model Training
- Model Evaluation

---

## 📊 Dataset

**Dataset:** Spotify Tracks Dataset (Kaggle)
link: https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset

It contains information about thousands of Spotify songs including:

- Popularity
- Danceability
- Energy
- Loudness
- Acousticness
- Tempo
- Valence
- Artist
- Genre
- Album Information

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis

Some of the analyses performed include:

- Correlation analysis between audio features
- Distribution of song characteristics
- Artist frequency analysis
- Pairwise feature relationships
- Tempo distribution
- Feature correlation heatmap

---

## 🤖 Machine Learning

The following regression models were trained to predict song popularity:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

---

## 📌 Key Takeaways

- Audio features alone explain only part of a song's popularity.
- Random Forest achieved the best performance among the tested models.
- Popularity is influenced by many external factors (artist reputation, marketing, playlists, trends, etc.) that are not present in the dataset.

---

## 📷 Sample Visualizations

- Correlation Heatmap
- Pairplot
- Top Artists by Number of Songs
- Tempo Distribution
---

## 📂 Repository Structure

```
spotify-song-intelligence/
│
├── spotify_song_intelligence.ipynb
├── dataset.csv
├── README.md
```

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Working with real-world datasets
- Data preprocessing and cleaning
- Exploratory Data Analysis
- Data visualization
- Feature engineering
- Building and evaluating machine learning models using scikit-learn
