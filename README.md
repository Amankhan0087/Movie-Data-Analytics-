<div align="center">

# 🎬 Movie Data Analytics

### Comprehensive Exploratory Data Analysis on Movie Performance, Ratings & Genre Trends

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=for-the-badge)](https://seaborn.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 🔍 Overview

This project performs a full **Exploratory Data Analysis (EDA)** on a comprehensive movie database (`mymoviedb.csv`) to uncover what drives a film's success — from budget and revenue correlations to genre popularity and audience reception trends.

The analysis answers critical questions like:
- Which genres consistently generate the highest revenue?
- Is there a strong correlation between budget and box office performance?
- How have movie production volumes and ratings evolved over the years?
- What separates a high-popularity film from a critically acclaimed one?
- Which movies are outliers — low budget, high revenue?

This project is a great hands-on resource for developing **data wrangling, statistical analysis, and visualization** skills using real-world entertainment industry data.

---

## 🗂️ Project Structure

```
Movie-Data-Analytics/
│
├── 📓 Movie Data Analytics Project.ipynb   # Main analysis notebook
├── 📄 mymoviedb.csv                        # Movie dataset
└── 📝 README.md                            # Project documentation
```

---

## 📌 Key Analysis Areas

| Area | Description |
|---|---|
| 🎭 **Genre Analysis** | Most popular and highest-grossing genres |
| 💰 **Budget vs. Revenue** | Correlation between production cost and box office return |
| ⭐ **Ratings & Scores** | Distribution of IMDB scores and audience reception |
| 📅 **Year-wise Trends** | How movie production volume has changed over decades |
| 🔥 **Popularity Metrics** | What makes a movie trend — votes, score, revenue |
| 🏆 **Top Movies** | Highest rated, most popular, and highest grossing films |
| 📉 **Outlier Detection** | Low-budget blockbusters and overbudget flops |
| ⏱️ **Runtime Analysis** | Does movie length affect ratings or revenue? |

---

## 📊 Visualizations Included

- **Revenue Distribution** — Histogram of movie revenues with skew analysis
- **Budget vs. Revenue Scatter Plot** — Identifying profitable vs. loss-making films
- **Genre Frequency Bar Chart** — Most produced and most profitable genres
- **Top 10 Highest Rated Movies** — Horizontal bar chart
- **Top 10 Most Popular Movies** — By popularity score
- **Movies Released Per Year** — Line chart showing industry growth
- **IMDB Score Distribution** — Bell curve analysis of ratings
- **Correlation Heatmap** — Numerical feature relationships (budget, revenue, popularity, votes)
- **Runtime vs. Rating** — Scatter plot to check if longer movies rate better
- **Votes vs. Popularity** — Does vote count determine popularity?

---

## 🧹 Data Cleaning & Preprocessing

```
Raw mymoviedb.csv
       ↓
  Data Cleaning
  ├── Drop duplicate movie entries
  ├── Handle missing values (budget, revenue, genres)
  ├── Standardize column names (snake_case)
  └── Convert Release_Date to datetime format
       ↓
  Feature Engineering
  ├── Extract Release Year & Decade
  ├── Calculate ROI = (Revenue - Budget) / Budget × 100
  ├── Create profit/loss binary flag
  └── Parse multi-value genre strings into lists
       ↓
  EDA & Visualization
       ↓
  Insights & Reporting
```

---

## 📁 Dataset Overview

**File:** `mymoviedb.csv`

A movie database containing detailed metadata on thousands of films across multiple decades and genres.

| Column | Description |
|---|---|
| `Title` | Name of the movie |
| `Release_Date` | Date the movie was released |
| `Overview` | Short plot summary |
| `Popularity` | Popularity score (based on views, votes, activity) |
| `Vote_Count` | Total number of audience votes |
| `Vote_Average` | Average audience rating (out of 10) |
| `Original_Language` | Language of the original film |
| `Genre` | One or more genres (Action, Drama, Comedy, etc.) |
| `Poster_Url` | URL link to the movie poster |

---

## ⚙️ Tech Stack

| Tool | Purpose |
|---|---|
| `Python 3.9+` | Core programming language |
| `Pandas` | Data loading, cleaning, and manipulation |
| `NumPy` | Numerical operations and array processing |
| `Matplotlib` | Base layer for all visualizations |
| `Seaborn` | Statistical plots and aesthetic styling |
| `Jupyter Notebook` | Interactive analysis and storytelling environment |

---

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.9+
pip
```

### Installation & Setup

```bash
# 1. Clone the repository
git clone https://github.com/Amankhan0087/Movie-Data-Analytics-.git
cd Movie-Data-Analytics-

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# 3. Launch the notebook
jupyter notebook "Movie Data Analytics Project.ipynb"
```

---

## 💡 Key Insights

- ✅ **Action and Adventure** genres dominate global box office revenue
- ✅ **Higher budget films** generally yield higher revenue, but ROI is often better for **mid-budget films**
- ✅ **Vote count** is a stronger predictor of popularity than average rating alone
- ✅ Movie production has seen **exponential growth** post-2000, with a dip during COVID-19 years
- ✅ **English-language films** make up the overwhelming majority of high-popularity entries
- ✅ Films with ratings between **7.0–8.5** tend to have the best balance of popularity and critical reception
- ✅ **Runtime sweet spot** for high-rated films is typically between **90–150 minutes**

---

## 🔭 Future Roadmap

- [ ] 🤖 Build an **ML model to predict movie success** (classification: hit / flop)
- [ ] 📊 Create an interactive **Streamlit or Power BI dashboard**
- [ ] 🌐 Add **TMDB API integration** for live, auto-updating data
- [ ] 🎯 Implement **content-based movie recommendation system**
- [ ] 🧠 Apply **NLP on movie overviews** for sentiment and theme clustering
- [ ] 📈 Add **decade-by-decade trend analysis** for deeper historical insights
- [ ] 🗺️ Include **country-wise production analysis** with geographic maps

---

## 🤝 Contributing

Contributions are welcome! Here's how:

```bash
# 1. Fork the repository
# 2. Create your feature branch
git checkout -b feature/your-feature-name

# 3. Commit your changes
git commit -m "Add: description of your changes"

# 4. Push to your branch
git push origin feature/your-feature-name

# 5. Open a Pull Request
```

> For major changes, please open an **issue** first to discuss.

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

<div align="center">

**Aman Khan**

*AI Engineer | Data Analyst | Python Developer*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-khan-data-scientist/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Amankhan0087)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://amankhan.online)

</div>

---

<div align="center">

⭐ **Found this project useful? Drop a star to show your support!** ⭐

</div>
