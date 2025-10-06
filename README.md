# 🎬 Movie Ratings Analysis

A comprehensive data analysis project exploring the relationship between critic and audience movie ratings, uncovering trends in genre preferences, runtime impacts, and rating distributions.

---

## 📊 Project Overview

This project analyzes a movie ratings dataset to reveal insights about how films are perceived by critics versus audiences. By examining tomatometer scores, audience ratings, genres, and runtime data, the analysis identifies patterns and trends in movie reception across different dimensions.

**Key Questions Explored:**
- How do critic ratings compare to audience ratings?
- Which genres receive the highest ratings from critics vs. audiences?
- Does movie runtime correlate with rating scores?
- What are the trends in movie releases over time?

---

## 🔍 Dataset

The dataset includes:
- **Movie titles** and release years
- **Genres** (Action, Drama, Comedy, etc.)
- **Tomatometer rating** (critic scores)
- **Audience rating** (user scores)
- **Runtime** (movie duration in minutes)
- Additional metadata

---

## 📈 Visualizations

The project features multiple visualizations to support data-driven insights:

### Rating Analysis
- Distribution of critic ratings (tomatometer)
- Distribution of audience ratings
- Scatter plot: Tomatometer vs. Audience Rating

### Genre Analysis
- Genre distribution across the dataset
- Average ratings by genre (critics and audience)
- Combined bar chart: Critic vs. Audience ratings by genre

### Runtime Analysis
- Runtime distribution histogram
- Scatter plot: Runtime vs. Tomatometer Rating
- Scatter plot: Runtime vs. Audience Rating

### Temporal Trends
- Line plot: Movie release trends over time

---

## 🛠️ Tech Stack

<p align="left">
<img src="https://cdn.simpleicons.org/python/3776AB" width="50" height="50" alt="Python"/>
<img src="https://cdn.simpleicons.org/pandas/150458" width="50" height="50" alt="Pandas"/>
<img src="https://cdn.simpleicons.org/numpy/013243" width="50" height="50" alt="NumPy"/>
<img src="https://cdn.simpleicons.org/plotly/3F4F75" width="50" height="50" alt="Plotly"/>
<img src="https://cdn.simpleicons.org/jupyter/F37626" width="50" height="50" alt="Jupyter"/>
</p>

- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib / Seaborn / Plotly** - Data visualization
- **Jupyter Notebook** - Interactive development environment

---

## 📂 Project Structure

```
movie-ratings-analysis/
├── data/
│   └── movie_ratings.csv          # Raw dataset
├── notebooks/
│   └── analysis.ipynb             # Main analysis notebook
├── visualizations/
│   ├── rating_distribution.png
│   ├── genre_comparison.png
│   └── runtime_analysis.png
├── requirements.txt               # Python dependencies
└── README.md                      # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip or conda

---

## 📊 Key Findings

*This section will be populated with insights from the analysis, such as:*
- Critic vs. audience rating correlations
- Top-rated genres by each group
- Impact of runtime on ratings
- Notable trends in movie releases

---

## 🔮 Future Enhancements
- Add sentiment analysis on movie reviews
- Incorporate box office revenue data
- Build interactive dashboard with Plotly Dash or Streamlit
- Perform time-series forecasting on rating trends
- Add machine learning model to predict ratings

---

## 📧 Contact

namyun.kim@ue-germany.de

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
