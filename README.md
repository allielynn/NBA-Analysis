# NBA Analytics: Predicting Game Outcomes and Player Salaries

This repository contains two data-driven projects applying statistical and machine learning techniques to analyze and predict key aspects of NBA performance: game outcomes and player salaries. The first study employs machine learning models to predict NBA game results based on historical season data, while the second applies linear regression to understand the determinants of NBA player salaries.

## 1. Predicting NBA Game Outcomes
Using historical season data, this project aimed to predict NBA game results for the 2023-2024 season through feature engineering and machine learning models employed in Python.

### Approach:
- Processed data from 2,460 NBA games, incorporating features such as team performance metrics, game statistics, and match history.
- Applied extensive feature engineering, introducing advanced metrics like True Shooting Percentage, Effective Field Goal Percentage, ELO ratings, rolling averages, win streaks, and variance stability measures.
- Utilized exponential decay weighting to emphasize recent games over older performances.
- Employed Linear SVC for feature selection.
- Evaluated multiple machine learning models, including Gradient Boosting, Random Forest, LDA, and QDA.
- Gradient Boosting and Random Forest emerged as the top models, achieving a prediction accuracy of 93.87%.
### Findings:
- ELO ratings and opponent-dependent statistics were key features for game prediction, emphasizing the interactive nature of basketball matchups.
- Non-linear models (Gradient Boosting and Random Forest) outperformed linear classifiers, demonstrating the complex relationships in game outcomes.
- Game outcome prediction significantly benefits from engineered features rather than raw statistics alone.

## 2. Predicting NBA Salaries with Linear Regression
This project sought to analyze NBA player salaries and identify key predictors influencing salary variations using linear regression techniques in R.

### Approach:
- Conducted an in-depth analysis of NBA player salaries using statistical modeling.
- Verified the assumptions of linear regression, including constant variance, linearity, and normality, using diagnostic plots.
- Transformed the salary variable through an inverse response method to better satisfy model assumptions.
- Performed variable selection and model evaluation using AIC, AICc, and BIC, ensuring an optimal balance between model complexity and performance.
### Findings:
- Performance metrics such as points per game, age, and total rebounds were significant predictors of salary.
- Addressing outliers and ensuring model assumptions were met improved predictive performance.
- While linear regression provided meaningful salary insights, the relationship between performance and salary is influenced by factors beyond in-game statistics, such as contract negotiations and marketability.
