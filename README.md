# 🎬 AI-Powered Movie Recommender System

Welcome to the **Movie Recommender System**, an intelligent web app built using **Streamlit** that suggests movies based on user preferences. Whether you're in the mood to explore by genres or find movies similar to one you've already seen, this system helps you discover what to watch next — quickly and intuitively.

---

## 💡 Overview

This project leverages a **K-Nearest Neighbours (KNN)** algorithm to recommend movies using features extracted from the **IMDB 5000 Movie Dataset**. Users can:

- Choose a movie and get similar recommendations
- Select genres and IMDb ratings to generate personalized suggestions
- Optionally view posters of recommended movies fetched live from IMDb

---

## 🚀 Features

✅ Movie-based recommendation  
✅ Genre-based recommendation  
✅ Interactive user interface with Streamlit  
✅ IMDb rating-based filtering  
✅ Real-time poster fetching using web scraping  
✅ Lightweight and easy to run locally

---

## 🧠 How It Works

- **Input**: A movie title or combination of genres + IMDb rating
- **Processing**: Custom KNN model finds nearest neighbors from dataset
- **Output**: List of recommended movies with titles, IMDb links, ratings, and posters

---

## 📦 Tech Stack

| Technology | Role                      |
|------------|---------------------------|
| `Python`   | Core programming language |
| `Streamlit`| Frontend Web App          |
| `Pillow`   | Poster image rendering    |
| `BeautifulSoup` | HTML parsing (IMDB scraping) |
| `Requests` | Web requests for poster links |
| `Custom KNN` | Movie similarity logic |

---

