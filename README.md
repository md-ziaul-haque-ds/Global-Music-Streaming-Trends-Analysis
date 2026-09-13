# 🎵 Global Music Streaming Trends Analysis

An end-to-end data analytics project analyzing global music streaming behavior, listener preferences, platform usage, engagement patterns, and regional trends using **Python and Power BI**.

---

## 📊 Dashboard Preview

### Dashboard Overview

![Dashboard Overview](05_Dashboard_Screenshots/1.%20Dashboard%20Overview.png)

### User Demographics

![User Demographics](05_Dashboard_Screenshots/2.%20User%20Demographics.png)

### Listening Behaviour

![Listening Behaviour](05_Dashboard_Screenshots/3.%20Listening%20Behaviour.png)

### Engagement & Preferences

![Engagement & Preferences](05_Dashboard_Screenshots/4.%20Engagement%20%26%20Preferences.png)

### Interactive Data Explore

![Interactive Data Explore](05_Dashboard_Screenshots/5.%20Interactive%20Data%20Explore.png)

---

## 🎯 Business Objective

The objective of this project is to analyze global listener preferences and streaming behavior to uncover patterns in:

* Streaming platform usage
* Genre and artist preferences
* User demographics
* Free vs. Premium subscription behavior
* Listening-time preferences
* Regional streaming trends
* User engagement and repeat listening

The analysis aims to generate **actionable business insights** that can support personalized recommendations, targeted marketing, content strategies, and subscription growth.

---

## ❓ Business Questions

The analysis focuses on six key business questions:

1. What are the most popular music streaming platforms?
2. How does age impact music preferences?
3. What are the most streamed genres and artists?
4. How do Free vs. Premium users differ in streaming behavior?
5. What time of day do users stream music the most?
6. Are there any regional trends in music streaming preferences?

---

## 🗂️ Dataset

The dataset contains **5,000 records and 12 attributes**, covering listener demographics, streaming behavior, subscription type, music preferences, and engagement.

### Key Attributes

* **User_ID** — Unique listener identifier
* **Age** — User age
* **Country** — Country of residence
* **Streaming Platform** — Music streaming service used
* **Top Genre** — Preferred music genre
* **Minutes Streamed Per Day** — Average daily streaming time
* **Number of Songs Liked** — Total songs liked
* **Most Played Artist** — Most frequently played artist
* **Subscription Type** — Free or Premium
* **Listening Time** — Morning, Afternoon, or Night
* **Discover Weekly Engagement (%)** — Engagement with recommended playlists
* **Repeat Song Rate (%)** — Song replay behavior

**Dataset Source:** Open-source Kaggle dataset — *Global Music Streaming Trends and Listener Insights*

📁 [View Raw Dataset](06_Raw_Dataset/Global_Music_Streaming_Listener_Preferences.csv)

---

## 🛠️ Tools & Technologies

| Category                 | Tools               |
| ------------------------ | ------------------- |
| Programming              | Python              |
| Data Manipulation        | Pandas, NumPy       |
| Data Visualization       | Matplotlib, Seaborn |
| Business Intelligence    | Power BI            |
| Data Transformation      | Power Query         |
| Analytics & Calculations | DAX                 |
| Development Environment  | Jupyter Notebook    |
| Data Format              | CSV                 |

---

## 🔄 Project Workflow

**Business Understanding → Data Exploration → Python EDA → Power BI Dashboard → Business Insights → Recommendations**

### 1️⃣ Business Objective & Data Exploration

Defined the business objective, explored the dataset structure and attributes, and established the key business questions.

📄 [View Business Objective, Data Exploration & Business Questions](1.%20Business%20Objective%2C%20Data%20Exploration%2C%20Business%20Questions.pdf)

---

### 2️⃣ Exploratory Data Analysis — Python

Performed exploratory data analysis using Python to investigate data distributions, relationships, user behavior, genre preferences, platform usage, and engagement patterns.

📄 [EDA Python Documentation](2_EDA_Python_Documentation.pdf)

🐍 [Python EDA Jupyter Notebook](2_EDA_Python.ipynb)

---

### 3️⃣ Power BI Dashboard

Developed an interactive Power BI dashboard to transform analytical findings into business-focused KPIs and visualizations.

📊 [Global Music Streaming Trends Analysis — Power BI](3.%20Global%20Music%20Streaming%20Trends%20Analysis.pbix)

📄 [Power BI Documentation](3.%20Power%20BI%20Documentation.pdf)

---

### 4️⃣ Business Insights & Recommendations

Translated the analytical findings into actionable recommendations for streaming platforms, focusing on engagement, personalization, subscription growth, regional targeting, and marketing optimization.

📄 [Business Insights & Recommendations](4.%20Business%20Insights%20and%20recommendations.pdf)

---

## 📈 Key Findings

### 🎧 Competitive Streaming Platforms

Amazon Music, Spotify, YouTube, Apple Music, Deezer, and Tidal have relatively competitive user distributions, with **Amazon Music showing slightly higher representation**.

### 👥 Dominant User Segments

The **31–45 and 46–60 age groups** represent the largest user segments, making users aged 31–60 an important target audience for personalized marketing and platform strategies.

### 🎸 Genre Engagement

**Rock, R&B, and Classical** show the highest average listening time, followed by Hip-Hop, EDM, and Jazz.

### 💎 Free vs. Premium

The dataset shows an almost even subscription split:

* **Free:** 49.48%
* **Premium:** 50.52%

This indicates a significant opportunity to convert highly engaged free users into premium subscribers.

### 🌙 Listening Time

**Night** is the dominant listening period, followed by Afternoon and Morning.

Listening preferences also vary by genre and region, creating opportunities for time-based personalization.

### 🌍 Regional Trends

Streaming behavior varies across regions. The analysis identifies stronger nighttime preferences in countries such as the **UK and Brazil**, while **Japan and South Korea** show stronger morning/afternoon preferences.

---

## 💡 Business Recommendations

Based on the analysis:

* Strengthen personalized recommendations using listener behavior and genre preferences.
* Introduce exclusive content and premium features to convert engaged Free users.
* Schedule new-release promotions around peak listening periods.
* Develop age- and region-specific marketing strategies.
* Use AI-driven playlist curation to improve recommendation engagement.
* Identify highly engaged Free-user segments for targeted conversion campaigns.
* Optimize push notifications and in-app promotions according to regional listening patterns.

---

## 📸 Dashboard Screenshots

The dashboard contains five analytical views:

| Dashboard View               | Focus                                             |
| ---------------------------- | ------------------------------------------------- |
| **Dashboard Overview**       | Overall KPIs, platforms, genres & subscriptions   |
| **User Demographics**        | Age groups, countries & subscription distribution |
| **Listening Behaviour**      | Genre, artist & listening-time behavior           |
| **Engagement & Preferences** | Repeat rates, platforms & genre/time preferences  |
| **Interactive Data Explore** | Interactive exploration of the underlying data    |

[📂 View all dashboard screenshots](05_Dashboard_Screenshots/)

---

## 📁 Project Structure

```text
global-music-streaming-analysis/
│
├── README.md
│
├── 1. Business Objective, Data Exploration, Business Questions.pdf
│
├── 2. EDA_Python_Documentation.pdf
│
├── 2. EDA_Python _. ipynb
│
├── 3. Global Music Streaming Trends Analysis.pbix
│
├── 3. Power BI Documentation.pdf
│
├── 4. Business Insights and recommendations.pdf
│
├── 05_Dashboard_Screenshots/
│   ├── .gitkeep
│   ├── 1. Dashboard Overview.png
│   ├── 2. User Demographics.png
│   ├── 3. Listening Behaviour.png
│   ├── 4. Engagement & Preferences.png
│   └── 5. Interactive Data Explore.png
│
└── 06_Raw_Dataset/
    ├── .gitkeep
    └── Global_Music_Streaming_Listener_Preferences.csv
```

---

## 🎯 Conclusion

This project demonstrates an end-to-end data analytics workflow — from **business problem definition and exploratory analysis to interactive dashboard development and actionable business recommendations**.

The analysis highlights opportunities around personalization, premium conversion, regional targeting, content timing, and data-driven marketing strategies.

---

## 👤 Author

**Md Ziaul Haque**

**Aspiring Data Analyst | Python | SQL | Power BI | Tableau | Excel | Machine Learning**

🔗 [LinkedIn](https://www.linkedin.com/in/mdziaulhaque-datascience)
