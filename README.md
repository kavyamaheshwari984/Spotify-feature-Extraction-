# 🎵 Spotify Tracks Data Analysis

A data analysis project on Spotify tracks using **Python, Pandas, NumPy, and Matplotlib**.

The project explores Spotify audio features, popularity, genres, artists, track duration, and relationships between different audio characteristics.

## 📌 Project Overview

The goal of this project is to clean, analyze, and visualize a Spotify tracks dataset to discover useful patterns and insights.

### Dataset

Spotify Tracks Dataset — Audio Features

The dataset contains information such as:

* Track name
* Artist
* Genre
* Popularity
* Track duration
* Energy
* Danceability
* Loudness
* Tempo
* Acousticness
* Valence
* Explicit content

## 🛠️ Technologies Used

* **Python**
* **Pandas** — Data cleaning and analysis
* **NumPy** — Numerical calculations
* **Matplotlib** — Data visualization

## 🔍 Project Workflow

### 1. Data Cleaning

* Checked missing values
* Removed duplicate records
* Checked data types
* Validated popularity values
* Converted track duration from milliseconds to minutes
* Identified potential outliers using IQR

### 2. Data Analysis

Performed analysis such as:

* Top 10 most popular tracks
* Average popularity by genre
* Artists with the most tracks
* Genres with highest average danceability
* Track count by genre
* Explicit vs non-explicit tracks
* Average energy and danceability by genre
* Popular tracks longer than 5 minutes
* Artists with at least 20 tracks and highest average popularity
* Most popular track from each genre
* Genres with shortest average track duration

### 3. NumPy Analysis

Used NumPy to calculate:

* Mean
* Median
* Standard deviation
* Minimum and maximum
* Percentiles
* Min-Max normalization
* Correlation between energy and danceability

### 4. Data Visualization

Created visualizations using Matplotlib:

* Popularity distribution histogram
* Top 10 genres by average popularity
* Energy vs Danceability scatter plot
* Track duration distribution histogram

## 📊 Sample Visualizations

The project generates visualizations directly from the dataset using Matplotlib.

## 📁 Project Structure

```text
spotify-analysis/
│
├── spotify_analysis.py
├── spotify-tracks-dataset-clean.csv
└── README.md
```

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd spotify-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib
```

### 3. Run the project

```bash
python spotify_analysis.py
```

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Data cleaning with Pandas
* GroupBy and aggregation
* Sorting and filtering datasets
* Working with NumPy arrays
* Statistical calculations
* Correlation analysis
* Data visualization with Matplotlib
* Extracting insights from real-world datasets

## 🚀 Future Improvements

* Add more advanced visualizations
* Build an interactive dashboard
* Perform deeper statistical analysis
* Explore machine learning applications on Spotify data

## 📚 Dataset Source

Kaggle — Spotify Tracks Dataset: Audio Features

---

**Built as a Python data analysis project to practice Pandas, NumPy, and Matplotlib.**
