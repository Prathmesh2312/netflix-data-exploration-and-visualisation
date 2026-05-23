# 🎬 Netflix – Data Exploration & Visualization

## 📌 Introduction
Netflix is one of the world’s most popular video streaming platforms, with over 220M+ subscribers globally (as of 2021). It offers a vast catalog of movies and TV shows across multiple genres and countries.  

This case study explores the **Netflix dataset (as of mid-2021, ~8,800 titles)** to uncover insights that can guide **content production strategies** and **business growth opportunities**.

---

## 🎯 Problem Statement
Netflix wants to understand:
- Which type of content (movies vs TV shows) to prioritize.  
- Which genres perform best across different regions.  
- How to grow in international markets by producing the right kind of localized content.  
- When is the best time to release new titles to maximize viewership.  

---

## 📂 Dataset
- **Source:** Public dataset of Netflix titles (2021 snapshot).  
- **Shape:** 8,807 rows × 12 columns.  
- **Features:**
  - `show_id`: Unique identifier  
  - `type`: Movie or TV Show  
  - `title`: Name of the content  
  - `director`: Director(s)  
  - `cast`: Main actors  
  - `country`: Country of production  
  - `date_added`: Date when added to Netflix  
  - `release_year`: Year of release  
  - `rating`: Content rating (PG, R, TV-MA, etc.)  
  - `duration`: Runtime (minutes for movies, seasons for shows)  
  - `listed_in`: Genre(s)  
  - `description`: Summary  

---

## 🛠 Methodology
1. **Data Preprocessing**
   - Checked data types, converted relevant attributes (e.g., dates, durations).  
   - Handled missing values (e.g., 30% missing directors, 10% missing country/cast).  
   - Created derived features (`Minutes`, `Month_Added`).  

2. **Exploratory Data Analysis**
   - **Non-Graphical Analysis:** Value counts, unique attributes, summary stats.  
   - **Univariate Analysis:** Distribution of release years, duration, genres, countries.  
   - **Bivariate Analysis:** Content trends across regions, TV shows vs movies, monthly additions, boxplots by type.  
   - **Correlation Analysis:** Heatmaps for numeric features.  

3. **Visualization Tools**
   - Python (Pandas, Seaborn, Matplotlib).  
   - Histograms, countplots, barplots, boxplots, heatmaps.  

---

## 📊 Key Findings
1. **Content Type**
   - Movies dominate the catalog (**6,131 movies vs 2,676 TV shows**).  
   - However, **TV shows are more recent**, indicating Netflix’s shift to episodic content.  

2. **Release Trends**
   - Majority of content released between **2013–2019**, with a surge around 2020.  
   - Typical movie duration: **90–110 minutes**.  

3. **Genre Preferences**
   - Top genres: **Dramas, Documentaries, International Movies, Stand-up Comedy, Kids’ TV**.  
   - Family-oriented content has strong presence, appealing to households.  

4. **Regional Insights**
   - **US:** Largest contributor (2818 titles) – strong in Drama, Comedy, Action.  
   - **India:** Second largest (972 titles) – movie-heavy, focused on Drama, Thriller, Romance.  
   - Other key producers: UK, Japan, South Korea, Canada.  

5. **Seasonality**
   - Titles are mostly added in **July & December**, aligning with school holidays and festive seasons.  

---

## 💡 Business Insights
- Netflix has shifted towards **TV shows** for higher engagement.  
- **Localized content** drives international growth (Bollywood in India, K-dramas in Korea, Spanish thrillers in LATAM).  
- **Family & Kids’ content** ensures long-term household subscriptions.  
- Strategic **release timing** (summer & holiday seasons) boosts viewership.  

---

## ✅ Recommendations
1. **Expand Regional Content**  
   Invest in local productions tailored to cultural preferences (e.g., Bollywood dramas, Korean series).  

2. **Balance TV Shows & Movies**  
   Continue growing episodic content while keeping strong movie offerings in trending genres (Drama, Thriller).  

3. **Capitalize on Seasonal Demand**  
   Plan **big releases in July and December** for maximum impact.  

4. **Strengthen Family & Kids’ Segment**  
   Produce more **children’s shows and family-friendly movies** to attract household subscriptions.  

5. **Talent Strategy**  
   Partner with **popular regional actors and directors** to attract local audiences. 

---

## 🛠 Tools & Skills
- Python - Pandas, Matplotlib, Seaborn  
- Environment - Jupyter Notebook / Google Colab 
- Exploratory Data Analysis (EDA)  
- Data Analysis & Visualization  

---

👨‍💻 **Author:** Prathmesh Raut  
📌 *MSc Computer Science | Data Analyst | Data Science & Machine Learning Enthusiast*  

