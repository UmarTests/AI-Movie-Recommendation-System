# 🎬 Hybrid AI Movie Recommendation System
*Award-winning ML project for Hollywood films released before 2015*

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red?logo=streamlit)
![Status](https://img.shields.io/badge/Academic_Grade-A-green)
![License](https://img.shields.io/badge/License-MIT-lightgrey)
![Built With](https://img.shields.io/badge/Built%20By-Umar-lightblue)

---

## 🏆 Project Highlights

- 🥇 **Best BSc Project (Grade A)** — Selected among top 1% of cohort  
- 🎯 **2 Competition Finalist** — Showcased at:
  - Project Expo Chandigarh University 2025 (Finalist, offered direct interview by one of the judges)
  - National Science Day 2025 (Finalist)
- 🎓 Built with: Python, Streamlit, Scikit-learn, Pandas, MovieLens 20M
- 🕰️ Optimized for **films released before 2015** (when user ratings are more consistent)

---

## 📖 Overview

This hybrid movie recommender system blends both collaborative and content-based filtering to recommend relevant Hollywood films.

It was trained on over **27,000 movies** and **20 million user ratings**, using:
- 🔗 **KNN-based collaborative filtering** for taste matching
- 🧠 **TF-IDF + Cosine similarity** for genre-based similarity
- ⚖️ **Hybrid weighting** to balance both approaches

> “Particularly excels with pre-2015 classic cinema, where user behavior patterns are strongest.”

---

## 🧠 System Architecture

```mermaid
graph LR
A[🎬 User Input] --> B[🔍 Normalized Title Matching]
B --> C{🤖 Hybrid Recommendation Engine}
C --> D[👥 Collaborative Filtering (KNN)]
C --> E[📚 Content-Based (Cosine Similarity)]
D --> F[🎯 Weighted Results]
E --> F
```
## 📊 Model Performance

| Metric    | Score              |
|-----------|--------------------|
| RMSE      | 0.87               |
| Coverage  | 94% (pre-2015)     |
| Diversity | 0.68               |

---

## 🚀 How to Run Locally

```bash
git clone https://github.com/UmarTests/AI-Movie-Recommendation-System.git
cd AI-Movie-Recommendation-System
pip install -r requirements.txt
streamlit run Movei_rec_app.py
```
## 🛠 Key Features

- 🎯 Personalized suggestions using hybrid ML techniques  
- 🗃️ Trained on MovieLens 20M dataset  
- 🧩 Robust against title misspellings  
- 🖥️ Optional Streamlit UI for end-user interaction  
- 🎥 Focused on films released before 2015 for rating strength  

---

## 🎓 Academic Recognition

- 📌 Capstone Project for BSc in Computer Science  
- 🏅 Grade A and Best Project Award  
- 🏆 Finalist and awardee in multiple competitions  
- 🧠 Demonstrated core ML techniques: matrix factorization, sparse vectors, cosine distance  

---

## ✨ Why This Project Stands Out

```diff
+ Demonstrates mastery in applied ML and recommender systems  
+ Focused on pre-2015 cinema: real-world data quirks handled  
+ End-to-end ready: From notebook → deployable UI  
+ Git versioned, modular Python architecture  
```

---

## 📂 File Structure

```bash
├── Movie_Rec_proj.py           # Recommender engine logic  
├── Movei_rec_app.py            # Streamlit UI (optional)  
├── recommendation_system.py    # Core similarity functions  
├── requirements.txt            # All dependencies  
├── README.md                   # You're reading it  
```

---

## 📫 Let’s Connect

- 🔗 LinkedIn  
- 🌐 Portfolio  
- 📧 your.email@example.com  

---

## 📄 License

**MIT License** – Free to use, fork, and learn from.

> For detailed methodology and dataset processing, see the [📄 Project Report (PDF)](https://github.com/UmarTests/AI-Movie-Recommendation-System/blob/main/YOUR_REPORT_FILE.pdf)

---

## 🌐 INTRO LANDING PAGE (For GitHub Pages or `index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Hybrid Movie Recommendation System</title>
  <style>
    body { font-family: sans-serif; background: #111; color: #eee; padding: 2rem; text-align: center; }
    h1 { font-size: 2.5rem; }
    p { font-size: 1.2rem; }
    .gif { margin-top: 2rem; }
    a.button {
      display: inline-block; padding: 0.8rem 1.5rem; background: crimson;
      color: white; text-decoration: none; border-radius: 8px; margin-top: 1rem;
    }
  </style>
</head>
<body>
  <h1>🎬 Hybrid Movie Recommendation System</h1>
  <p>An award-winning AI engine for recommending movies released before 2015.</p>
  <p><strong>Built with:</strong> Python, Streamlit, scikit-learn, MovieLens</p>

  <div class="gif">
    <img src="https://media.giphy.com/media/3o7TKsrfldmm8cukWs/giphy.gif" width="480" />
  </div>

  <a href="https://github.com/UmarTests/AI-Movie-Recommendation-System" class="button">🔗 View on GitHub</a>
</body>
</html>
```
