# **Spoti-Find**
#### By Zach Evans, Carolyn Johnson, David Ma, Yonas Michael, Dejan Savic, Wendell Killette Jr.
***
## **Project Description:**
We constructed a song recommendation system to help induividuals add songs to favorite playlists. Using spotify API and user-friendly Spotipy, machine learning models were created to be the back bone to the recommendation system; a continuously learning model which gets better time. 

## Project Outline
1. Set up developer account to **access Spotify API credentials**; making API calls to retrieve necessary data 
   
   [Spotipy](https://spotipy.readthedocs.io/en/2.22.0/)
   
   [Spotify for Developers](https://developer.spotify.com/)
   
2. Take into consideration the **data most useful** for our purposes
3. Make the data API calls to **retrieve your data**
4. **Clean Data** and remove unnecessary information
5. **Split the data** into training and test sets. You'll use the training set to train your model, and the test set to evaluate its performance.
6. **Extract features from the data**. Making sure the ML models can use the features
7. **Train a machine learning model**. We choose an appropriate model for your data and goals, such as a collaborative filtering model or a content-based recommendation system. You'll then need to train the model using the training data
8. **Evaluate the model's performance**. Use the test data to evaluate the model's performance in terms of metrics such as precision, recall, and F1 score. You may need to adjust the model's hyperparameters or try a different model if the performance is not satisfactory.
9. **Use the model to make recommendations**. Once you have a trained model, you can use it to make recommendations to users based on their input.
---
Ultimately, we were able to build his song recommendation web application through Python Flask. User provides a link to a spotify playlist. The application will take the playlist and begin requesting metric data on each song in this playlist to give us an idea of the genre of music. Additionally using the machine learning algorithms, user will get returned songs that are similar based on the initial playlist.

## Limitations
The use of of free API do have rate limits which reduced the datasets we could obtain.

If you would like to learn what [Python Flask](https://pythonbasics.org/what-is-flask-python/) is. Click on the link.

![Spotify Banner](https://developer.spotify.com/assets/branding-guidelines/using-our-logo.png)
