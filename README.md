# etl_yt_spotify

# 🎵📺 YouTube & Spotify Analytics ETL Pipeline

This project demonstrates an end-to-end **ETL (Extract, Transform, Load)** pipeline using **Python** to process streaming data from YouTube and Spotify. The goal is to extract key insights, clean raw JSON data, transform it for analytics, and prepare it for BI dashboards.

---

## 📌 Project Overview

**Domain:** Entertainment/Streaming  
**Type:** Data Engineering | Analytics | BI  
**Tools Used:** Python, Pandas, CSV, Tableau/Power BI (optional)

---

## 📊 Data Sources

- **YouTube JSON**: Video views, likes, upload dates
- **Spotify JSON**: Artist, streams, release dates

---

## 🔄 ETL Pipeline

### ✅ Extract
- Read raw JSON files for YouTube & Spotify data
- Load into Pandas DataFrames

### ✅ Transform
- Clean nulls, convert data types
- Generate:
  - Engagement rate (YouTube)
  - Days since upload/release
  - Streams in millions (Spotify)

### ✅ Load
- Exported cleaned data to:
  - `youtube_transformed.csv`
  - `spotify_transformed.csv`

> These are ready to be visualized in Tableau, Power BI, or loaded into SQL.


