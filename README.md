# Netflix Content Strategy Analysis

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

> **A strategic deep-dive into Netflix's global content catalog, transforming raw data into actionable business intelligence.**

---

## Executive Summary

Understanding content trends is crucial for streaming platforms. This project utilizes **Exploratory Data Analysis (EDA)** to uncover the strategic direction of Netflix over the last decade. 

By cleaning and analyzing a dataset of **8,800+ movies and TV shows**, this analysis provides insights into:
* **Content Strategy:** The shift between Movies vs. TV Series production.
* **Global Expansion:** Identifying top producing countries and emerging markets.
* **Release Patterns:** Analyzing the acceleration of content addition over time.

---

## Key Insights & Visuals

### 1. Content Mix Strategy (Movies vs. TV Shows)
*Analysis of the distribution showing the dominance of Feature Films in the catalog.*

![Content Mix](content_mix.png)

### 2. Global Market Dominance
*Breakdown of the top 10 countries contributing to Netflix's library.*

![Top Countries](top_countries.png)

---

## The Workflow

This project follows a rigorous Data Science pipeline:

1.  **Data Ingestion:** Loading the raw dataset.
2.  **Data Cleaning (Crucial Step):**
    * Handling missing values in critical columns (Director, Cast, Country).
    * Standardizing date formats for Time-Series analysis.
    * Removing duplicates to ensure 100% data integrity.
3.  **Exploratory Analysis:** Using **Pandas** for statistical summaries.
4.  **Visualization:** Leveraging **Seaborn** & **Matplotlib** to create intuitive charts.

---

## Tech Stack

* **Language:** Python 3.x
* **Analysis:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

## How to Run

To run this project locally, follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/arshiaestineh2005-tech/Netflix-Content-Strategy-Analysis.git](https://github.com/arshiaestineh2005-tech/Netflix-Content-Strategy-Analysis.git)
    ```

2.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch the Notebook**
    ```bash
    jupyter notebook netflix_shows.ipynb
    ```

---

## File Structure

* **netflix_shows.ipynb:** Main analysis notebook (Code + Visuals)
* **netflix_titles.csv:** Raw dataset source
* **requirements.txt:** Project dependencies
* **content_mix.png:** Visualization export
* **top_countries.png:** Visualization export
* **README.md:** Project documentation

---

**Arshia Estineh**
*Machine Learning Engineer | Data Analyst*