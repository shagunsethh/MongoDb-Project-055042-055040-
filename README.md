# 📌 MongoDB Data Analysis Using ⁠ sample_mflix ⁠ Dataset(055042-055040)

## 📖 Overview  
This project utilizes *MongoDB Atlas* to analyze the ⁠ sample_mflix ⁠ dataset, which contains information about movies, including *title, year, genres, IMDb ratings, cast, and languages*.  

The project is divided into two key sections:  
1️⃣ *MongoDB Queries* – Performing *CRUD operations, filtering, and aggregations* to extract insights from the dataset.  
2️⃣ *MongoDB Atlas Dashboard* – A visual representation of key metrics using *interactive charts*.  

📊 *View the Dashboard Here:*  
[MongoDB Atlas Dashboard](https://charts.mongodb.com/charts-project-0-lwvnffp/public/dashboards/e60424cf-d4c6-4062-85a2-e7d631f40acf)  

---

## ⚡ 1. Queries Section  
The queries are written in *MongoDB aggregation pipeline format* and perform the following operations:  

### 🔹 *Data Retrieval (Find Queries)*  
•⁠  ⁠*Find movies released after 2000*  
•⁠  ⁠*Retrieve movies with IMDb rating > 8*  
•⁠  ⁠*Filter movies by genre (e.g., Action, Comedy, Sci-Fi, etc.)*  
•⁠  ⁠*Find movies with at least 3 cast members*  
•⁠  ⁠*Filter movies by runtime between 90–150 minutes*  
•⁠  ⁠*Retrieve movies that are neither Horror nor Thriller*  

### 🔹 *CRUD Operations*  
•⁠  ⁠*Insert a new movie (⁠ Inception ⁠, ⁠ The AI Revolution ⁠)*  
•⁠  ⁠*Update IMDb ratings and Metacritic scores*  
•⁠  ⁠*Delete a movie from the database*  

### 🔹 *Aggregation Queries*  
•⁠  ⁠*Find the average IMDb rating per genre*  
•⁠  ⁠*Identify the most common movie languages*  
•⁠  ⁠*Count movies released per year*  
•⁠  ⁠*Top 10 highest-rated movies with at least 1000 votes*  

---

## 📊 2. MongoDB Atlas Dashboard  
The *MongoDB Atlas Dashboard* provides a *visual summary* of key insights derived from the dataset.  

### 🔹 *Dashboard Highlights:*  
✔ *Genre Distribution:* Identifies the most popular movie genres.  
✔ *Movies Per Year:* Displays trends in movie production over time.  
✔ *Top Rated Movies:* Highlights the highest-rated films.  
✔ *Language Distribution:* Shows the most commonly used languages in movies.  
✔ *IMDb Ratings Breakdown:* Analyzes how IMDb ratings are distributed across movies.  

📊 *View the Full Dashboard Here:*  
[MongoDB Atlas Dashboard](https://charts.mongodb.com/charts-project-0-lwvnffp/public/dashboards/e60424cf-d4c6-4062-85a2-e7d631f40acf)  

---

## 🔍 3. Key Insights  

### 🎭 *Genre Trends:*  
•⁠  ⁠*Drama, Action, and Comedy* are the most frequent genres.  
•⁠  ⁠*Sci-Fi and Thriller* movies tend to have *higher IMDb ratings*.  

### 📅 *Yearly Movie Production Trends:*  
•⁠  ⁠The number of movies *increased significantly post-2000*.  
•⁠  ⁠*2020 saw a decline, likely due to **COVID-19's impact* on the film industry.  

### ⭐ *IMDb Rating Patterns:*  
•⁠  ⁠Only a *small percentage* of movies have an IMDb rating *above 8*.  
•⁠  ⁠The *majority of movies fall between 5–7*, indicating an average reception.  

### 🎬 *Director & Actor Insights:*  
•⁠  ⁠*Certain directors (e.g., Christopher Nolan, Steven Spielberg) consistently produce high-rated films*.  
•⁠  ⁠*Blockbuster actors appear in multiple high-grossing movies*, showing strong commercial appeal.  

### 🌍 *Language Distribution:*  
•⁠  ⁠*English dominates, but **French, Spanish, and Hindi* movies have a strong presence.  
•⁠  ⁠*International films (Korean, Japanese, etc.) are gaining popularity.*  

---

## ✅ 4. Recommendations  
Based on the analysis, the following recommendations can be made:  

1️⃣ *For Filmmakers & Studios:*  
   - Investing in *Sci-Fi and Thriller* films may lead to *higher IMDb ratings*.  
   - *Big-budget movies with well-known directors* tend to perform better.  

2️⃣ *For Streaming Platforms & Distributors:*  
   - *English remains dominant, but acquiring **international movies* can expand audience reach.  
   - Focus on promoting movies *with 1000+ IMDb votes*, as they provide more reliable audience feedback.  

3️⃣ *For Data Analysts & Researchers:*  
   - Future analysis can explore *box office revenue correlations* with IMDb ratings and genres.  
   - Sentiment analysis on *movie reviews* could provide additional insights into audience preferences.  
---

## 🛠 5. Tools & Technologies Used  
•⁠  ⁠*MongoDB Atlas* – Database and aggregation pipeline queries.  
•⁠  ⁠*MongoDB Compass* – Query testing and local data visualization.  
•⁠  ⁠*MongoDB Charts* – Interactive dashboard for data insights.  
•⁠  ⁠*Google Colab* – Python-based querying and reporting.
