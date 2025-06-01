# Credit Risk Dashboard & Scoring System
# Project Goal
This project simulates a real-world credit risk assessment system. It uses Python and machine learning to score loan applicants based on default probability, stores cleaned and scored data in a PostgreSQL database, and presents key risk insights via an interactive Tableau dashboard. CI/CD is implemented using GitHub Actions to automate testing and ensure code quality.

# Tools
-Python: Data cleaning, risk modeling (pandas, scikit-learn)
-PostgreSQL: Structured data storage & queries
-Tableau: Visualization of risk categories, income segmentation, and default trends
-Git + GitHub: Version control
-GitHub Actions: Continuous integration (automated testing + linting)

# Key Features
-Developed a logistic regression model to classify loan applicants as low-risk or high-risk
-Cleaned and preprocessed real-world credit data from Kaggle (~150k rows)
-Wrote SQL scripts to design and populate normalized relational tables in PostgreSQL
-Built a Tableau dashboard to display KPIs like default rate by income group, age category, and risk score distribution
-Implemented a GitHub Actions workflow to automatically test and lint code on every push