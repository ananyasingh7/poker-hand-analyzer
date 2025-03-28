# Poker Hand Analyzer and Strategy Predictor

## Overview
This project is a Python-based web application that analyzes poker hands from the UCI Poker Hand Dataset, predicts hand rankings (e.g., "Pair," "Flush"), and aims to suggest strategies using machine learning. Built with Flask, Scikit-Learn, Keras, TensorFlow, and multithreading, it’s a learning tool to master Python and a showcase of data science and web development skills.

### Goals
- Master Python through practical application.
- Build a cool poker ML project with a web interface.
- Learn data structures, algorithms, Flask, multithreading, and ML (Scikit-Learn, Keras, TensorFlow).

### Key Features
- **Data Processing**: Parse UCI poker hands and extract features (suits, ranks).
- **Machine Learning**: Predict hand rankings or simulate strategies with ML models.
- **Web Interface**: Flask app for users to input hands and view predictions.
- **Multithreading**: Handle concurrent requests efficiently.
- **Visualization**: Display poker stats (e.g., hand type distributions).

---

## Project Plan

### 1. Data Exploration and Preprocessing
- Load and clean UCI Poker Hand Dataset (training and testing files).
- Extract features: suits and ranks for 5-card hands.
- Use pandas for structured data.

### 2. Hand Evaluation and Feature Engineering
- Build a hand strength evaluator (e.g., pair, flush).
- Simulate basic metrics (e.g., hand probability).
- Prepare ML features (suit/rank patterns).

### 3. Machine Learning Models
- Scikit-Learn: Random Forest for hand ranking prediction.
- Keras/TensorFlow: Neural network for deeper patterns.
- Train and evaluate models.

### 4. Flask Web Application
- Create routes (e.g., `/analyze`) and HTML forms.
- Integrate ML models for real-time predictions.

### 5. Multithreading
- Use Python’s `threading` for concurrent tasks (e.g., multiple users).
- Run background processes like model retraining.

### 6. Data Visualization
- Plot insights (e.g., hand type frequencies) with Matplotlib/Seaborn.
- Embed visuals in Flask.

### 7. Stretch Goals
- Simulate betting actions (e.g., with `pypokerengine`).
- Add a database (SQLite) for persistence.
- Develop a real-time poker AI.

---

## Learning Outcomes
- **Python**: File I/O, pandas, Flask, threading.
- **Data Structures**: Custom classes for hands.
- **Algorithms**: Hand ranking, probability calculations.
- **ML**: Classification, neural networks.
- **Web Dev**: Full-stack Flask app.

---

## Getting Started
1. **Milestone 1**: Parse UCI data and print stats (e.g., hand type counts).
2. **Milestone 2**: Build and test a hand evaluator.
3. **Milestone 3**: Train a basic ML model.
4. **Milestone 4**: Launch a Flask app with predictions.
5. **Milestone 5**: Add multithreading and visuals.

---

## Requirements
- Python 3.x
- Libraries: `pandas`, `scikit-learn`, `tensorflow`, `keras`, `flask`, `matplotlib`, `seaborn`
- Dataset: UCI Poker Hand Dataset (https://archive.ics.uci.edu/dataset/158/poker+hand)

---

## Challenges
- Handling imbalanced hand types (e.g., rare "Royal Flush").
- Extending static hands to strategic predictions.
- Optimizing ML performance.

---

## Why This Project?
A practical, scalable way to learn Python while building an impressive poker ML web app—perfect for skill-building and portfolio development.

---

*Created on March 27, 2025*