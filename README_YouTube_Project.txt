# 🎥 YouTube Data Harvesting and Warehousing Project

## 📌 Project Overview
This project is a Streamlit-based web application that collects YouTube channel data using the YouTube Data API v3, stores it in MongoDB (NoSQL), and migrates it to PostgreSQL (SQL) for structured analysis.

It also provides SQL-based analytics to query insights like top videos, views, likes, comments, and channel performance.

---

## ⚙️ Features

- YouTube API Integration
- Channel Data Extraction
- Video, Playlist & Comment Data Collection
- MongoDB Storage (Raw Data Layer)
- PostgreSQL Storage (Structured Data Layer)
- Data Migration from MongoDB → PostgreSQL
- SQL Analytics Dashboard using Streamlit
- Data visualization using Pandas + Streamlit

---

## 🧰 Technologies Used

- Python
- Google YouTube Data API v3
- Streamlit
- MongoDB
- PostgreSQL
- Pandas
- Psycopg2
- PyMongo

---

## 📂 Project Structure

main.py (Streamlit App)

---

## 🚀 How to Run the Project

1. Install Dependencies:
pip install google-api-python-client pymongo psycopg2 pandas streamlit

2. Run Streamlit App:
streamlit run main.py

---

## 🔑 Setup Requirements

- YouTube API Key (Google Cloud Console)
- MongoDB connection string
- PostgreSQL local server setup

---

## 📊 Features in App

1. Data Collection
- Enter YouTube Channel ID
- Fetch channel info, videos, playlists, comments
- Store in MongoDB

2. Data Migration
- Convert MongoDB data → PostgreSQL tables
- Tables: channels, playlists, videos, comments

3. SQL Analysis Queries
- Top videos by views
- Likes and comments analysis
- Channel performance metrics

---

## 👨‍💻 Author
Generated README for YouTube Data Harvesting Project
