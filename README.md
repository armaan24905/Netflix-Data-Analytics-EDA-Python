# 🎬 Movie Database Exploratory Data Analysis (EDA)

An end-to-end Exploratory Data Analysis (EDA) project built using **Python**, **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**. This project focuses on cleaning, transforming, and analyzing a movie dataset to discover meaningful insights about movie genres, popularity, ratings, and release trends through data visualization.

---

# 📌 Project Overview

The primary objective of this project is to demonstrate the complete workflow of a data analytics project, starting from loading a raw dataset to generating meaningful business insights using exploratory data analysis.

The dataset was cleaned, transformed, and analyzed using industry-standard Python libraries. Various visualizations were created to understand genre distribution, movie popularity, vote categories, and release year trends.

This project highlights fundamental data analytics skills such as data preprocessing, feature engineering, visualization, and insight generation.

---

# 🎯 Objectives

* Load and inspect the movie dataset.
* Understand the structure and quality of the data.
* Perform data cleaning and preprocessing.
* Remove unnecessary columns.
* Convert date columns into a usable format.
* Categorize movie ratings for analysis.
* Transform genre data for better visualization.
* Perform Exploratory Data Analysis (EDA).
* Generate meaningful visualizations.
* Extract useful business insights.

---

# 📂 Dataset

**Dataset Name:** `mymoviedb.csv`

The dataset contains movie-related information including:

* Title
* Genre
* Popularity
* Vote Average
* Release Date
* Overview
* Original Language
* Poster URL

During preprocessing, only the relevant analytical features were retained.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Import Libraries

Imported all required Python libraries for data analysis and visualization.

## 2. Load Dataset

Loaded the dataset using Pandas and verified that it was successfully imported into a DataFrame.

## 3. Data Exploration

Performed an initial inspection of the dataset using:

* `head()`
* `info()`
* `describe()`
* `columns`
* Duplicate record checking

This helped understand the dataset structure before preprocessing.

## 4. Data Cleaning

The following preprocessing steps were performed:

* Converted `Release_Date` into datetime format.
* Extracted only the release year.
* Removed unnecessary columns:

  * Overview
  * Original_Language
  * Poster_Url
* Verified duplicate records.

## 5. Feature Engineering

Additional transformations were performed to improve analysis:

* Categorized `Vote_Average` into:

  * Not Popular
  * Below Average
  * Average
  * Popular
* Split multiple genres into individual rows using `explode()`.
* Converted Genre into a categorical feature.

## 6. Exploratory Data Analysis

The following analyses were performed:

* Genre Distribution
* Vote Average Category Distribution
* Release Year Distribution
* Most Popular Movie
* Least Popular Movie

---

# 📊 Visualizations

The project includes the following visualizations:

* Genre Distribution Count Plot
* Vote Average Distribution
* Release Year Histogram

These charts help understand movie trends and overall dataset characteristics.

---

# 📈 Key Insights

* Some genres appear significantly more frequently than others.
* Most movies belong to the average vote category.
* Movie releases are concentrated within specific time periods.
* Popularity varies greatly across different movies.
* Feature engineering makes categorical analysis easier and more meaningful.

---

# 📁 Project Structure

```text
Movie-Database-EDA-Python/
│
├── mymoviedb.csv
├── Netflix_Data_Analytics.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── genre_distribution.png
    ├── vote_distribution.png
    └── release_year_distribution.png
```

---

# ▶️ How to Run

1. Clone the repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

4. Run all cells sequentially.

---

# 📚 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Python Programming
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

# 🚀 Future Improvements

* Build an interactive dashboard using Streamlit.
* Add advanced visualizations.
* Perform correlation analysis.
* Create a recommendation model using movie metadata.
* Expand the project with additional datasets.

---

# 👨‍💻 Author

**Armaan Saad**
**B.Tech – Artificial Intelligence & Data Science**

This project was created to strengthen practical skills in Python, Data Analytics, and Exploratory Data Analysis while building a professional data science portfolio.
