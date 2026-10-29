# Emotion Detector — IBM Full Stack AI Final Project

An AI-powered web application that detects emotions in text using the **IBM Watson NLP Library**. Built with Python and Flask as the final project for the IBM AI Applications with Python and Flask course.

## Project Overview

This application analyzes input text and returns emotion scores for five emotions:
- 😠 **Anger**
- 🤢 **Disgust**
- 😨 **Fear**
- 😊 **Joy**
- 😢 **Sadness**

It also identifies the **dominant emotion** in the text.

## Project Structure

```
EmotionDetector/
├── EmotionDetection/
│   ├── __init__.py          # Package initializer
│   └── emotion_detection.py # Core Watson NLP emotion function
├── templates/
│   └── index.html           # Web UI
├── static/                  # Static assets
├── server.py                # Flask web server
├── test_emotion_detection.py# Unit tests
└── README.md                # This file
```

## Tasks Completed

| Task | Description |
|------|-------------|
| Task 1 | Cloned and set up the project repository |
| Task 2 | Created emotion detection using Watson NLP |
| Task 3 | Formatted output with dominant emotion |
| Task 4 | Packaged as `EmotionDetection` module |
| Task 5 | Unit tests for all 5 emotions |
| Task 6 | Flask web deployment |
| Task 7 | Error handling for blank input (status 400) |
| Task 8 | Pylint static code analysis — perfect score |

## Running the Application

```bash
pip install flask requests pylint
python server.py
```
Visit: http://localhost:5001

## Running Unit Tests

```bash
python -m pytest test_emotion_detection.py -v
```

## Static Code Analysis

```bash
pylint server.py
```
