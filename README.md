# Movie Data Analysis Project

## Team Members
1. **Niat Kahsay**
2. **Allison McKernan**
3. **Gabriel Duffy**

## Project Overview
This project aims to analyze and compare data from multiple movie databases, including IMDB, Netflix, and a large dataset of 58,000 popular movies. By merging and preprocessing these datasets, we can uncover insights about movie ratings, trends, genres, and other key attributes.

## Datasets Used
### 1. [Popular Movies Dataset (58,000+ Movies)](https://www.kaggle.com/datasets/whenamancodes/popular-movies-datasets-58000-movies)
   - Contains metadata for over 58,000 movies.
   - Includes details such as title, release year, genre, budget, revenue, and more.
   
### 2. [IMDB Top 250 Movies](https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset)
   - Lists the top 250 movies from IMDB.
   - Features include movie rank, title, release year, rating, votes, genre, director, and more.

### 3. [Netflix Movies Dataset](https://www.kaggle.com/datasets/danghuutri/netflix-movies)
   - Contains a list of movies available on Netflix.
   - Includes information like title, genre, director, cast, release date, duration, and country of origin.

## Preprocessing Steps
1. **Data Cleaning:**
   - Handling missing values and duplicate entries.
   - Standardizing date formats and numerical values.
   
2. **Feature Engineering:**
   - Extracting relevant features such as movie duration in minutes.
   - Standardizing currency values for budget and revenue.
   
3. **Data Merging:**
   - Combining datasets based on common fields such as movie title and release year.
   - Handling variations in naming conventions.
   
4. **Exploratory Data Analysis (EDA):**
   - Visualizing trends in movie ratings, budget, and box office revenue.
   - Comparing IMDB, Netflix, and general movie trends.
   
## How to Use
1. Download the datasets from the provided links.
2. Run the preprocessing script (`data_preprocessing.py`) to clean and merge the datasets.
3. Use the analysis notebooks (`movie_analysis.ipynb`) to explore trends and insights.
4. Generate visualizations using tools like Matplotlib and Seaborn.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (for interactive analysis)

## Future Enhancements
- Sentiment analysis on user reviews.
- Predictive modeling for movie success based on past trends.
- Recommendation system based on user preferences.
