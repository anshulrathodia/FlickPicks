# FlickPicks

This project is a movie recommendation system that suggests similar movies based on a given movie title. It leverages the TMDB movies dataset and employs a content-based filtering algorithm using vectorization techniques and cosine similarity. The model is deployed using Streamlit for an interactive user experience.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Overview

The movie recommendation system suggests similar movies by analyzing the content of movies in the TMDB dataset. This is achieved through the following steps:

1. Vectorizing movie descriptions using the Bag of Words technique.
2. Calculating similarity between movies using cosine similarity.
3. Deploying the model on a Streamlit web application for user interaction.

## Features

- **Content-Based Filtering:** Recommends movies based on the similarity of their content.
- **Vectorization Technique:** Utilizes the Bag of Words model for text vectorization.
- **Cosine Similarity:** Measures the similarity between movies to provide accurate recommendations.
- **Interactive UI:** Streamlit application for easy and intuitive user interaction.

## Dataset

The TMDB movies dataset is used for this project. It includes information about various movies such as titles, overviews, genres, and more.

## Tech Stack

- **Python:** Core programming language.
- **Pandas:** For data manipulation and analysis.
- **Scikit-learn:** For vectorization and similarity calculations.
- **Streamlit:** For deploying the model as a web application.


## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```
2. Open your web browser and go to `http://localhost:8501`.
3. Enter the title of a movie to get recommendations for similar movies.

## Acknowledgements

- The TMDB dataset used in this project is provided by [The Movie Database (TMDB)](https://www.themoviedb.org/).
- This project is inspired by the need for personalized movie recommendations using content-based filtering techniques.
