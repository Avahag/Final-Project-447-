
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

## 📊 Distribution of Song Popularity

<img width="866" height="276" alt="image" src="https://github.com/user-attachments/assets/3e906211-6eb6-436d-bffd-dcb3804d5e62" />




The histogram and boxplot show that most Spotify songs have popularity scores between **20 and 50**, while only a small fraction achieve very high popularity. The average popularity score is **37.1**, which is nearly identical to the median (**37**), indicating that the overall distribution is fairly balanced despite a small number of highly popular songs.

### Key Takeaways
- Most songs achieve only moderate popularity.
- Extremely popular songs are relatively rare.
- The distribution suggests that identifying factors associated with highly popular songs is an important objective of the analysis.

## 🎵 Distribution of Audio Features

The histograms reveal that different musical characteristics follow different distributions.
<img width="758" height="285" alt="image" src="https://github.com/user-attachments/assets/2ba1fa6f-68ac-4717-a907-83270808670c" />



### Key Takeaways
- Spotify songs represent a wide variety of musical styles.
- Several variables are non-normal, emphasizing the importance of interpreting statistical relationships carefully.
- Understanding these distributions provides context for the correlation and regression analyses that follow.


## 🔥 Correlation Between Audio Features and Popularity
<img  width="866" height="500" alt="image" src="https://github.com/user-attachments/assets/f4141f03-23bb-4b59-8771-529b0e2e3955" />

### Key Takeaways
- No audio feature is a strong predictor of popularity.
- Instrumental songs tend to be slightly less popular.
- Danceability and loudness show weak positive relationships.
- Correlations among predictors motivate the use of multiple linear regression.

## 🎤 Popularity by Explicit Content

<img  width="866" height="500" alt="image" src="https://github.com/user-attachments/assets/d3a037fe-3b49-41c1-a2b8-49148d27df53" />


### Key Takeaways
- Explicit songs are slightly more popular on average.
- The effect size is small.
- Explicit content alone is not a strong predictor of song popularity.

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


