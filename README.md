# Emotion Detection System

## Project Description
This application is the final project for the IBM "Developing AI Applications with Python and Flask" course. It uses the Watson NLP (Natural Language Processing) library to analyze text input and identify the underlying emotions.

The system returns scores for the following emotions:
* Anger
* Disgust
* Fear
* Joy
* Sadness

It also identifies the **Dominant Emotion** based on the highest score.

## Features
* **AI Integration:** Connects to the Watson NLP Emotion Prediction service.
* **Web Interface:** Built using Flask to allow users to enter text and see results in real-time.
* **Robust Error Handling:** Specifically handles blank inputs (Status Code 400).
* **Unit Tested:** Includes a suite of tests to ensure high accuracy in detection.
* **Static Code Analysis:** Follows clean code principles as verified by Pylint.

## Project Structure
* `EmotionDetection/`: Contains the core logic and Watson API integration.
* `server.py`: The Flask server that handles web requests.
* `test_emotion_detection.py`: Unit tests for the application.

## How to Run
1. Install dependencies: `pip install requests flask`
2. Run the server: `python3 server.py`
3. Access the app: `http://localhost:5000`