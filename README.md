# 🎬 Netflix Movies & TV Shows Analysis using Power BI

This project explores the **Netflix Movies and TV Shows dataset** with **Power BI** to uncover insights about content distribution, ratings, and trends across different countries.  

---

## 📂 Dataset  
The dataset used: **`netflix_titles.csv`**  
It contains details of Netflix content including:  

- 📌 Title  
- 🎥 Type (Movie / TV Show)  
- 🌍 Country  
- ⏱ Duration (in minutes or seasons)  
- 📅 Release Year  
- ⭐ Rating  
- 🎭 Genre (listed_in)  
- 📝 Description  

---

## 🛠 Data Cleaning & Transformation (Power Query)  

Steps performed in **Power Query** before visualization:  

- ✅ Removed null and duplicate values.  
- ✅ Split duration into **minutes (for movies)** and **seasons (for TV shows)**.  
- ✅ Standardized and renamed column names.  
- ✅ Extracted `country1` from country column for better grouping.  
- ✅ Converted data types (numbers, text, dates) properly.  

📸 *Power Query Transformation Screenshot:*  
![Power Query Screenshot](Screenshot%20(124).png)

---

## 📊 Power BI Dashboard  

The dashboard provides the following visualizations:  

1. **Show Count by Type** → Pie chart showing the share of Movies vs. TV Shows.  
2. **Show Count by Rating** → Bar chart representing distribution across age ratings (TV-MA, TV-14, PG, etc.).  
3. **Show Count by Country** → Horizontal bar chart showing top content-producing countries.  

📸 *Power BI Dashboard Screenshot:*  
![Power BI Dashboard](Screenshot%20(125).png)

---

## 🔎 Insights  

- 🎬 **Movies dominate** Netflix’s catalog compared to TV shows.  
- ⭐ Most titles are rated **TV-MA** and **TV-14**, highlighting Netflix’s focus on mature audiences.  
- 🌍 The **United States** and **India** contribute the largest share of Netflix content.  

---

## ⚡ Tools & Technologies  

- **Power BI Desktop** → Dashboard and visualization  
- **Power Query**

