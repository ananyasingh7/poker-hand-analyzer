# Poker Hand Analyzer and Strategy Predictor

## Overview
This project is a Python-based web application that analyzes poker hands from the 2023 WSOP dataset (via Papers With Code), predicts outcomes, and suggests optimal actions using machine learning. Built with Flask, Scikit-Learn, Keras, TensorFlow, and multithreading, it serves as both a learning tool to master Python and a showcase of data science and web development skills.

### Goals
- Master Python through practical application.
- Build a cool poker ML project with a web interface.
- Learn data structures, algorithms, Flask, multithreading, and ML (Scikit-Learn, Keras, TensorFlow).

### Key Features
- **Data Processing**: Parse WSOP hand histories and extract features (cards, actions, positions).
- **Machine Learning**: Predict winners or suggest actions using ML models.
- **Web Interface**: Flask app for users to input hands and view predictions.
- **Multithreading**: Handle concurrent requests efficiently.
- **Visualization**: Display poker stats (e.g., hand strength distributions).

---

## Project Plan

### 1. Data Exploration and Preprocessing
- Load and clean WSOP hand histories.
- Extract features: actions, cards, stack sizes.
- Use pandas for structured data.

### 2. Hand Evaluation and Feature Engineering
- Build a hand strength evaluator (e.g., pair, flush).
- Compute metrics like pot odds or equity.
- Prepare ML features (betting patterns, position).

### 3. Machine Learning Models
- Scikit-Learn: Random Forest for winner prediction.
- Keras/TensorFlow: Neural network for complex patterns.
- Train and evaluate models.

### 4. Flask Web Application
- Create routes (e.g., `/analyze`) and HTML forms.
- Integrate ML models for real-time predictions.

### 5. Multithreading
- Use Python’s `threading` for concurrent tasks (e.g., multiple users).
- Run background processes like model retraining.

### 6. Data Visualization
- Plot insights (e.g., win probabilities) with Matplotlib/Seaborn.
- Embed visuals in Flask.

### 7. Stretch Goals
- Simulate “what-if” scenarios (Monte Carlo).
- Add a database (SQLite) for persistence.
- Develop a real-time poker AI.

---

## Learning Outcomes
- **Python**: File I/O, pandas, Flask, threading.
- **Data Structures**: Custom classes for hands/game states.
- **Algorithms**: Hand ranking, equity calculations.
- **ML**: Classification, neural networks.
- **Web Dev**: Full-stack Flask app.

---

## Getting Started
1. **Milestone 1**: Parse WSOP data and print stats.
2. **Milestone 2**: Build and test a hand evaluator.
3. **Milestone 3**: Train a basic ML model.
4. **Milestone 4**: Launch a Flask app with predictions.
5. **Milestone 5**: Add multithreading and visuals.

---

## Requirements
- Python 3.x
- Libraries: `pandas`, `scikit-learn`, `tensorflow`, `keras`, `flask`, `matplotlib`, `seaborn`
- Dataset: WSOP hand histories (Papers With Code)

---

## Challenges
- Handling messy poker data formats.
- Modeling hidden info (e.g., folded cards).
- Optimizing ML performance.

---

## Why This Project?
A practical, scalable way to learn Python while building an impressive poker ML web app—perfect for skill-building and portfolio development.

---

*Created on March 27, 2025*