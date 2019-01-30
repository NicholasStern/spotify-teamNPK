# Spotify Track Recommendation

This is the code base for a final project completed for Harvard's Data Science 1 course, AC 209a. 
The project team consisted of Nicholas Stern, Phoebe Wong, and Karina Huang. 
The goal of the project was to build a song recommendation system for that takes in a user playlist and returns suggested tracks.

#Data Source
The dataset we used was the Spotify Recsys Challgenge dataset obtained through Harvard University. 
Read more about the Recsys challenge <a href=https://recsys-challenge.spotify.com/>here</a>.

Note: We cleaned and stored the Million Playlist Dataset in SQL, and queried the Spotify API for metadata. 
The code for this is omitted as it either irrelevant or contains private account details.

#What's in the Repo?
* The code for the baseline, k-NN collaborative filtering model is in **baseline_model.ipynb**
* The code for the content-based filtering model is in **content_filtering.ipynb**
* The code for the k-means clustering model is in **clustering_model.ipynb** within the clustering_model directory
* The code for the ALS Matrix Factorization is in **ALS_model.ipynb**

