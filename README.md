# Life-Expectancy-Prediction-Using-Regression-Models
This repository contains files for the analysis and predictive modeling of Life Expectancy in Africa, using multiple regression techniques. The dataset includes various factors such as GDP per-capita, health expenditure, military expenditure, forest cover, CO2 emmissions, access to drinking water services, people practicing open defecation, adult obesity, access to internet, and more.

## Models Used:
* Linear Regression
* K-Nearest Neighbors (KNN)
* Random Forest (RF)
* XGBoost

After tuning and evaluating the models, KNN achieved the best performance with an RMSE of 0.638. Predictions made by the KNN model would be expected to be within (plus or minus) 0.64 years of true Life Expectancy.

## Key Processes:
* Data Preprocessing: Cleaning and normalizing data for improved model accuracy.
* EDA: Summarizing the data to obtain measures of centrality, and visualizing the data to understand existing patterns.
* Model Training: Training and testing various regression models, and benchmarking the model training processes.
* Model Evaluation: Comparing model performance using RMSE and R-squared.
* Feature Importance: Analyzing which factors most influence life expectancy.

## Tools and Libraries
RStudio (tidyverse, janitor, caret, kknn, mlr, parallel, parallelMap)

## Contributions
Contributions to improve the model performance and reliability are welcome. Please fork the repository, make your changes, and submit a pull request. For significant changes, please open an issue first to discuss your proposed modifications.
