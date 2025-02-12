# Music Popularity Prediction

### Project Overview
The Music Popularity Prediction project aims to develop a regression model that accurately estimates the popularity score of music tracks based on their audio features. 
Accurate predictions of music popularity can help music streaming platforms better understand user preferences, 
enhance recommendation systems, and optimize playlists to boost user engagement.

### Objective
The main objective is to predict the popularity of a music track using its audio features. By identifying the most relevant features influencing popularity, the model can assist in understanding music trends and preferences.

### Dataset Description

The dataset contains various attributes related to individual music tracks, including the following key features:

- Energy: A measure of intensity and activity in the track.
- Valence: Indicates the musical positiveness conveyed by a track.
- Danceability: Describes how suitable a track is for dancing.
- Loudness: Overall loudness of a track in decibels (dB).
- Acousticness: Confidence measure of whether the track is acoustic.
- Tempo: The speed or pace of a piece, measured in beats per minute (BPM).
- Speechiness: Measures the presence of spoken words in a track.
- Liveness: Detects the presence of an audience in the recording.
- Popularity: The target variable indicating the popularity score of the track.
- Feature Importance

### The following are the most influential features identified for predicting music popularity:

- Energy: 17.532590
- Loudness: 14.171994
- Danceability: 13.737252
- Liveness: 12.254913
- Speechiness: 11.469206
- Tempo: 11.287009
- Explicit: 9.996894
- Instrumentalness: 9.550142

### Approach

**Data Preprocessing:**

1) Handling missing values and outliers.
2) Feature scaling and encoding categorical variables.
3) Exploratory Data Analysis (EDA):
4) Analyzing distributions and correlations between features.
5) Identifying influential features using feature importance metrics.

### Model Building:

1) Random Forest Regressor was used as the primary model.
2) Hyperparameter tuning to optimize model performance.

### Model Evaluation:

Evaluating model performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).

### Results

The model's performance was evaluated using the identified features, and Random Forest Regressor was selected for its accuracy in predicting the popularity score. 
The top contributing features were Energy, Loudness, and Danceability, highlighting the importance of track intensity and rhythm in determining popularity.

### Conclusion
This project successfully developed a predictive model to estimate music popularity using audio features. 
The insights gained can be leveraged by music streaming platforms to enhance recommendation systems, curate personalized playlists, and better understand user preferences.
