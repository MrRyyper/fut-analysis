# Data Exploration Portfolio (Ongoing Project)

## Project Overview
This portfolio consists of various analyses focused on soccer players and team performance using machine learning techniques. Each analysis explores specific aspects such as player stats, team performance, and predictive modeling. The project is a work in progress, and additional features and analyses may be included over time.

---

## File Structure
### Jupyter Notebooks
These notebooks contain the primary analyses:
- WB_0b_4.ipynb
- WB_1.ipynb
- WB_2.ipynb
- WB_3.ipynb
- WB_4.ipynb
- WB_5.ipynb
- WB_6.ipynb
- WB_7.ipynb
- WB_8.ipynb

### Data Files
#### CSV Files
These files provide the datasets used for various analyses:
- **combined_data.csv**: Contains comprehensive information on all players from the Premier League up until 2022, including metrics for performance, goals, and actions.
- **defenders_data.csv**: Focuses on detailed metrics for defenders, such as tackles, interceptions, and blocks.
- **forwards_data.csv**: Provides statistics for forwards, including goals scored, assists, and offensive actions.
- **midfielders_data.csv**: Covers metrics for midfield players, such as passing accuracy, key passes, and defensive contributions.

### Python Scripts
- **ID3.py**: This file, created by Khune Li, implements the ID3 decision tree algorithm and was used in one of the analyses. Its specific usage will be detailed in the relevant section.

---

## Analyses Overview
Each notebook explores specific themes using different machine learning techniques. Here’s an overview of the objectives:

- **`WB_0b_4.ipynb`**:
  Focuses on analyzing player contributions in terms of offensive actions and goals scored. Machine learning techniques include feature selection and binary classification (e.g., logistic regression).

- **`WB_1.ipynb`**:
  Explores predictive modeling for team-level performance metrics using linear regression. Significant focus on feature engineering from team and player data.

- **`WB_2.ipynb`**:
  Implements clustering techniques (e.g., K-means) to group players based on similar performance metrics. Helps identify patterns among player roles.

- **`WB_3.ipynb`**:
  Investigates defensive performance metrics using decision trees and random forests. Evaluates model performance through metrics like accuracy and confusion matrices.

- **`WB_4.ipynb`**:
  Focuses on predicting player performance using logistic regression and Poisson regression. Includes extensive statistical modeling and prediction intervals.

- **`WB_5.ipynb`**:
  Uses a decision tree classifier (`ID3.py` module) to analyze Manchester City matches and predict outcomes based on match data. Includes feature engineering and visualization of decision trees.

- **`WB_6.ipynb`**:
  Implements a Random Forest model to evaluate player performance and predict metrics like passing accuracy. Explores feature importance and model evaluation using Mean Squared Error (MSE).

- **`WB_7.ipynb`**:
  Performs time-series analysis using ARIMA to forecast trends like recoveries or team performance. Includes autocorrelation and partial autocorrelation analyses.

- **`WB_8.ipynb`**:
  Extends time-series forecasting with SARIMA models, focusing on recoveries and other team metrics. Evaluates forecast accuracy with confidence intervals.

---

## Future Work
- Incorporate more advanced predictive models.
- Improve feature tuning.
- Expand analyses to include more teams and broader datasets.
- Enhance visualizations and interpretability.

---

## License and Acknowledgements
- The `ID3.py` file was created by Khune Li and incorporated into one analysis.
- All datasets are sourced or generated for educational purposes.

---
