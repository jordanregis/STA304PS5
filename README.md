# Overview
This repository contains the code used for analyzing the Spotify Web API dataset. It was created by Timothy Regis. The purpose of this is to create a report that summarises the results of the statistical model used in the paper. This led to the discovery of; danceability, energy, speechiness, and valence, all as significant predictors of a song's popularity, with danceability and energy showing positive correlations and the latter two showing negative correlations. 

The sections of this repo are: inputs, outputs, and scripts.

Inputs contain the raw data used for the analysis. 
The primary dataset used for this analysis was provided by a user on Kaggle: https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks. To download the dataset used for this paper; go to the link and download the "data.csv" file under the Data Explorer section, next, extract the csv file and place this file into your working directory.

Outputs contain both the raw RMarkdown file of the paper, as well as the pdf copy. 
These Are:
- SpotifyPaper.rmd
- SpotifyPaper.pdf

Lastly, Scripts contain the R code used that took in the inputs and produced the outputs.
This is:
- SpotifyAppendix.rmd
