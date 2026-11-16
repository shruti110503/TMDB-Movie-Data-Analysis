# 🎬 TMDB Movie Data Analysis

An Exploratory Data Analysis (EDA) project on the TMDB movie dataset using Python to uncover insights into movie popularity, genres, budgets, and revenue.

## 📌 Project Overview

This project analyzes movie data from 1960 to 2015 to identify trends and relationships in the movie industry. It explores how movie popularity relates to revenue, identifies the most frequently produced genres, and investigates the relationship between movie budgets and box office performance.

## 🎯 Research Questions

1. Do movies with high popularity achieve higher revenue?
2. What are the most frequently produced movie genres?
3. Is there a correlation between a movie's budget and its revenue?

## 📂 Dataset Information

- **Dataset:** TMDB Movies Dataset
- **Source:** [Kaggle – TMDB Movie Metadata](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
- **Time Period:** 1960–2015
- **Initial Records:** 10,866
- **Records After Cleaning:** 10,840
- **Initial Columns:** 21
- **Final Columns:** 10

The dataset includes movie titles, genres, popularity, budget, revenue, runtime, ratings, release dates, and other movie-related attributes.

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Analysis & Methodology

### 1. Data Wrangling
- Loaded and explored the TMDB dataset.
- Examined data structure, columns, and data types.
- Identified missing values and duplicate records.

### 2. Data Cleaning
- Removed duplicate records.
- Dropped unnecessary columns.
- Handled missing values.
- Processed categorical data containing multiple values separated by `|`.
- Converted the release date column into an appropriate date format.
- Created a new `profit` column using:

  `Profit = Revenue - Budget`

- Categorized movie ratings and profits for further analysis.

### 3. Exploratory Data Analysis (EDA)

**Q1. Do movies with high popularity achieve higher revenue?**

Finding: More popular movies generate considerably higher revenue than less popular movies.

**Q2. What are the most frequently produced movie genres?**

Findings:
- Drama, Comedy, and Action are the three most frequently occurring genres.
- Drama accounts for approximately 22.6% of the movies analyzed.

**Q3. Is there a correlation between a movie's budget and its revenue?**

Finding: Movie budgets and revenues show a positive correlation, indicating that movies with higher budgets generally tend to generate higher revenue, although some outliers exist.

## 📈 Key Insights

- Movies with higher popularity tend to generate higher revenue.
- Drama is the most frequently represented genre in the dataset.
- Comedy and Action are also among the most popular genres.
- Movie budget and revenue have a positive relationship.
- Exploratory data analysis helps identify patterns and relationships within movie industry data.

## 📁 Project Structure

```text
TMDB-Movie-Data-Analysis/
│
├── TMDB-dataset-analysis.ipynb
├── tmdb-movies.csv
└── README.md
```

## 🚀 How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/shruti110503/TMDB-Movie-Data-Analysis.git
```

**2. Navigate to the project directory**

```bash
cd TMDB-Movie-Data-Analysis
```

**3. Install the required libraries**

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**4. Launch Jupyter Notebook**

```bash
jupyter notebook
```

**5. Open and run `TMDB-dataset-analysis.ipynb`.**

Make sure the dataset file `tmdb-movies.csv` is present in the same directory.

## 🙌 Acknowledgements

- [The Movie Database (TMDB)](https://www.themoviedb.org/)
- [TMDB Movie Metadata – Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata)

---

**Author:** Shruti Shukla
