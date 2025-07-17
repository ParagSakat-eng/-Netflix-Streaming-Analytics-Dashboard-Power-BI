# -Netflix-Streaming-Analytics-Dashboard-Power-BI
## 📌 Project Objective:
This project explores the Netflix content library using Power BI. The dashboard highlights key metrics such as content type (Movies vs TV Shows),  genre distribution, ratings, regional origin, and historical trends. The goal is to visualize how Netflix has evolved over time and understand its content strategies.

## 💡 Tip:This is not real-time or official Netflix data. It is a sample dataset used for learning and visualization purposes only.

## 📂 Dataset Used
A sample Netflix dataset in CSV format including:
- Title
- Type (Movie/TV Show)
- Genre
- Country
- Rating
- Duration
- Release Year
- Start and End Year
- Locations
  <a href="https://github.com/ParagSakat-eng/-Netflix-Streaming-Analytics-Dashboard-Power-BI/blob/main/netflix_titles.csv"> Netflix Streaming Data</a>
  
## ❓ Questions Answered (KPIs)
- Total number of titles on Netflix?
- Content distribution: Movies vs TV Shows?
- Which genres dominate Netflix?
- What are the most common ratings?
- What are the top content-producing countries?
- How has Netflix grown over time?
- What are the start and end years of available titles?
- DashBoard Interaction <a href="https://github.com/ParagSakat-eng/-Netflix-Streaming-Analytics-Dashboard-Power-BI/blob/main/Netflix%20Dashboard.pdf"> View DashBoard </a>
  

## ⚙️ Process

1. **Power Query**:
   - Removed nulls/duplicates
   - Normalized genres
   - Extracted and cleaned year fields

2. **Data Modeling**:
   - Created DAX KPIs (e.g., Movie %, Rating counts)
   - Connected dimension and fact tables

3. **Dashboard Design**:
   - Donut Chart: Content Type
   - Bar Charts: Ratings, Genres
   - Tree Map: Top 10 Countries
   - Line Chart: Release Trend
   - Theme: Netflix-style dark UI

  ## 🔍 Project Insights

- **Total Titles**: 6,169
- 68% Movies, 32% TV Shows
- Top Genres: Documentaries, Comedy, Dramas
- Dominant Ratings: TV-MA, TV-14
- Most content from: United States, India, UK
- Massive content growth after 2015
  
## ✅ Final Conclusion

Netflix's library emphasizes **adult-rated content**, with a strong focus on **documentary and drama** genres. Its primary market is the **U.S.**, with selective expansion globally. This dashboard provides valuable insights into Netflix's evolving content strategy.

## 🛠️ Tools Used
- Microsoft Power BI
- Power Query
- DAX
  
## 📷 Dashboard Preview
<a href="https://github.com/ParagSakat-eng/-Netflix-Streaming-Analytics-Dashboard-Power-BI/blob/main/Netflix%20DashBoard%20SS.PNG"> Dashboard Preview </a>

