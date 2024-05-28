Sentiment Analysis YouTube Comment App

This repository contains a Flask web application that performs sentiment analysis on YouTube comments. The application cleans and processes the comments, checks for special characters and spelling errors, and predicts the sentiment using a pre-trained machine learning model.

Features
1. Cleans and processes input comments by removing unnecessary characters and stop words.
2. Checks for the presence of special characters and spelling errors.
3. Uses a voting model to predict the sentiment of the comments.
4. Provides a user-friendly web interface for entering comments and viewing predictions.

Requirements
1. Flask
2. NLTK
3. SpellChecker
4. Pickle
5. css or Bootstrap (for front-end styling)

Installation
1. Install the required libraries and python packages used.
2. Place the pre-trained model('youtube_model7.pkl) in the root directory of the project.

Usage
1. "Please click on the following link to access our deployed application: https://ml-youtube.onrender.com/
2. Once the page loads, feel free to write the comment that you want in the designated input field. After entering your comment, you can submit it by clicking the  button. The result of the sentiment analysis will be shown on the screen shortly after submitting your comment. Thank you for using our application!


Application Structure
1. app.py: The main Flask application file.
2. templates/index.html: The HTML template for the web interface.
3. static/: Directory for static files like images and CSS.
