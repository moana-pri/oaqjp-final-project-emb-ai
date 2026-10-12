# Emotion Detector

## Project Overview

The Emotion Detector is an AI-based application that analyzes text and identifies the emotions expressed in it using the IBM Watson Natural Language Processing (NLP) service.

## Project Objectives

- Analyze text to detect emotions.
- Identify anger, disgust, fear, joy, and sadness.
- Determine the dominant emotion in the given text.
- Develop a web application using Python and Flask.
- Implement unit testing and error handling.
- Perform static code analysis using Pylint.

## Technologies Used

- Python
- IBM Watson NLP
- Flask
- Requests
- Unittest
- Pylint

## Application Features

1. Accepts text input from the user.
2. Analyzes the input using the Watson NLP service.
3. Returns emotion scores and the dominant emotion.
4. Handles blank input and invalid responses.
5. Provides a simple web interface.

## Project Structure

- `EmotionDetection/` — Emotion detection Python package.
- `server.py` — Flask web application.
- `test_emotion_detection.py` — Unit tests.
- `README.md` — Project documentation.

## How to Run

Install the required dependencies:

```bash
python -m pip install requests flask pylint
```

Run the application:

```bash
python server.py
```

Open `http://127.0.0.1:5000` in your browser.

## Testing

Run the unit tests:

```bash
python -m unittest -v test_emotion_detection.py
```

Run static code analysis:

```bash
python -m pylint server.py
```

## Expected Outcome

The application returns emotion scores for the input text and identifies the dominant emotion when the NLP service responds successfully.
