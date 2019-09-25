# Spotify Genre Detection
----
In this project, I have decided to implement a genre classification system using Spotify's preselected features. The dataset for this project was found originally on [Kaggle](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db), and includes many different features and genre tags, including approximately 10,000 tracks over 26 total genres. The dataset can be found in this project held within the [`data`](./data/) folder.

## Implementation
For this project I chose to use Python, my most familiar language and a common choice for data analysis tasks. The [main notebook file](index.ipynb) contains an interactive interface to explore the analysis of this dataset, the possible classification implementations, and general data information. For the underlying machine-learning implementations, I chose to use the industry standard `sklearn`.

## The Features:
Spotify lists the following features in the dataset:
- artist_name
- track_name
- track_id
- popularity
- acousticness
- danceability
- duration_ms
- energy
- instrumentalness
- key
- liveness
- loudness
- mode
- speechiness
- tempo
- time_signature
- valence
And the dataset has the following as target labelings:
- genre