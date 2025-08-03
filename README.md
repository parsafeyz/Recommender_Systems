# 🎬 Movie Recommendation System

A personalized movie recommender built with Python and 💡 pure data magic. It analyzes your movie ratings, compares them with other users, and serves up the **top picks** just for *you* 🍿

## 🚀 How It Works

This project uses **collaborative filtering** with **Pearson correlation** to match your taste with similar users and recommend movies you’re likely to enjoy.

### 👣 Steps:
1. Load movie and rating data (with genres, titles, and timestamps).
2. Clean and structure the data: extract years, split genres, remove unnecessary fields.
3. Build a user profile from your input ratings.
4. Compare your preferences with others using the **Pearson similarity index**.
5. Score and rank unseen movies based on weighted ratings from similar users.
6. BOOM — top 10 recommendations, fresh and ready.

## 🧠 Tech Stack

- `pandas` for data wrangling  
- `numpy` for math & vectors  
- `matplotlib` for quick visuals  
- Built-in `math.sqrt()` for similarity calculations  

## 💻 Example Input

```python
userInput = [
    {'title':'Toy Story', 'rating':3.5},
    {'title':'Pulp Fiction', 'rating':5},
    {'title':'Akira', 'rating':4.5}
]
