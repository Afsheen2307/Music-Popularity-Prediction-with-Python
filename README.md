# Music-Popularity-Prediction-with-Python

Predict music track popularity using audio features and metadata with Python machine learning.

Music popularity prediction involves building machine learning models to estimate the expected popularity of songs based on their audio features and metadata. This tool is valuable for music streaming services, producers, and marketers who wish to forecast hit songs, optimize playlists, and enhance user experiences through better recommendation systems.

Overview
This project demonstrates how to train a regression model using Python to predict the popularity of music tracks. The workflow covers data preparation, exploratory data analysis, feature selection, model training, evaluation, and visualization of the results.


Dataset
The dataset contains 227 music tracks, each with:

Track and artist names

Audio features (e.g., energy, valence, danceability, loudness)

Metadata like album, release date, and popularity scores

Columns include:

Track Name

Artists

Album Name

Album ID

Track ID

Popularity (target)

Release Date

Duration (ms)

Explicit

Danceability

Energy

Key

Loudness

Mode

Speechiness

Acousticness

Instrumentalness

Liveness

Valence

Tempo

Project Structure
Spotify_data.csv — Input dataset (not included, see article for download link)

music_popularity_prediction.ipynb — Main notebook with end-to-end pipeline

README.md — Project documentation

Requirements
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn
