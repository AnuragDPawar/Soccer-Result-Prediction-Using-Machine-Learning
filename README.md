# Soccer Result Prediction Using Machine Learning

## Introduction

This project tackles the challenging task of predicting soccer match scores, considering the unique constraints posed by limited data availability in the sport. Unlike fields like stock market prediction, soccer prediction relies on a relatively small dataset due to the limited number of matches in a season. To overcome this, we leverage two datasets: comprehensive player attributes from FIFA and match records from major European football leagues. Our approach involves aggregating player data, constructing custom dataframes to capture team performance, and training random forest and regression models to predict home and away team scores. This project aims to provide a more accurate approach to football match score prediction, taking into account the specific challenges and data limitations in this domain.

## Methodology

- Utilized player attributes and match records datasets to enhance prediction accuracy.
- Aggregated player data to calculate average attacking, defending, and midfield strengths for each team.
- Developed custom dataframes for home and away teams to train random forest and regression models.
- Leveraged multivariate linear regression to estimate the relationship between match-specific factors and team scores.
- Utilized the random forest algorithm to predict home and away scores based on various features extracted from the match dataset.
- Conducted performance analysis of both models, achieving promising results.

## Performance Analysis

**Multivariate Linear Regression:**
- Mean Squared Error (MSE): Home Team (3.41), Away Team (0.48)
- Root Mean Squared Error (RMSE): Home Team (1.84), Away Team (0.69)
- Mean Absolute Error (MAE): Home Team (1.84), Away Team (0.69)
- R-squared (R²): 1 (Strong correlation)

**Random Forest:**
- Mean Squared Error (MSE): Home Team (2.8561), Away Team (3.0976)
- Root Mean Squared Error (RMSE): Home Team (1.69), Away Team (1.76)
- Mean Absolute Error (MAE): Home Team (1.69), Away Team (1.76)
- R-squared (R²): 1 (Strong correlation)

## Conclusion

This project offers a unique approach to soccer match score prediction by incorporating player attributes and match-specific information. By considering individual player abilities, team dynamics, and contextual factors, we achieve improved prediction accuracy despite limited data availability. The results have practical implications in sports analytics, such as sports betting strategies, team performance analysis, and fan engagement initiatives. This research contributes to the ongoing efforts to enhance prediction accuracy and gain fresh insights in football analytics.

For more details, refer to the full project report and references provided.

*Note: This README provides a brief overview of the project. Please refer to the full project report for in-depth information and analysis.*
