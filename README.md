# 🎬 Netflix Movies & TV Shows — Data Analysis

A complete exploratory data analysis (EDA) project on the Netflix Movies and TV Shows dataset using Python. This project covers data cleaning, visualization, and business insight generation.

## 📌 Project Overview

This project analyzes Netflix's content library (8,800+ titles) to uncover patterns in content type, genre distribution, regional content strategy, target audience, and growth trends over time. The goal is to derive actionable business insights from raw, messy real-world data.

## 📂 Dataset

- **Source:** [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) (Kaggle)
- **Size:** 8,807 rows × 12 columns (original)
- **Description:** Contains details of Movies and TV Shows available on Netflix, including title, director, cast, country, date added, release year, rating, duration, genre, and description.

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** — data manipulation & cleaning
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Seaborn** — statistical visualization

## 🧹 Data Cleaning Steps

1. Fixed mislabeled values (duration data found in the `rating` column)
2. Handled missing values in `rating`, `country`, `cast`, `director`, and `date_added`
3. Converted `date_added` to proper datetime format
4. Extracted `year_added` and `month_added` for time-based analysis
5. Split `duration` into separate numeric columns: `duration_minutes` (Movies) and `duration_seasons` (TV Shows)
6. Verified and confirmed zero duplicate records

## 📊 Exploratory Data Analysis

The analysis covers:
- Movies vs TV Shows distribution
- Year-wise content addition trend (2008–2021)
- Top 10 countries producing Netflix content
- Top 10 genres on the platform
- Content rating distribution (audience maturity)
- Movie duration distribution
- TV Show season-count distribution
- Movies vs TV Shows growth trend over time

## 💡 Key Business Insights

1. **Content Mix:** Netflix's library is movie-heavy (~70% Movies vs ~30% TV Shows), though TV Shows have shown more stable growth in recent years.
2. **Expansion Era:** Content additions grew explosively between 2016–2019, aligning with the rise of streaming competition (Disney+, Amazon Prime).
3. **Global Strategy:** India is the second-largest content market after the US, reflecting Netflix's strong investment in regional and international content.
4. **Genre Focus:** "International Movies" is the single largest genre category, reinforcing a localized, globally-diverse content strategy.
5. **Target Audience:** Roughly 61% of content is rated for mature/teen audiences (TV-MA, TV-14), while kids' content makes up only ~10% of the library.
6. **Content Lifecycle:** The median TV Show runs for just 1 season, suggesting Netflix frequently cancels shows early — a pattern often criticized by viewers.
7. **Resilience Post-2020:** TV Show additions remained more stable than Movies during the 2020–2021 decline, highlighting their value for long-term subscriber retention.

## 🎯 Strategic Recommendations

- Increase investment in TV Shows, given their stronger retention value and post-2020 resilience.
- Reassess the early cancellation pattern for new series to improve subscriber trust.
- Continue expanding in high-growth regional markets like India and South Korea.
- Explore growth opportunities in the underserved kids' content segment (~10% of library).

## 📁 Repository Structure

```
netflix-data-analysis/
│
├── README.md
├── netflix_titles.csv
├── netflix_cleaned.csv
├── netflix_analysis.ipynb
├── requirements.txt
└── images/
```

## ▶️ How to Run

```bash
git clone https://github.com/your-username/netflix-data-analysis.git
cd netflix-data-analysis
pip install -r requirements.txt
jupyter notebook netflix_analysis.ipynb
```

## 📬 Connect

Feel free to connect or reach out if you have feedback or questions about this project.
