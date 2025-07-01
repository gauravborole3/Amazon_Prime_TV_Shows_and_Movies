# 🎬 Amazon Prime TV Shows and Movies – Exploratory Data Analysis (EDA)

This project presents a detailed Exploratory Data Analysis (EDA) on Amazon Prime Video's U.S. catalog, using two datasets:  
- `titles.csv` containing metadata for each title  
- `credits.csv` containing actor and director information

---

## 📌 Project Objective

To extract actionable insights about content trends, quality, popularity, and contributor performance on Amazon Prime — helping:
- 📺 Content Strategists plan future releases  
- 📣 Marketing Teams promote high-performing or underrated titles  
- 💰 Investors identify growth areas in the catalog

---

## 📁 Dataset Overview

- **titles.csv**  
  Contains over 9,000 titles with details like title name, genre, release year, runtime, IMDb/ TMDb scores, and age certifications.

- **credits.csv**  
  Contains over 120,000 entries mapping actors and directors to the titles, along with roles and character names.

---

## 🧹 Data Cleaning & Preparation

- Handled missing values, especially for `imdb_score`, `tmdb_score`, and `age_certification`
- Cleaned genres and country data stored in list-like formats
- Checked for and handled outliers in numeric columns (e.g., runtime)
- Merged relevant columns for contributor analysis

---

## 📊 Key Visualizations

1. **🟠 Content Type Distribution** – Movie vs. TV Show
2. **🎭 Top 10 Genres** – Based on frequency
3. **🌟 IMDb Score Distribution**
4. **📈 Titles Released Over the Years**
5. **🔞 Age Certification Distribution**
6. **🔥 Most Popular Titles by TMDb Popularity**
7. **🌍 Top Content-Producing Countries**
8. **⭐ Top Genres by IMDb Score**
9. **🎭 Top 10 Actors by Average IMDb Score**
10. **🎬 Top 10 Directors by Average IMDb Score**

---

## 📌 Summary & Conclusion

- Movies dominate Amazon Prime's catalog
- Drama & Comedy are most frequent, but genres like Documentary and History score higher
- Metadata gaps like missing age ratings affect UX and filters
- Content is heavily U.S.-centric
- High engagement doesn’t always align with high quality (TMDb vs IMDb)
- Certain actors and directors consistently contribute to top-rated content

---

## 🎯 Strategic Business Insights

- Improve metadata completeness (especially age ratings)
- Explore underrepresented high-quality genres
- Use actor/director analytics for original content planning
- Expand regional content offerings

---

## 🧠 What I Learned

- Used Plotly Express for interactive visualizations
- Connected EDA insights to real-world business decisions
- Analyzed contributor impact beyond just title metadata
- Sharpened storytelling through data

---

## 👨‍💻 Author

**Gaurav Borole**  
Data Analyst @ Astegic Infosoft Pvt. Ltd.  
📧 gauravborole3@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/gaurav-borole)  
