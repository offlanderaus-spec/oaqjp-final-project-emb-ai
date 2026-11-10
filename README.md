# Final Project

An AI-based web application built with Python and Flask that uses Watson NLP emotion detection to analyze customer emotions from provided statements.

## Project Description

This project demonstrates an end-to-end web deployment of an emotion detection application. It includes:
- Packaging the core emotion analysis logic (`EmotionDetection`) using Watson NLP.
- Unit testing with Python's built-in `unittest` library.
- Deploying the application locally via a Flask server (`server.py`).
- Robust error handling for blank/invalid queries.
- Clean code architecture verified through static analysis (`pylint`).

## Features

- **Watson NLP Integration:** Analyzes input statements and scores emotions across anger, disgust, fear, joy, and sadness.
- **Dominant Emotion Identification:** Automatically computes and identifies the predominant emotional state.
- **Error Handling:** Returns clear feedback (`Invalid text! Please try again!`) on blank inputs or invalid requests.
- **Web Interface:** Interactive web UI hosted at `localhost:5000` via Flask.

## Getting Started

### Prerequisites

Ensure the following dependencies are installed:
```bash
pip install flask requests pylint
