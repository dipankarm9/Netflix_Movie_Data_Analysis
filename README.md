# 🎥 Netflix Movie Data Analysis 📊

Welcome to the **Netflix Movie Data Analysis** project! This repository contains a comprehensive analysis of Netflix movie data, focusing on genres, popularity, votes, and release trends. Below, you'll find a step-by-step guide to the project, including the tools and techniques used.

---

## 📝 Project Overview

The goal of this project is to analyze Netflix movie data to gain insights into:
- 🎬 **Genres**: Most frequent and popular genres.
- 🌟 **Popularity**: Movies with the highest and lowest popularity.
- 🗳️ **Votes**: Distribution and categorization of votes.
- 📅 **Release Trends**: Yearly trends in movie releases.

---

## 📂 Dataset Overview

The dataset contains information about movies available on Netflix, including:
- **Release_Date**: Year of release.
- **Title**: Movie title.
- **Popularity**: Popularity score.
- **Vote_Count**: Number of votes.
- **Vote_Average**: Average vote categorized into four labels: `Not Popular`, `Below Average`, `Average`, and `Popular`.
- **Genre**: Movie genres (exploded to have one genre per row).

---

## 🛠️ Tools and Libraries

- 🐍 **Python**: For data manipulation and analysis.
- 🐼 **Pandas**: For data cleaning and transformation.
- 📊 **Matplotlib & Seaborn**: For data visualization.
- 🔢 **NumPy**: For numerical operations.

---

## 🚀 Step-by-Step Process

### 1️⃣ **Data Cleaning**
- 🧹 Removed commas from `Vote_Count` and `Vote_Average` columns and converted them to numeric types.
- 🗓️ Converted `Release_Date` to datetime format and extracted the year.
- 🗑️ Dropped unnecessary columns: `Overview`, `Original_Language`, and `Poster_Url`.

### 2️⃣ **Data Transformation**
- 🏷️ Categorized `Vote_Average` into four labels: `Not Popular`, `Below Average`, `Average`, and `Popular`.
- 🔄 Split the `Genre` column into lists and exploded the dataframe to have one genre per row.
- 🗂️ Converted `Genre` to a categorical data type.

### 3️⃣ **Exploratory Data Analysis (EDA)**
- 🔍 Checked for duplicates and missing values.
- 📈 Explored summary statistics and unique values for each column.

### 4️⃣ **Data Visualization**
- 📊 Visualized the distribution of genres to identify the most frequent genre.
- 🌟 Analyzed the distribution of votes and popularity.
- 🎥 Identified the most and least popular movies and their genres.
- 📅 Examined the trend of movie releases over the years.

---

## 🔑 Key Insights

1. 🎭 **Most Frequent Genre**: Identified the most common genre of movies released on Netflix.
2. 🗳️ **Genres with Highest Votes**: Found genres with the highest average votes.
3. 🌟 **Most Popular Movie**: Discovered the movie with the highest popularity score and its genre.
4. 📉 **Least Popular Movie**: Found the movie with the lowest popularity score and its genre.
5. 📅 **Year with Most Movies**: Determined the year with the highest number of movie releases.

---

## 📈 Visualizations

- **Genre Distribution**: Bar chart showing the frequency of each genre.
- **Vote Distribution**: Count plot of categorized votes.
- **Popularity Trends**: Insights into the most and least popular movies.
- **Release Trends**: Histogram of movie releases by year.

---

## 🏁 Conclusion

This project provides valuable insights into Netflix movie trends, helping stakeholders make data-driven decisions about content strategy and audience preferences. 🎉

---

## 📂 Repository Structure

- `movie-data-analysis-netflix.ipynb`: Jupyter Notebook containing the full analysis.
- `README.md`: Project documentation (this file).
- `resources/`: Folder containing the dataset (`mymoviedb.csv`).

---

## 🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests to improve the analysis or add new features! 😊

---

## 📧 Contact

For any questions or feedback, please reach out via GitHub Issues. 🚀