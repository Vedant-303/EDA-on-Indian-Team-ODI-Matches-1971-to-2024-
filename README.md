# EDA on Indian Team ODI Matches (1971 - 2024)

This project presents a comprehensive **statistical analysis and probabilistic modeling** of India's performance in ODI (One Day International) cricket matches played between **1971 and 2024**. The analysis uses Python (Pandas, NumPy, Seaborn, Matplotlib) to explore match data, performance trends, and conditional probabilities using **Bayes' Theorem**.

---

## 📁 Dataset

The dataset consists of:
- `odi_Matches_Data.csv`: Contains match-level details (teams, scores, venues, umpires, toss, results, etc.)
- `odi_Batting_Card.csv`: Contains individual batting records
- `odi_Bowling_card.csv`: Contains bowling stats
- `players_info.csv`: Contains player metadata

---

## 📊 Analysis Performed

### 1. 📈 Descriptive Statistics
- Measures of **central tendency**: mean, median, mode
- Measures of **dispersion**: range, standard deviation, variance, IQR
- Measures of **shape**: skewness and kurtosis
- Correlation matrix and heatmap

### 2. 🧠 Probabilistic Modeling
- **Bayesian Probability**:
  - Probability of India winning given toss win
  - Probability of India winning after batting or bowling first
- Venue-based scoring probabilities (300+ and <250 runs)
- Chasing success rates based on target ranges
- Defending totals and success likelihood
- Win probabilities against each opponent team
