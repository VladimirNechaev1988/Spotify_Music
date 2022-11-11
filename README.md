# Spotify Music Analysis

This notebook contains an analysis of a Spotify data set that contains the top songs from 2010 to 2019 as measured by Billboard. The data contains 14 columns which show different characteristics of the songs.

## Data set

The data set used is uploaded to this folder and was originally taken from [this page](https://www.kaggle.com/datasets/leonardopena/top-spotify-songs-from-20102019-by-year)

|    | Variable   | Explanation                                                |
|---:|:-----------|:-----------------------------------------------------------|
|  0 | title      | The title of the song                                      |
|  1 | artist     | The artist of the song                                     |
|  2 | top genre  | The genre of the song                                      |
|  3 | year       | The year the song was in the Billboard                     |
|  4 | bpm        | Beats per minute: the tempo of the song                    |
|  5 | nrgy       | The energy of the song: higher values mean more energetic (fast, loud)  |
|  6 | dnce       | The danceability of the song: higher values mean it's easier to dance to  |
|  7 | dB         | Decibel: the loudness of the song  |
|  8 | live       | Liveness: likeliness the song was recorded with a live audience  |
|  9 | val        | Valence: higher values mean a more positive sound (happy, cheerful) |
| 10 | dur        | The duration of the song |
| 11 | acous      | The acousticness of the song: likeliness the song is acoustic|
| 12 | spch       | Speechines: higher values mean more spoken words |
| 13 | pop        | Popularity: higher values mean more popular|

## Objectives

The notebook has a goal of performing a descriptive analysis and visualizations of the Spotify data set and covering the following topics:

* Decide which artists are the most popular
* Discuss the criteria for the popularity
* See what year has the highest popularity and why
* Analyze what genre people like the most
* Demonstrate the role of outliers

## Tools used

This Jupyter notebook analysis is done in Python with the help of visualization libraries Seaborn and Matplotlib.
