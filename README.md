# Taylor Swift: Creative Evolution

## Overview
This project explores the evolution of Taylor Swift’s musical style using Spotify audio features and unsupervised learning techniques.  
I apply **PCA for dimensionality reduction** and **K-means clustering** to identify recurring stylistic groupings and examine how these clusters evolve over time.

## Data
- Spotify audio features (danceability, energy, valence, acousticness, etc.)
- One observation per song across Taylor Swift’s discography
- Data sourced from a pre-collected CSV (no live API calls)

## Methods
- Feature standardization
- Principal Component Analysis (3 components)
- K-means clustering (k = 4, selected via elbow method)
- Temporal analysis of cluster dominance by release year

## Key Findings
- Stylistic change is **gradual**, with overlapping clusters rather than abrupt shifts
- A dominant sound emerges in the mid-career period (≈2012–2019)
- Recent years show increased stylistic diversity and experimentation
- Small outlier clusters represent intentional experimentation rather than noise

## Files
- `TaylorSwift_CreativeEvolution.ipynb` - full analysis and visualizations

## Tools
Python, pandas, scikit-learn, matplotlib, seaborn

## Notes
This project was developed in Google Colab and uploaded to GitHub for sharing and reproducibility.

## Author
Keelin McLoughlin
