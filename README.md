
# Spotify Song Popularity Analysis

## Overview

This project investigates which Spotify song characteristics are associated with popularity using statistical analysis and machine learning techniques.

The analysis explores whether audio features such as danceability, energy, loudness, acousticness, and instrumentalness can predict a song's popularity.

---

## Research Question

**Which Spotify audio features are most strongly associated with song popularity?**

---

## Dataset

This project uses two publicly available Spotify datasets from Kaggle.

- Spotify Tracks Attributes and Popularity
- Spotify Dataset

Over **80,000 songs** were analyzed after data cleaning.

---

## Project Workflow

### Data Cleaning

- Removed duplicate songs
- Removed missing values
- Filtered unrealistic values
- Converted duration into minutes
- Created popularity categories

---

### Exploratory Data Analysis

The project investigates

- Popularity distribution
- Audio feature distributions
- Correlation heatmap
- Genre popularity
- Explicit vs Non-explicit songs

---

### Statistical Methods

- Pearson Correlation
- Cohen's d Effect Size
- Multiple Linear Regression
- Feature Standardization

---

## Key Findings

- Audio features alone explain only **7.4%** of song popularity.

- Instrumentalness has the strongest negative relationship with popularity.

- Danceability and loudness have weak positive relationships.

- Genre explains popularity much better than audio features.

- Popularity appears to be driven largely by external factors such as marketing, artist recognition, and audience.

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-Learn

---


