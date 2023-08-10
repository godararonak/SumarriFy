# Summarify - Text Summarization Web App

## Description

"Summarify" is a Flask web application that utilizes the Hugging Face Transformers library to provide text summarization. Users can input text, set the desired maximum length for the summary, and the app will generate a summarized version of the input text using the BART-large-CNN model.

## Features

- Web-based interface for text summarization.
- Utilizes the Hugging Face Transformers library for NLP tasks.
- User-friendly input form for entering text and selecting summarization parameters.

## How to Use

1. Install the required libraries by running: pip install flask requests
 
2. Clone this repository and navigate to the project directory.

3. Run the Flask app: python app.py

4. 
4. Open your web browser and go to the displayed URL (usually `http://localhost:5000`).

5. Enter the text you want to summarize in the input field.

6. Adjust the "Maximum Length" slider to set the desired length of the summary.

7. Click the "Summarize" button to generate the summarized text.

## Project Structure

- `app.py`: The main Flask application code that handles routing and summarization.
- `templates/index.html`: HTML template for the web interface.
- `screenshot.png`: Screenshot of the Summarify web app in action.

## Hugging Face API

- This app uses the Hugging Face model "facebook/bart-large-cnn" for text summarization.

## Author

- Ronak Godara

## Acknowledgments

This project was created for educational purposes as a demonstration of building a text summarization web application using Flask and the Hugging Face Transformers library.



