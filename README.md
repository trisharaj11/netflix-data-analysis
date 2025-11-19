# 📺 Netflix Data Analysis  

This project performs a complete **Exploratory Data Analysis (EDA)** on the **Netflix Titles Dataset**, including data cleaning, transformation, and visualizations using Python.  
The goal is to understand trends in Netflix content such as ratings, genres, duration, release patterns, and country-wise contributions.

Project created entirely in **Google Colab**.

---

## 📂 Project Structure

netflix-data-analysis/
 netflix_project.ipynb # Main Jupyter Notebook (full analysis)
 netflix_titles.csv # Dataset used for analysis
content_rating_pie.png # Content rating pie chart
movie_dur_hist.png # Movie duration histogram
movies_tv_shows_comp.png # Movie vs TV show genre comparison
movies_vs_tv.png # Movies vs TV shows count
release_year_vs_show.png # Release year trend
top10_countries.png # Top 10 countries producing Netflix content
netflix_project.zip # Compressed version of project files

##📊 Dataset Information

**Dataset:** Netflix Movies and TV Shows Dataset  
**Source:** Public dataset containing Netflix titles.

### 🔸 Dataset Columns

| Column | Description |
|--------|-------------|
| show_id | Unique identifier |
| type | Movie or TV Show |
| title | Name of the content |
| director | Director(s) involved |
| cast | Actors/actresses |
| country | Country of origin |
| date_added | Date added on Netflix |
| release_year | Original release year |
| rating | Content maturity rating |
| duration | Duration (min/seasons) |
| listed_in | Genre information |
| description | Summary of the title |

---

## 📈 Visualizations & Insights

### 1️⃣ **Content Rating Distribution**  
📌 *File:* `content_rating_pie.png`  
Shows how content is rated (e.g., TV-MA, TV-14, PG, etc.).

---

### 2️⃣ **Movie Duration Distribution**  
📌 *File:* `movie_dur_hist.png`  
Analyzes typical duration ranges of movies.

---

### 3️⃣ **Movies vs TV Shows Count**  
📌 *File:* `movies_vs_tv.png`  
Displays how many movies and TV shows exist on Netflix.

---

### 4️⃣ **Genre Comparison Between Movies & TV Shows**  
📌 *File:* `movies_tv_shows_comp.png`  
Shows which genres dominate movies and which dominate TV shows.

---

### 5️⃣ **Release Year Trend**  
📌 *File:* `release_year_vs_show.png`  
Shows historical patterns of Netflix releases.

---

### 6️⃣ **Top 10 Countries Producing the Most Content**  
📌 *File:* `top10_countries.png`  
Shows which countries contribute the most content to Netflix.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/trisharaj11/netflix-data-analysis.git
