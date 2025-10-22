# Spotify Advanced SQL Project and Query Optimization  

### Project Category: Advanced  
**Dataset:** [Spotify Dataset on Kaggle](https://www.kaggle.com/datasets/sanjanchaudhari/spotify-dataset)  

---

## 🧠 Overview  
This project focuses on analyzing a **Spotify dataset** containing information about songs, albums, and artists using **SQL**.  
The goal was to practice **advanced SQL concepts**, clean and organize raw data, run queries of different difficulty levels, and improve performance using **query optimization** techniques.  

---

## ⚙️ Project Steps  

### 1. Understanding the Data  
The dataset includes details like:  
- **Artist:** Name of the performer  
- **Track:** Song name  
- **Album:** The album the song belongs to  
- **Album Type:** Whether it’s a single or a full album  
- **Metrics:** Danceability, energy, loudness, tempo, and more  

A sample SQL table structure was created to store all these details in an organized format.  

---

### 2. Writing SQL Queries  
Once the data was ready, queries were written at three levels — **easy**, **medium**, and **advanced** — to explore different SQL techniques.  

#### 🟢 Easy Queries  
Simple queries to retrieve or filter data.  
Examples:  
- Find all songs with more than 1 billion streams.  
- List all albums with their artists.  
- Count total comments on licensed tracks.  

#### 🟠 Medium Queries  
Queries that use **joins**, **aggregations**, and **grouping**.  
Examples:  
- Calculate the average danceability per album.  
- Find top 5 energetic tracks.  
- Compare streams between Spotify and YouTube.  

#### 🔴 Advanced Queries  
Used **window functions**, **CTEs**, and **subqueries** for complex analysis.  
Examples:  
- Get the top 3 most-viewed songs for each artist.  
- Calculate the difference between highest and lowest energy tracks per album.  
- Find cumulative likes based on views.  

---

### 3. Query Optimization  
To make SQL queries faster and more efficient:  
- **Analyzed performance** using the `EXPLAIN` command.  
- **Created indexes** (e.g., on the `artist` column) to speed up data retrieval.  
- Measured how query execution time dropped significantly after indexing.  

This process showed how a few small optimizations can make a big difference in database performance.  

---

## 🧩 Technology Stack  
- **Database:** PostgreSQL  
- **Tools Used:** pgAdmin 4 or any SQL editor  
- **Techniques:** DDL/DML queries, joins, subqueries, window functions, and indexing  

---

## ▶️ How to Run the Project  
1. Install PostgreSQL and pgAdmin (or use any SQL editor).  
2. Create the database and table using the provided SQL schema.  
3. Load the dataset from Kaggle.  
4. Run the SQL queries listed above to explore insights.  
5. Try query optimization using the `EXPLAIN` command and indexing.  

---

## 🚀 Next Steps  
- Create dashboards in **Power BI** or **Tableau** using the query results.  
- Add more data for deeper insights.  
- Experiment with new optimization techniques for large datasets.  

---

## 🤝 Contributing  
Want to improve this project?  
- Fork the repository  
- Suggest ideas or open issues  
- Submit pull requests  

---

## 📜 License  
This project is licensed under the **MIT License**, meaning you’re free to use and modify it with attribution.  
