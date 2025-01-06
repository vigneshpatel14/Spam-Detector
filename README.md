# Spam Classifier

This project implements a machine learning-based spam classification system to distinguish between spam and Ham messages. The project includes a web interface for users to input text and receive classification results

## Features
* Machine Learning Model: Uses a trained model to classify messages as spam or ham.

* Web Interface: Flask-based web app with a simple and user-friendly design.

* Interactive Notebook: Includes a Jupyter notebook for data preprocessing, model training, and evaluation.

* Deployment Ready: Configured for deployment on platforms like Heroku.

## Project Structure
Spam-Classifier-main/
|-- .gitignore
|-- README.md
|-- app.py
|-- model.pkl
|-- requirements.txt
|-- spam.csv
|-- spam_classifier.ipynb
|-- vectorizer.pkl
|-- static/
|   |-- css/
|       |-- styles.css
|-- templates/
    |-- index.html

## Prerequisites

* Python 3.8 or higher
* pip (Python package manager)

## Installation

1. Clone the repository:
    git clone <repository-url>
2. Navigate to the project directory:
    cd Spam-Classifier-main
3. Install dependencies:
    pip install -r requirements.txt
4. Download necessary NLTK data:
    python -m nltk.downloader -f nltk.txt

## Usage

1. Run the Flask app:
    python app.py

2. Open your browser and navigate to:
    http://127.0.0.1:5000

3. Input text into the provided field to classify it as spam or ham.

## DataSet

The project uses a CSV file (spam.csv) containing labeled messages for training and evaluation. The dataset is preprocessed and vectorized using NLTK and scikit-learn.

## Model

The classifier is built using a machine learning model trained on vectorized text data. The model and vectorizer are saved as model.pkl and vectorizer.pkl, respectively, for reuse.

## Deployment

The project is ready for deployed on render:
https://spam-detector-a5wi.onrender.com




## Acknowledgments

* NLTK: For natural language processing tools.

* scikit-learn: For machine learning algorithms.

* Flask: For the web framework.

Feel free to contribute or raise issues to enhance the project further!