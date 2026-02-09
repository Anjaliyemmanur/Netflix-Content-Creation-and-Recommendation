# Netflix-Content-Creation-and-Recommendation

## 📌 Project Objective
The objective of this project is to analyze Netflix’s catalog of movies and TV shows to identify trends in:
- Content type (Movies vs TV Shows)
- Genre distribution
- Country-wise availability
- Release patterns over time

The goal is to generate data-driven insights and business recommendations to help Netflix:
- Decide what type of content to produce
- Identify high-potential countries and genres
- Improve engagement across global markets

## Project work- https://colab.research.google.com/drive/1GfcMI4Va2weMmcq1RpIYpqgwTYWE45D0#scrollTo=5GvTshLsWyBH

🗂 Dataset
Source: Netflix Movies and TV Shows dataset
Records: Titles available on Netflix
Key Attributes:
title, type, director, cast, country, date_added, release_year, rating, duration, listed_in, description

🛠 Tools & Libraries
Python
Pandas, NumPy
Matplotlib, Seaborn
Google Colab

## 🔍 Data Exploration & Cleaning
Key questions addressed:
- Is the dataset complete and suitable for analysis?
- Which attributes contain missing values, and how significant are they?
- Which fields (director, cast, country, date added, description) require cleaning?
- How can missing categorical data be handled without losing records?
- What do statistical summaries reveal about data distribution and variability?

## 🧩 Feature Engineering
Key questions addressed:
- Which columns contain multi-valued information limiting analysis?
- How can directors, cast members, and countries be analyzed individually?
- What transformations are needed to make features analysis-ready?
- How can transformed features be merged without losing dataset context?
- How should duration values be standardized for fair comparison?

## 📊 Exploratory Data Analysis (EDA)
Key questions addressed:
- What is the distribution of Movies vs TV Shows on Netflix?
- Which genres dominate the catalog, and how strong is international content?
- Which countries contribute the most content globally?
- How has Netflix’s content output evolved over time?
- How do ratings vary by country and content type?
- Which actors and directors appear most frequently across regions?

## 🌍 Country-wise Univariate Analysis
 Separate analysis conducted for:
- Movies & TV Shows: United States, India, United Kingdom
- TV Shows only: Japan, South Korea

## 💡 Key Insights
- Content Mix: Movies account for ~70% of the catalog, while TV Shows make up ~30%. However, TV Show engagement is increasing in select regions.
- Top Producing Countries:
    o Movies: United States, United Kingdom, India
    o TV Shows: United States, United Kingdom, Japan, South Korea, India
    o Duration Trends: Indian movies tend to have longer durations, which may impact completion rates and engagement.
    o Ratings & Engagement: Ratings vary significantly by country and content type; higher-rated content shows stronger engagement.
    o Talent Impact: Certain actors and directors consistently drive higher regional engagement.
    o Regional Preferences: Movies dominate globally, while TV Shows show strong growth in Asia-Pacific markets.

## 📈 Business Recommendations
- Increase investment in TV Show production, especially in Asia-Pacific regions.
- Focus content expansion in US, UK, India, Japan, and South Korea.
- Introduce short-form series and episodic content to boost retention.
- Localize content by incorporating region-specific genres, languages, and cultural themes.
- Optimize content duration—shorter movies or segmented releases for markets like India.
- Use ratings to guide content recommendations and production decisions.
- Promote high-rated content regionally to maximize engagement.
- Prioritize collaborations with popular actors and directors in specific markets.
- Cross-promote TV Shows to movie viewers in high binge-watch regions.
- Track re-watch behavior, peak viewing times, and genre-level engagement for future optimization.
