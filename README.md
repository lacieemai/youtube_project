# VideoTags Predictor
The goal of this project was to predict video tags based on the subtitles text. Data for the project was obtained by interaction with the Google API, after that it was cleansed mostly using regular expressions; the TF-IDF analysis was performed as well.
Finally, the text data was vectorized using the word2vec algorithm, and an SVR model was trained as a means of tags prediction.
