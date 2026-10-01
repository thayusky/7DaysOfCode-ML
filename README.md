# 🎧 #7DaysOfCode – Machine Learning

My solutions to the **#7DaysOfCode Machine Learning challenge** by Alura. Over seven days, I am exploring a dataset of Spotify tracks and building Machine Learning models to predict song popularity.

## 📊 Dataset

[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) from Kaggle, containing around 114,000 songs across 114 genres, with musical features such as danceability, energy, loudness, acousticness and tempo.

## 🛠️ Tools

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## 📅 Progress

| Day | Topic | Status |
|---|---|---|
| 1 | Exploratory Data Analysis | ✅ |
| 2 | Coming soon | ⏳ |
| 3 | Coming soon | ⏳ |
| 4 | Coming soon | ⏳ |
| 5 | Coming soon | ⏳ |
| 6 | Coming soon | ⏳ |
| 7 | Coming soon | ⏳ |

## 🔍 Day 1: Exploratory Data Analysis

**What I did:**
- Loaded and cleaned the data (removed an extra index column, missing values and duplicated tracks)
- Found the most popular songs, genres and artists
- Created visualisations: histogram, bar charts, boxplot, scatter plot and correlation heatmap
- Investigated why so many songs have zero popularity

**Key findings:**
- 🎵 The same song can appear several times in the dataset because it can belong to more than one genre.
- 🎤 Having the most songs in the dataset does not mean being the most popular artist: the way the data was collected strongly influences the results.
- 🔞 Explicit songs tend to be more popular, although this does not mean that being explicit causes popularity.
- 🔥 Energy and loudness are strongly correlated (0.76), whereas energy and acousticness are strongly negatively correlated (-0.73).
- 📉 Popularity has a very weak correlation with every individual feature, so a model will need to combine several features.
- 🕵️ 57.7% of zero-popularity songs have another version with the same name and artists (compared with 9.5% of other songs), suggesting many are re-releases or compilations.

## ▶️ How to run

1. Open the notebook in this repository.
2. Click the **"Open in Colab"** button at the top.
3. Go to **Runtime → Run all**.

## 👩‍💻 Author

Made by [Thayusky](https://github.com/thayusky) as part of the #7DaysOfCode challenge.
