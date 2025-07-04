# Movie Recommendation System using Collaborative Filtering

This project demonstrates a basic **collaborative filtering**-based movie recommender system using the **MovieLens 100k** dataset. It calculates user-user similarity using **cosine similarity** and recommends movies based on ratings by similar users.

---

## 📚 Dataset

- **Source:** [MovieLens 100k](https://grouplens.org/datasets/movielens/100k/)
- **Files Used:**
  - `u.data`: User ratings (user_id, item_id, rating, timestamp)
  - `u.item`: Movie metadata (item_id, movie title, genres, etc.)

---

## 🚀 Features

- Load and preprocess the MovieLens 100k dataset
- Create a user-item matrix
- Compute cosine similarity between users
- Generate personalized movie recommendations
- Filter unseen movies for each user

---

## 🧪 How It Works

1. Load and clean the datasets.
2. Create a user-item matrix with ratings.
3. Use cosine similarity to find similar users.
4. Recommend movies that similar users liked but the target user hasn't seen.

---

## 🧠 Algorithms Used

- **Cosine Similarity** from `sklearn`
- **Collaborative Filtering** based on nearest neighbors

---

## 📈 Output

- Recommendations for a sample user
- Similarity matrix (optional)
- Ratings matrix overview

---

## 📁 Files

- `Experiment11.ipynb` – Jupyter notebook containing the full recommendation pipeline
- `README.md` – Project overview
- `requirements.txt` – Python dependencies

---

## 🔧 Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
📦 Dependencies
txt
Copy
Edit
pandas
numpy
scikit-learn
