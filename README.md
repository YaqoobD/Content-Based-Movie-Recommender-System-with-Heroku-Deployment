# Content-Based-Movie-Recommender-System-with-Heroku-Deployment

This is a project centered around a content-based movie recommendation system. The system utilizes the TMDB dataset and incorporates various natural language processing techniques to facilitate movie recommendations based on the content features of films, including genres, keywords, cast, and crew.

To achieve this, two key methods, cosine similarity and vectorization, are employed. Cosine similarity is a measure that quantifies the similarity between two vectors by computing the cosine of the angle between them. In the context of this recommendation system, it is utilized to determine the similarity between the content features of different movies, allowing for the identification of movies with similar characteristics.

Additionally, vectorization is employed as a means of representing textual data in a numerical format that can be processed by machine learning algorithms. This technique transforms textual features, such as genres, keywords, cast, and crew, into numerical vectors, enabling mathematical operations and comparisons to be performed on them.

By leveraging these methods, the content-based movie recommendation system can analyze the content features of movies and provide recommendations based on similarities between their characteristics, thus assisting users in discovering movies that align with their preferences and interests.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The movie recommendation system is designed to help users discover new movies based on their preferences and movie content. It uses a content-based approach, which means it recommends movies similar to the ones the user has already liked or watched. The system analyzes movie features such as genres, keywords, cast, and crew to find similar movies and generate recommendations.

## Dataset

The dataset used in this project is the TMDB dataset. It contains information about movies, including their titles, overviews, genres, keywords, cast, and crew. The dataset is preprocessed to extract relevant features for the recommendation system.

## Technologies Used

- Python
- Pandas
- scikit-learn
- Streamlit
- Heroku

## Project Structure

The project has the following structure:

- `app.py`: The main Python script that contains the movie recommendation system implementation and the Streamlit web application.
- `tmdb_5000_movies.csv`: The movie dataset file in CSV format.
- `tmdb_5000_credits.csv`: The credits dataset file in CSV format.
- `requirements.txt`: The list of Python dependencies for the project.

## Getting Started

To get started with the movie recommendation system, follow these steps:

1. Clone the repository: `git clone <repository-url>`
2. Install the dependencies: `pip install -r requirements.txt`
3. Run the application: `streamlit run app.py`

## Usage

Once the application is running, you can access it through the provided URL. The web interface allows users to enter the name of a movie and get recommendations based on that movie. The recommendations are displayed on the screen, providing the user with similar movies to explore.

## Deployment

The movie recommendation system is deployed using Heroku. The deployment process involves the following steps:

1. Create a Heroku account and install the Heroku CLI.
2. Create a new Heroku app.
3. Connect the Heroku app to the GitHub repository.
4. Configure the necessary environment variables.
5. Deploy the application to Heroku.

The deployed application can be accessed using the Heroku app's URL.

## Demo

![image](https://github.com/YaqoobD/Content-Based-Movie-Recommender-System-with-Heroku-Deployment/assets/52135942/520eaab7-4825-4c91-93c1-4a64c7b16b1f)

![image](https://github.com/YaqoobD/Content-Based-Movie-Recommender-System-with-Heroku-Deployment/assets/52135942/242cf4cf-5ad9-4b51-b306-568d14fbc614)

![image](https://github.com/YaqoobD/Content-Based-Movie-Recommender-System-with-Heroku-Deployment/assets/52135942/a14ab9dd-738e-41d3-9051-7278f5d52a42)
