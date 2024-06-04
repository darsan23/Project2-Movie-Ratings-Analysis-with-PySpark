# Movie Ratings Analysis

## Overview

Movie Ratings Analysis is a project that utilizes the MovieLens dataset to analyze movie ratings and user preferences. The dataset contains 100,000 ratings from 943 users on 1,682 movies, along with demographic information about the users. The goal of this project is to perform exploratory data analysis (EDA) and build a movie recommendation system based on user ratings and preferences.

## Dataset Description

The dataset consists of the following files:

- **u.data**: Contains 100,000 ratings by 943 users on 1,682 items. Each user has rated at least 20 movies. The data includes user ID, item ID, rating, and timestamp.
- **u.item**: Provides information about the movies, including movie ID, title, release date, genres, and IMDb URL.
- **u.user**: Contains demographic information about the users, such as user ID, age, gender, occupation, and zip code.
- **u.genre** and **u.occupation**: Lists of movie genres and user occupations, respectively.
- **u1.base, u1.test, ..., u5.base, u5.test**: Training and test datasets for cross-validation.

## Project Structure

1. **Data Ingestion and Preparation**: Extract the dataset and load it into Spark DataFrames. Perform data cleaning and schema definition.
2. **Exploratory Data Analysis (EDA)**: Analyze movie ratings, user demographics, and movie genres using SQL queries and DataFrame operations.
3. **User Ratings Analysis**: Explore user preferences, identify top-rated movies, and analyze user demographics.
4. **Building Recommendation System**: Implement algorithms to build a movie recommendation system based on collaborative filtering or content-based methods.
5. **Evaluation**: Evaluate the performance of the recommendation system using appropriate metrics such as precision, recall, and accuracy.

## Usage

1. Clone the repository to your local machine.
2. Set up a Spark environment and import the necessary libraries.
3. Run the Jupyter notebook or Python script to execute the analysis and build the recommendation system.
4. Customize the analysis and algorithms based on your requirements.
5. Share your insights and results with others.

## Acknowledgements

Special thanks to instructor Harika for providing the cleaned-up dataset and accompanying scripts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

