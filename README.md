# 🎥 Movie Recommendation System  

**Team Members**:  
- **Niat Kahsay**  
- **Allison McKernan**  
- **Gabriel Duffy**  

---

## 🚀 Overview  

This project builds an **ETL pipeline** to process and analyze movie ratings, metadata, and Oscar awards data, ultimately generating personalized movie recommendations. The system leverages collaborative filtering techniques and a user-friendly dashboard to deliver insightful and engaging recommendations.  

### 🌟 Key Features  
- **Data Integration**: Combines information from **MovieLens**, **Kaggle**, and **Oscar Awards** datasets for comprehensive analysis.  
- **Recommendation Algorithm**: Implements collaborative filtering to deliver tailored movie suggestions based on user preferences.  
- **Visual Dashboard**: Interactive dashboard showcasing trends, analytics, and award-winning films for an enhanced user experience.  
- **Awards Insights**: Highlights Oscar-winning films to enrich the recommendation process.  

---

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

## 🛠️ Tools & Technologies  

- **Programming Languages**: Python  
- **Libraries**: Pandas, NumPy, SciKit-Learn, Matplotlib, Seaborn  
- **Dashboard Framework**: Streamlit / Dash  
- **Database**: PostgreSQL / SQLite (for data storage and querying)  
- **Pipeline Orchestration**: Apache Airflow / Prefect  

---

## 📂 Project Workflow  

1. **Data Extraction**:  
   - Retrieve data from the MovieLens, Kaggle, and Oscar Awards sources.  

2. **Data Transformation**:  
   - Clean and preprocess datasets (e.g., handling missing values, standardizing formats).  
   - Enrich movie metadata with award insights for better recommendations.  

3. **Data Loading**:  
   - Load cleaned datasets into a relational database for querying and analysis.  

4. **Recommendation System**:  
   - Build and train a collaborative filtering model to generate personalized recommendations.  

5. **Visualization Dashboard**:  
   - Create an interactive interface to display recommendations, trends, and insights.  

---

## 📈 Results & Insights  

- **User Preferences**: Analyze user ratings to uncover popular genres and preferences.  
- **Award-winning Films**: Highlight the impact of Oscar wins on movie popularity and recommendations.  

---
