# IMDb Movie Rating Analysis

This project analyzes the IMDb 5000 Movies dataset to uncover patterns behind highly-rated films. It examines how movie ratings vary across budget, revenue, genre, director performance, and release year trends, supported by visualizations and statistical summaries.

---


## 📂 Repository Structure
```
imdb-movie-rating-analysis/
├── README.md
├── notebook.ipynb
├── requirements.txt
├── data/
│   └── imdb.csv
└── images/
    ├── rating_dist.png
    ├── budget_vs_rating.png
    ├── revenue_vs_rating.png
    ├── top_directors.png
    └── correlations.png
```
---


## 📊 Dataset

- **Source:** Kaggle  
  https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset  
- **Movies Covered:** ~5,000  
- **Period Covered:** 1920–2016  
- **Key Fields:** IMDb score, budget, revenue, genres, directors, etc.

---

## 🎯 Objectives

- Analyze IMDb rating distribution  
- Compare ratings across genres and directors  
- Examine relationships between budget, revenue, and ratings  
- Identify long-term rating trends across decades  
- Highlight top-performing directors and genres  

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Google Colab  

---

## 🔍 Key Insights

- Some directors consistently produce higher-rated films  
- Budget shows a weak relationship with ratings; revenue patterns are more meaningful  
- Certain genres outperform others in average IMDb score  
- Rating trends shift significantly across decades  
- A few outliers break typical budget–rating patterns  

---

## 📁 Visualizations

Available in the `images/` folder:

- Average IMDB Rating Over Years.png
- Average IMDB Rating by Genres.png
- Revenue in Millions vs IMDB Rating.png
- Top 10 Directors by Average IMDB Rating.png
- Top 10 Highest Rated Movies.png 

---

```

## ▶️ How to Run

1. **Clone the repository:**
```bash
   git clone https://github.com/anisahmed01/imdb-movie-rating-analysis
```

2. **Install dependencies:**
```bash
   pip install -r requirements.txt
```

3. **Open the notebook:**
```bash
   jupyter notebook notebook.ipynb
```

4. **Run all cells** to reproduce the analysis.




#### 📘 Project Summary
```
This analysis shows how financial attributes, genres, and creative contributors influence IMDb ratings. Through visual exploration and statistical comparisons, it identifies which directors, movie categories, and production patterns are associated with stronger viewer ratings across nearly a century of cinema.

---

