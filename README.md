Movie Dataset Analysis

---Overview

This project analyzes a movie dataset containing thousands of films (e.g., 7668 movies) to uncover trends in genres, financial performance, and movie quality. Using Python with pandas, matplotlib, and seaborn, the project demonstrates data cleaning, exploration, and visualization skills at a moderate level, suitable for learning, coursework, or a data science portfolio.

---Objectives

-Clean and preprocess the dataset to handle missing values.

-Explore genre distributions, financial metrics (budget, gross), and movie scores.

-Visualize trends and relationships to derive actionable insights.

---Key Features

--Data Cleaning: Imputed missing values (e.g., 2171 budgets, 189 gross) using medians for numerical columns and modes for categorical columns.

--Exploratory Analysis:

-Summary statistics for ratings (e.g., 3697 R, 2112 PG-13), genres (2245 Comedy, 1705 Action), and countries (5475 United States).

-Visualizations: Genre distribution bar plot, budget vs. gross scatter plot, score histogram.

-Correlation Analysis: Heatmap of numerical features (budget, gross, score, votes, runtime, year) to identify relationships.

-Genre Analysis: Identified high-score movies (score ≥ 8.0) and analyzed average gross by genre.

--Key Findings:

-Most common genre: Comedy.

-Highest grossing movie: Varies by dataset (e.g., a top film earned hundreds of millions).

-Average score: ~6.5 (based on typical distributions).

-Animation and Action genres often have higher gross earnings.
