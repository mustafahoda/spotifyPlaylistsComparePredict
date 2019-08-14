# spotifyPlaylistsComparePredict
an iPython Notebook that compares two Spotify Playlists and classifies a song into either of those playlists.

# Inspiration
[You can find a nice writeup on this code on my Medium](https://medium.com/datadriveninvestor/are-my-spotify-playlists-any-good-a-data-approach-9f24aa0cf28c)


The inpspiration behind this project was my initial introduction to MachineLearning. I learned that Spotify has this beautiful API
that allows you to get song features like:
- Loudness
- Tempo
- Danceability
- and more!

The goal of this project was to determine if any of the Spotify Playlist I have made myself were any good. The ML behind this is
super simple: using the KNN Algorithm.

# What does this program do?

This Jupyter Notebook takes two input playlists and does the following:
    1. Identifies most dissimilar features between two playlists
    2. Plots the tracks in each playlist respective to their top two dissimilar features
    3. Use KNN Algorithm to predict which playlist a song may belong to
    
- all inputs for playlists and tracks ... enter without the prefix. So for example, enter: *"5Sf3GyLEAzJXxZ5mbCPXTu"*. DO NOT ENTER: *"spotify:track:5Sf3GyLEAzJXxZ5mbCPXTu"*
