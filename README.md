# EDA on Indian Team ODI Matches (1971 - 2024) - Statistical Analysis & Bayes Modeling

This project presents a comprehensive **statistical analysis** and **probabilistic modeling** of India’s performance in ODI (One Day International) cricket matches from **1971 to 2024**. It uses Python and key data science libraries to explore match trends, player stats, and conditional probabilities with **Bayes' Theorem**.

---

## 📁 Dataset

The dataset includes:

- `odi_Matches_Data.csv`: Match-level details (teams, scores, venues, umpires, toss, results, etc.)
- `odi_Batting_Card.csv`: Individual batting records
- `odi_Bowling_card.csv`: Bowling statistics
- `players_info.csv`: Player metadata

---

## 📊 Analysis Performed

### 1. 🏏 India-Specific Match Analysis
- Filtered matches involving **India**.
- Cleaned missing/null values and removed irrelevant columns.
- Standardized data types for analysis.

### 2. 📈 Descriptive Statistics
- Measures of **central tendency**: Mean, Median, Mode
- Measures of **dispersion**: Range, Standard Deviation, Variance, IQR
- Measures of **shape**: Skewness, Kurtosis
- Correlation Matrix and Heatmap
- Histograms and Box Plots for numeric columns

### 3. 🧠 Bayesian Probability Modeling
- **P(Win | Toss Won)**
- **P(Win | Bat First)** and **P(Win | Bowl First)**
- Scoring Probabilities: 300+, 250–299, <250
- Chasing success rate across target ranges
- Win probabilities vs different opponents
- **Pie Charts** visualizing conditional probabilities

### 4. 🧍 Player Data Analysis
- Distribution of **Batting** and **Bowling Styles**
- Cleaned nulls, dropped irrelevant columns (e.g., `dod`, `image_url`)
- Filled missing values with `"NA"`
- Visualized style distributions using **bar plots**

### 5. 🏏 Batting Performance Analysis
- Cleaned fielders' format and mapped player IDs to names
- Descriptive Stats for `runs`, `balls`, `fours`, `sixes`, `strikeRate`
- Grouped by batsman to compute:
  - **Average** and **Median** Stats
  - Correlation Matrix and Heatmap
  - Distributions & Box Plots for numeric columns
  - **Pair Plot** of performance metrics
- 🏆 Top 10 Lists:
  - Total Runs
  - Average Runs
  - Strike Rate
  - Fours and Sixes
- Top 10 Fielders (dismissal involvement)
- Distribution of Wicket Types

### 6. 🎯 Bowling Performance Analysis
- Cleaned nulls and filtered out bowlers with <30 overs
- Aggregated by bowler:
  - Total Wickets
  - Economy Rate
- Visualizations:
  - Top 10 Indian Bowlers by **Wickets**
  - Top 10 Most **Economical Bowlers**
  - Correlation Heatmap
  - Box Plots for economy, wickets, overs

### 🏆 Bonus Insights
- Indian Captains with Most Wins (Bar Chart)
- Players with Most **Man of the Match** awards (Bar Chart)

---

## 🛠️ Tools & Libraries Used

```bash
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook
```

---

## 👨‍💻 Author
Made with ❤️ by [Vedant-303](https://github.com/Vedant-303)
Cricket buff | Data Science Enthusiast | Pattern Seeker 🧠

### 🔗 Connect with Me
[Vedant Jeughale](https://www.linkedin.com/in/vedantjeughale/)

---

## ⭐ Star this Repository
If you liked the project or found it helpful, consider giving it a ⭐ on GitHub!
