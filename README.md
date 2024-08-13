# Sentiment-Based Product Recommendation System

## Project Overview

This project is a sentiment-based product recommendation system built for an e-commerce company named 'Ebuss'. The goal is to improve product recommendations by analyzing user reviews and ratings. The system recommends the top products for users based on their past interactions and sentiments.

## Features

- **Sentiment Analysis:** Uses machine learning models to determine the sentiment of user reviews.
- **Recommendation System:** Recommends 20 products based on user history, and filters the top 5 products based on sentiment analysis.
- **Web Interface:** Deployed using Flask, allowing users to interact with the recommendation system through a web application.

## Tech Stack

- **Backend:** Flask, Python
- **Frontend:** HTML, Jinja2
- **Machine Learning:** Scikit-learn, NLTK, SpaCy
- **Deployment:** Heroku

## Installation

### Prerequisites

- Python 3.8 or higher
- pip (Python package installer)

### Steps

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sandilyaap/sentinement-based-prodcut-recommedation.git
    cd sentiment-product-recommendation
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Download the SpaCy language model:**

    ```bash
    python -m spacy download en_core_web_sm
    ```

4. **Run the application:**

    ```bash
    python app.py
    ```

5. **Visit the application:**
   
   Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

1. Enter your username in the input field.
2. Click the "Submit" button to get product recommendations.
3. The system will display the top 5 recommended products based on your past reviews and sentiments.

## Project Structure

```plaintext
├── app.py              # Flask application entry point
├── model.py            # Machine learning models for sentiment analysis and recommendation
├── requirements.txt    # Python dependencies
├── Procfile            # Heroku process file
├── templates/          # HTML templates
│   └── index.html      # Main interface template
├── static/             # Static files (CSS, JS, images)
│   └── style.css       # Stylesheet
└── README.md           # Project documentation


## Deployment
Deploying to Heroku
1. Login to Heroku:  
heroku login
2.Create a new Heroku app: 
heroku create Sentiment Based Product recommendation system
3. Deploy the app:
git push heroku main
4.Open the app in your browser:
heroku open




