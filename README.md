# 🎬 Movie Recommendation System using Machine Learning

## Day 18/50 – 50 Days 50 Data Science Projects Challenge
Building real-world Machine Learning projects to master Data Science & secure a top Data Scientist role.

## Project Overview

This project is a Content-Based Movie Recommendation System built using Python and Machine Learning.

The system recommends movies similar to a user-selected movie based on features like:

Genres

Keywords

Taglines

Cast

Director

It uses Cosine Similarity to measure similarity between movies and generate accurate recommendations.

## Problem Statement

With thousands of movies available on streaming platforms, users often struggle to find movies similar to their interests.

This project solves that problem by:

Analyzing movie metadata

Converting textual features into numerical vectors

Computing similarity scores

Recommending the top similar movies instantly

## Tech Stack

Python

NumPy

Pandas

Scikit-Learn

TfidfVectorizer

Cosine Similarity

Jupyter Notebook

## Dataset

Dataset used: movies.csv

Contains movie metadata such as:

Title

Genres

Keywords

Cast

Director

Tagline

## Project Workflow

1️⃣ Data Collection

2️⃣ Data Preprocessing

3️⃣ Feature Selection

4️⃣ Feature Combination

5️⃣ Text Vectorization using TF-IDF

6️⃣ Similarity Score Calculation

7️⃣ Recommendation Function Development

## Machine Learning Concept Used
* TF-IDF Vectorization

Converts textual data into numerical feature vectors.

* Cosine Similarity

Measures similarity between movie vectors.

### How It Works
 Example Usage
recommend_movies("Avatar")

* Output: Top 10 movies similar to Avatar

## Key Highlights

* Built a real-world recommendation engine
* Implemented NLP techniques for feature engineering
* Applied vectorization and similarity metrics
* Structured ML pipeline from raw data to deployment logic
* Improved understanding of recommender systems

## Business Impact

Helps OTT platforms personalize content

Increases user engagement

Improves customer retention

Enhances recommendation accuracy

## Future Improvements

Deploy using Streamlit

Add collaborative filtering

Integrate real-time user ratings

Improve scalability
