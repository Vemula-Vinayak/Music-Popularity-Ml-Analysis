# Spotify Audio Feature Analysis & Popularity Prediction

## Overview
This project analyzes Spotify audio features to understand the factors influencing song popularity. Multiple machine learning techniques were applied, including classification, regression, and clustering, with performance comparison and robustness testing.

---

## Dataset
- Spotify Audio Features Dataset (Kaggle)
- Features include: danceability, energy, loudness, valence, tempo, acousticness, etc.
- Target variable: Popularity score

---

## Objectives
- Analyze audio feature correlations with popularity
- Compare classification models
- Predict continuous popularity scores
- Discover natural song groupings
- Evaluate robustness across different seeds
- Build a rule-based mini classifier

---

## Models Implemented

### Classification
- Decision Tree
- Random Forest (Best Performing Model)

### Regression
- Linear Regression

### Clustering
- K-Means (Elbow Method for optimal k)

---

## Key Results

- Random Forest achieved highest and most stable classification accuracy.
- Model performance remained consistent across seeds (0, 21, 42).
- Linear Regression showed moderate correlation for popularity prediction.
- K-Means revealed 3 distinct natural song clusters.
- Audio features significantly influence song popularity.

---

## Mini Classification Tool
A simple rule-based classifier was built using insights:
- High danceability + high energy → Likely Hit
- High acousticness → Not a Hit
- Otherwise → Maybe a Hit

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## How to Run
1. Install dependencies:
   ```
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Open:
   ```
   spotify_ml_analysis.ipynb
   ```
3. Run all cells sequentially.
