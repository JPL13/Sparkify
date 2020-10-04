# Sparkify

This project manipulates large and realistic datasets with Spark to engineer relevant features for predicting churn. This project uses Spark MLlib to build machine learning models with large datasets.

## Installation

The following was used for the environment setup:

- Python 3
- PySpark SQL
- PySpark ML


## Dataset

The  dataset is provided by Udacity. The data is users' activity data from Sparkify app, which is a fictional Music streaming service similar to Spotify or Apple Music. For this analysis, I am using a tiny subset (128MB) of the full dataset (12GB) to explore the data and build a machine learning model.

The dataset consists of the following numerical columns.

- ItemInSession: Number of items in session
- Length : Length of song
- Registration: User registration number
- SessionId: Session ID
- Status: Web status, three possible values : 200, 307, 404
- Ts: Timestamp of the log

The dataset consists of the following categorial columns.

- Artist: The name of the artist being listened to
- Auth: User authentication status; Logged In, Logged Out, Cancelled, Guest
- FirstName: First name of the user
- Gender: Gender of the user
- LastName: Last name of the user
- Level: Free or Paid user
- Location: Location of user
- Method: Get or Put requests (Http method)
- Page: Page Name
- Song: Title of the song being played
- UserAgent: Type of browser user is on
- UserId: UserID for user

## File Descriptions
- Sparkify.ipynb  : a jupyter notebook 
- mini_sparkify_event_data.json  : dataset used in the analysis
- README.md

## Publication

The blog post about this analysis can be found on (https://medium.com/@xiaoruyue1986/churn-prediction-with-pyspark-a75c391bf720)
