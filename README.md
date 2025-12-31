# IMDB_Dashboard
📊 IMDb Movies Analytics Dashboard – Built in Power BI 
🎬 85,000+ real movie records (genres, ratings, directors, votes) 
🔍 Insights: Top genres, decade trends, highest-rated directors, runtime vs rating 
🧰 Tools: Power BI, Power Query, DAX, IMDb Open Dataset

**🎬 IMDb Movies Power BI Dashboard**

Data-Driven Analysis of Global Cinema Trends (1980–2024)

This repository contains a Power BI dashboard built using the IMDb Movies Open Dataset (85,000+ records).
The dashboard explores movie ratings, genres, audience popularity, directors, and actor statistics, helping uncover insightful trends in the global film industry.

**📌 Project Overview**
The objective of this project was to:
Extract and clean raw IMDb TSV/CSV files (title.basics, title.ratings, name.basics, title.principals)
Build a Star-Schema Data Model inside Power BI
Apply DAX measures to calculate KPIs
Design a cinematic-themed visual dashboard for presentation & storytelling
This dashboard is suitable for academic display, data analytics portfolios, and BI demonstration.

**🎯 Key Features**
Feature	Description
Movie KPIs	Total Movies, Average Rating, Total Votes
Genre Breakdown	Most popular genres based on movie count & audience ratings
Rating Distribution	Histogram of IMDb rating ranges
Director Analytics	Top Directors by Average Rating & Movie Count
Actor / Actress Roles	Donut chart breakdown of film industry roles
Runtime & Popularity	Correlation between movie length & user engagement
Slicers	Dynamic filtering by decade, genre, and rating bin

**🧠 Tech Stack**
Power BI Desktop
Power Query Editor
DAX Measures
IMDb Open Dataset (Kaggle / TSV files)

**🛠 Data Processing Workflow**
1️⃣ Import IMDb TSV files into Power BI
2️⃣ Clean data & handle nulls (\N → null)
3️⃣ Transform genre column (split → rows)
4️⃣ Create date grouping (Decade)
5️⃣ Add measures:
Total Movies = COUNTROWS('title basics')
Average IMDb Rating = AVERAGE('title ratings'[averageRating])
…and advanced calculations for Top Directors

**📥 Dataset Source**
Dataset Used: IMDb Movies Dataset – 85,000+ Movies
🔗 https://www.kaggle.com/datasets/ashirwadsangwan/imdb-dataset

**🚀 How to Use**
Download .pbix file from this repo
Open using Power BI Desktop
Use slicers to filter data
View interactive visuals and explore insights

🏁 Future Improvements
Add Box Office Revenue Analysis
Deploy Power BI Dashboard to Web
Add RLS (Row Level Security) for multi-user deployment
Build ML Recommendation Engine powered by IMDb metadata

💡 Author
Hritvik Garg & Advika khaushik – Data Science | Power BI | Analytics
