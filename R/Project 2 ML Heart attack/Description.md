# Machine learning : Heart attack
This project investigates the potential of machine learning to predict heart attacks. The analysis leverages a dataset retrieved from Kaggle's  [Heart Attack Analysis & Prediction Dataset](https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset) collection.

The exploration employs R programming language and its rich ecosystem of libraries. Data cleaning and preparation are facilitated by `tidyverse`, while `ggplot2` visualizes the data to identify patterns and trends.  The core of the project involves model training using the `caret` package.

## Methodology:
- A variety of machine learning algorithms are explored, including Logistic Regression, Ridge and Lasso Regression, K-Nearest Neighbors (KNN), Decision Trees, and Random Forests.
- Hyperparameter tuning is implemented to optimize the performance of each model.
- Feature selection techniques are considered for potential improvements in future iterations.
  
## Findings:
- The analysis reveals that heart attack risk factors extend beyond traditional markers like cholesterol and blood pressure. Individuals with atypical angina and elevated heart rate (>150 bpm) may exhibit increased risk, even with normal readings in other areas.
- Among the implemented models, Ridge and Lasso Regression achieved the highest median accuracy (87.7%) and Kappa statistic (75.0%).
  
## Conclusion:
This project demonstrates the feasibility of utilizing machine learning for heart attack prediction. While the current models offer promising results, further exploration of feature selection techniques holds the potential to enhance accuracy and model interpretability.
