# HelloHarmony: Emotion-Based Music Recommendation System Using Machine Learning and Artificial Intelligence

## By Sophia Mares, Manahil Nasim
### University of San Diego

## Project Overview
In this project, we aim to solve the problem of music recommendations for online music streaming services. The goal is to help users discover new music in a stress-free manner by creating a recommendation system that suggests music based on user preferences, listening habits, and trends.

## Dataset
Two datasets are used in this project, an Emotion Detection Dataset and a Spotify Music Dataset.
## Emotion Detection Features:
Description: The dataset consists of 35,685 grayscale images of various faces, each one is labeled with seven emotions: happiness, sadness, anger, surprise, disgust, and fear. 
- Dataset Source: Kaggle Emotion Detection Dataset : https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer/data
- Image Size: 48x48 pixels
- Color Scale: Grayscale
- Number of Examples: 35,685
- Emotion Labels: Happiness, Neutral, Sadness, Anger, Surprise, Disgust, Fear
- Data Split: Training and Test sets
## Features
Image Data:
- Resolution: 48x48 pixels, grayscale.
- Number of Images: 35,685 images.
- Emotion Categories: Each image is labeled with one of the following seven emotions:
- Happiness
-Neutral
- Sadness
- Anger
- Surprise
- Disgust
- Fear
Data Structure:
- Training Set: 28,709 images.
- Test Set: 7,176 images.
- Format: Each image is represented as a 48x48 pixel matrix, with pixel values ranging from 0 to 255.

## Spotify Music Dataset: 
Description: This dataset consists of metadata for over 500,000 songs on Spotify's platform, which includes various features such as danceability, energy, valence, tempo, and more. 
Dataset Source: Kaggle Spotify Music Dataset: https://www.kaggle.com/datasets/musicblogger/spotify-music-data-to-identify-the-moods/data
Number of Songs: Over 500,000 tracks
Features Included: Track name, artist, album, danceability, energy, key, loudness, mode, acousticness, instrumentalness, liveness, valence, tempo, duration, time signature, and popularity.
## Features
## Track Metadata:
- Track Name: The title of the song.
- Artist: The name of the artist or band.
- Album: The album to which the song belongs.
Audio Features:
- Danceability: A measure of how suitable a track is for dancing. Values range from 0.0 to 1.0.
- Energy: A measure of intensity and activity. Higher values indicate more energetic tracks.
- Valence: Describes the musical positiveness conveyed by a track. Higher valence means more positive-sounding tracks.
- Tempo: The speed or pace of the track, measured in beats per minute (BPM).
- Acousticness: A measure of whether a track is acoustic. Higher values indicate more acoustic content.
- Instrumentalness: Predicts whether a track contains no vocals. Higher values mean less vocal content.
- Liveness: Detects the presence of an audience in the recording. Higher values indicate a live performance.
- Loudness: The overall loudness of a track in decibels (dB).
- Mode: Indicates the modality (major or minor) of a track, where major is 1 and minor is 0.
- Key: The key of the track (e.g., C, D, E).
- Time Signature: The musical time signature of the track (e.g., 4/4, 3/4).
Popularity:
- Popularity Score: This is a metric that represents the popularity of a track, with higher values indicating a songs higher popularity.
Categorization:
- Mood Classification: Songs are also grouped into various mood categories based on their valence, energy, and tempo values, which are then further used to match the detected emotion from the Emotion Detection Dataset.

## How to Use
1. Clone the repository.
2. Install the necessary libraries using `requirements.txt`.
3. Run the EDA and feature engineering scripts to preprocess the data.
4. Use the recommendation system scripts to generate music recommendations based on user preferences.
