# news-feed-recommender
Personalized news feed app that recommends articles using collaborative filtering and NLP with Transformers. Built with Flask, React, AWS Lambda, and Plotly Dash.
# News Feed Recommender

A personalized news feed system that mimics Meta’s News Feed behavior. Combines collaborative filtering and NLP embeddings to recommend content based on user preferences.

## 🚀 Features

- 🔍 **Recommendation Engine**: Collaborative filtering + Transformers for NLP-based embeddings (Hugging Face, scikit-learn).
- 🧠 **User Modeling**: Learns from post titles and text to capture user interest.
- 🖥️ **Frontend**: React-based interface that simulates Meta-style news interaction.
- 🔧 **Backend**: Flask REST API for data access and user actions.
- ☁️ **Automation**: AWS Lambda + Pandas pipelines for daily feed updates from RSS/blog APIs.
- 📊 **Dashboard**: Plotly Dash dashboard to monitor engagement metrics and model performance.

## 🛠️ Tech Stack

- **Frontend**: React
- **Backend**: Flask
- **ML/NLP**: scikit-learn, Hugging Face Transformers
- **Pipelines**: Pandas, AWS Lambda
- **Visualization**: Plotly Dash
- **APIs**: RSS feeds (e.g. Google News, TechCrunch)

## 📦 Setup Instructions

```bash
# Backend
cd backend
pip install -r requirements.txt
python app.py

# Frontend
cd frontend
npm install
npm start
