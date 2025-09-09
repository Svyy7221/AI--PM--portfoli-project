# AI--PM--portfoli-project
AI Movie Recommender – A portfolio project demonstrating how AI Product Managers design recommendation systems using the MovieLens dataset.
# 🎬 AI Movie Recommender System  

## 📖 Project Overview  
Finding a good movie is hard when there are thousands of options.  
This project designs an **AI-powered recommendation system** that suggests movies based on user preferences.  

As an **AI Product Manager**, my focus is not just on coding, but on **framing the problem, defining the AI approach, and selecting success metrics**.  

---

## 🎯 Problem Statement  
- Users often spend too much time searching for movies.  
- Current rule-based systems show only trending or popular movies, not personalized choices.  
- Goal: Deliver **personalized recommendations** that increase user satisfaction and engagement.  

---

## 📊 Dataset  
- Source: [MovieLens Dataset](https://grouplens.org/datasets/movielens/)  
- Contains:  
  - Users  
  - Movies (title, genre, release year)  
  - Ratings (1–5 stars)  
- Size: ~100k ratings across 9,000+ movies  

---

## 🛠️ AI Approach  
1. **Collaborative Filtering**  
   - Recommends movies based on similar users.  
   - Example: If User A and User B have similar tastes, recommend movies liked by User B to User A.  

2. **Content-Based Filtering**  
   - Recommends movies with similar genres, actors, or descriptions.  

3. **Hybrid Model**  
   - Combines collaborative + content-based for better performance.  

---

## 📏 Success Metrics  
To measure the system’s performance, we use:  

- **Precision** → How many recommended movies were actually good?  
- **Recall** → How many good movies did we capture in our recommendations?  
- **Diversity** → Are recommendations varied (not just the same genre)?  
- **Engagement** → Did users actually watch/click the recommendations?  

---

## 🚀 Future Improvements  
- Add **deep learning models** (e.g., neural collaborative filtering).  
- Include **real-time recommendations** based on user behavior.  
- Expand dataset with user demographics.  

---

## 🧑‍💻 Files in This Repo  
- `README.md` → Project documentation (this file).  
- `notebook.ipynb` → (Optional) Sample Python code in Google Colab.  
- `metrics.md` → Explanation of evaluation metrics.  

---

## 💡 Key Takeaway (PM Role)  
This project highlights how an AI Product Manager:  
- Defines the business problem.  
- Chooses an appropriate AI/ML approach.  
- Decides on success metrics.  
- Aligns AI outcomes with **user and business goals**.
## 📂 Dataset

This project uses the [MovieLens dataset](https://grouplens.org/datasets/movielens/).

1. Download the dataset (e.g., `ml-latest-small.zip`).
2. Extract it to your Google Drive or local machine.
3. In Colab, upload it or mount Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
