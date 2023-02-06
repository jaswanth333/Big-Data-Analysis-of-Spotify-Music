# ECE552 Final Project: Big-Data-Analysis-of-Spotify-Music

<center>
<strong>Predicting Optimal Bike Demand based on Seoul Bike Sharing Data</strong><br><br><br>

Abhishek Godavarti

Bhargav Teja Jakku

Jaswanth Kumar Kunku

<br><br>

ECE-552: Big Data Analysis

George Mason University

December 13, 2022

<br><br><strong>Under the guidance of:</strong>

Dr. Erton Boci
</center>

---


## Project Goals
- **Identify and discover patterns in the data using relevant spark big data libraries available in python and accurately forecast the classification of highly popular songs from the less popular ones.


## Data Set
The dataset for this project was downloaded from Kaggle .It consists of following 25 attributes:

- id: The unique identifier for the track.
- Track name: Name of the song
- Track popularity: A measure between 0 -100 where 0 indicates low popularity and 100 indicates high popularity.
- duration_ms: The duration of the track in milliseconds.
- Explicit: Explicit describes whether a song is suitable for age below 18 or not. 0 indicates suitable,1 indicates not suitable.
- Artist Id: The unique identifier for the artist.
- Artist Name: Name of the person who played the song
- Release date: The year and date on which the song was released.
- Danceability: Danceability describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
- Energy: Energy is a measure from 0.0 to 1.0 and represents a perceptual measure of intensity and activity.
- Key: The key the track is in. Integers map to pitches using standard Pitch Class notation. E.g. 0 = C, 1 = C♯/D♭, 2 = D, and so on. If no key was detected, the value is -1.
- Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks.
- Mode: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived. Major is represented by 1 and minor is 0.
- Speechiness: Speechiness detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value. Values above 0.66 describe tracks that are probably made entirely of spoken words. Values between 0.33 and 0.66 describe tracks that may contain both music and speech, either in sections or layered, including such cases as rap music. Values below 0.33 most likely represent music and other non-speech-like tracks.
- Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic
- Instrumentalness: Predicts whether a track contains no vocals. "Ooh" and "aah" sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly "vocal".
- Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live. A value above 0.8 provides strong likelihood that the track is live.
- Tempo: The overall estimated tempo of a track in beats per minute (BPM). In musical terminology, tempo is the speed or pace of a given piece and derives directly from the average beat duration.
- Valence: A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
- Time Signature: An estimated time signature. The time signature (meter) is a notational convention to specify how many beats are in each bar (or measure).
- Genre: Type of the genre the song belongs to. For example, Pop, Latin etc.
- Artist Popularity: Measusre between 0 to 100
• Followers: Number of followers

## Project Methodology
-   Data Exploration, Data Cleaning, and Pre-Processing
-   Predictive Models
    -   Logistic Regression
    -   Decision Tree
    -   Random Forest
