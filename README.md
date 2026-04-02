# 🎬 Movie Recommender System

A content-based movie recommendation system that suggests movies similar to the one selected by the user. Built using machine learning and natural language processing techniques.

---

## 📌 Features

- Recommends top similar movies based on user input
- Uses movie metadata like genres, keywords, cast, and crew
- Fast and efficient similarity computation
- Simple and interactive interface (Streamlit / Flask if used)

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Streamlit 

---

## 📂 Dataset

- TMDB 5000 Movie Dataset
- Includes:
  - Movies metadata
  - Credits (cast & crew)

---

## ⚙️ How It Works

1. Data preprocessing:
   - Merge datasets
   - Handle missing values
   - Extract important features (genres, keywords, cast, crew)

2. Feature Engineering:
   - Convert text data into tags
   - Apply stemming

3. Vectorization:
   - Use CountVectorizer / TF-IDF

4. Similarity Calculation:
   - Cosine similarity is used to find similar movies

5. Recommendation:
   - Top 5 similar movies are displayed

---

## ▶️ Installation & Setup

```bash
git clone https://github.com/raghav88raghu/Movie-Recommender-System.git
cd movie-recommender
pip install -r requirements.txt