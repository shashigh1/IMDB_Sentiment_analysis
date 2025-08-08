🎬 IMDB Movie Review Sentiment Analysis
A deployed web application that performs sentiment analysis on movie reviews using a Recurrent Neural Network (RNN) built with Keras and TensorFlow, and deployed using Streamlit.

🔗 Live Demo: https://imdbsentimentanalysis-skk.streamlit.app/

📌 Overview
This project classifies movie reviews as either positive or negative using a deep learning model trained on the IMDB dataset. It is designed for real-time prediction through a user-friendly web interface.

Users can input any movie review, and the app returns the sentiment classification along with a prediction confidence score.

🧠 Model Summary
The model is built using a simple Recurrent Neural Network (RNN) architecture:

Embedding layer for word representation

SimpleRNN layer with ReLU activation

Dense output layer with sigmoid activation

The model processes reviews with a maximum length of 500 tokens and uses the 10,000 most frequent words in the dataset.

🏋️ Training Details
Dataset: IMDB reviews dataset (binary sentiment classification)

Training: 10 epochs with a batch size of 64

Validation Split: 30%

Early Stopping: Included to prevent overfitting

The model was trained using RMSprop optimizer and binary crossentropy loss.

🌐 Web Application Features
Built using Streamlit for ease of deployment and interaction

Accepts custom review text input

Preprocesses text using the IMDB word index

Displays predicted sentiment as Positive or Negative

Outputs prediction confidence score
