# CDS522 Data Analysis Project

This repository contains the source code and data analysis workflow for the CDS522 course project. The project focuses on analyzing movie datasets to investigate the relationship between movie popularity, user ratings, and viewing habits.

## 📁 Project Structure

- **`cds522da.ipynb`**: The main Jupyter Notebook containing data loading, preprocessing, visualization, and statistical analysis.
- **Data Files** (Prerequisites):
  - `movies.csv`: Metadata for over 10,000 movies.
  - `ratings.csv`: User ratings for specific movies.
  - `users.csv`: User demographic information.
  - `watch_history.csv`: User viewing duration and timestamps.
  - `actors.csv` & `movie_actors.csv`: Actor information and cast associations.
  - `subscription.csv`: User subscription details.

## 🛠️ Technologies & Libraries Used

The analysis is performed using **Python 3**. The following libraries are required to run the notebook:

- **Pandas**: For data manipulation and aggregation.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization (histograms, scatter plots, boxplots).
- **SciPy**: For statistical testing (Pearson/Spearman correlation, ANOVA, Shapiro-Wilk test).

```bash
pip install pandas numpy matplotlib seaborn scipy
Key Analysis Dimensions
The notebook covers the following key analytical steps:

Data Preprocessing:

Cleaning missing values.

Merging datasets (Movies, Ratings, Watch History).

Data transformation (Log transformation for skewed popularity distributions).

Dimension 1: Popularity vs. Ratings Analysis:

Investigating the correlation between TMDB Popularity and User Ratings.

Visualizations: Scatter plots with trend lines, boxplots comparing popularity groups.

Statistical Tests:

Pearson & Spearman Correlation coefficients.

ANOVA Test: Investigating if significant rating differences exist across different popularity groups (Low, Medium-Low, Medium-High, High).

📈 Summary of Findings
Based on the statistical outputs within the notebook:

Correlation: A moderate positive correlation exists between TMDB/IMDB scores and user ratings.

Group Differences: The ANOVA test (F-statistic: 2.938, P-value: 0.035) suggests significant differences in average ratings across different popularity tiers.

Extreme Values: Movies in the top 1% of popularity tend to have a significantly higher average rating (Mean: 8.05) compared to the rest of the dataset (Mean: 5.88).

🚀 How to Run
Clone this repository.

Ensure all CSV data files are in the same directory as the notebook.

Launch Jupyter Notebook:

Bash

jupyter notebook cds522da.ipynb
Run all cells to reproduce the analysis and visualizations.

👥 Authors
Group Members - CDS522

WU Ke (5582625)

ZHUANG Jingkun (5500938)

ZHENG Guangyuan (5541645)

GAN Haohong (5527986)

ZHENG Ye (5525108)
