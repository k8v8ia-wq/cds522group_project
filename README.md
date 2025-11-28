# CDS522 Data Analysis Project

This repository contains the source code and data analysis workflow for the CDS522 course project. The project focuses on analyzing movie datasets to investigate the relationship between movie popularity, user ratings, and viewing habits using statistical methods.

## 📁 Project Structure

- **`cds522da.ipynb`**: The main Jupyter Notebook containing data loading, preprocessing, visualization, and statistical analysis.
- **Data Files** (Prerequisites):
  - `movies.csv`: Metadata for over 10,000 movies (including TMDB/IMDB scores).
  - `ratings.csv`: User ratings for specific movies.
  - `users.csv`: User demographic information.
  - `watch_history.csv`: User viewing duration and timestamps.
  - `actors.csv` & `movie_actors.csv`: Actor information and cast associations.
  - `subscription.csv`: User subscription details.

## 🛠️ Technologies & Libraries Used

The analysis is performed using **Python 3**. The following libraries are required to run the notebook:

- **Pandas**: For data manipulation, merging, and aggregation.
- **NumPy**: For numerical operations.
- **Matplotlib & Seaborn**: For data visualization (histograms, scatter plots, boxplots).
- **SciPy**: For statistical testing (Pearson/Spearman correlation, ANOVA).

To install the dependencies, run:
```bash
pip install pandas numpy matplotlib seaborn scipy
