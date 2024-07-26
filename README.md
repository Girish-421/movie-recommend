# Prerequisits

Use command - pip install streamlit //to install dependencies streamlit run app.py //to run the streamlit script

Lastly export your own similarity.pkl file and use it to run the final model

# Movie-Recommender-System
This project implements a movie recommendation system using content-based filtering techniques. It utilizes the movie dataset containing information about movie titles, overviews, and genres to suggest similar movies to users based on their preferences.

## Dataset
The dataset used in this project contains movie information including:

title: The title of the movie.
overview: A brief description of the movie.
genre: The genre(s) associated with the movie.
## Implementation Details
The dataset is loaded using pandas and preprocessed to extract relevant features such as title, overview, genre, and synopsis (a combination of overview and genre).
CountVectorizer from scikit-learn is used to convert the text data into a matrix of token counts.
Cosine similarity is computed between the movie synopses to find similarities between movies.
A recommend function is implemented to suggest similar movies based on a given movie title.
