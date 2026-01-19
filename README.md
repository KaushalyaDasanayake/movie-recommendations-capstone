# Movie Recommendation System — Machine Learning Capstone

## Project Overview

This project builds a movie recommendation system using collaborative filtering techniques to recommend movies based on user similarity and item similarity. It also explores matrix factorization using SVD to learn latent features of users and movies.

The objective is to simulate real-world recommender systems used in streaming platforms.

---

## Problem Statement

Given historical user–movie ratings, the goal is to predict how users would rate unseen movies and recommend the Top-N most relevant movies for each user.

This simulates real-world recommendation systems used in streaming platforms such as Netflix and Amazon Prime.

---

## Dataset

* Dataset: MovieLens 100K
* Users: 943
* Movies: 1,682
* Ratings: 100,000
* Rating scale: 1–5

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## System Architecture

Raw Ratings Data
        ↓
User–Item Matrix Construction
        ↓
Similarity Models (User / Item)
        ↓
Matrix Factorization (SVD)
        ↓
Predicted Ratings Matrix
        ↓
Top-N Recommendation Function

---

## Methods Implemented

1. Popularity-Based Recommendation
2. User-Based Collaborative Filtering (Cosine Similarity)
3. Item-Based Collaborative Filtering
4. Matrix Factorization using SVD

---

## Data Processing

* Merged ratings and movie metadata
* Built user–item rating matrix
* Filled missing ratings with zeros for matrix factorization
* Mean-centered ratings for SVD

---

## Evaluation

* RMSE — evaluates accuracy of predicted ratings
* Precision@K — evaluates quality of Top-N recommendations

---

## Limitations & Future Work

* Cold-start problem not handled for new users or movies
* No content-based features (genres, tags)
* Could improve using hybrid recommendation methods
* Could deploy model using FastAPI as REST service

---

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open `notebook.ipynb` and run all cells.

---

## What I Learned

* Working with sparse user–item matrices
* Similarity-based recommendation techniques
* Model-based recommendation using matrix factorization
* Evaluation of recommender systems

---

## Contact

**Kaushalya Rathnayake**
Software Engineer with growing focus on Machine Learning GitHub: https://github.com/KaushalyaDasanayake LinkedIn: https://www.linkedin.com/in/kaushalya-rathnayake-d/
