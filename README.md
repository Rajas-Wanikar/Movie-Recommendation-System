# 🎬 Movie Recommendation System

This is a **Content-Based Movie Recommender System** that suggests movies similar to the one you select. It uses **Natural Language Processing (NLP)** techniques to analyze movie metadata and return recommendations based on cosine similarity.

![System Screenshot]((https://github.com/Rajas-Wanikar/Movie-Recommendation-System/blob/main/Image_of_the_system.png))

---

## 🔍 Types of Recommender Systems
This project focuses on the **Content-Based** recommendation method. Below are the common types of recommender systems:

1. **Content-Based Filtering** – Recommends items similar to those the user liked in the past.
2. **Collaborative Filtering** – Recommends items liked by similar users.
3. **Hybrid System** – Combines both content-based and collaborative filtering.

---

## 🧠 Project Flow

1. **Data Collection**  
   Utilized datasets from [TMDB (The Movie Database)](https://www.themoviedb.org/).

2. **Preprocessing**  
   Cleaned the data and created a combined metadata string for each movie using features like genres, cast, crew, and keywords.

3. **Model Building**  
   - Used `CountVectorizer` to convert text data into a 5000-dimensional numerical vector.
   - Calculated **cosine similarity** between movie vectors to determine closeness.

4. **Website Deployment**  
   Frontend built using **Streamlit** and deployed via local/server environment using **PyCharm**.

---

## 🧰 Technologies Used

- **Frontend**: Streamlit  
- **Backend**: Python (Jupyter Notebook / PyCharm)
- **Libraries**: 
  - Pandas
  - Scikit-learn
  - Pickle
  - Requests (for fetching movie posters from TMDB API)
- **Modeling**:
  - CountVectorizer (from sklearn)
  - Cosine Similarity

---

## 📁 Files in This Repository

| File/Folder Name | Description |
|------------------|-------------|
| `App.py` | Main Streamlit app code to run the recommender UI |
| `Movie Recommendation System.ipynb` | Jupyter notebook for data exploration, preprocessing, and model building |
| `Image_of_the_system.png` | Screenshot of the application for preview |
| `README.md` | Project documentation |

---

