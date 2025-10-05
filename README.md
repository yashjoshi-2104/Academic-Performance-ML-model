# Academic-Performance-ML-model
This project predicts students’ writing scores using various academic and demographic factors with a Linear Regression model. It demonstrates a simple regression pipeline: data preprocessing, feature encoding, model training, evaluation, and result visualization.

1. Preprocessing

      Loaded dataset with Pandas.
      
      Handled categorical variables using pd.get_dummies(..., drop_first=True).
      
      Defined X (independent variables) and y (dependent variable = writing score).
      
      Split into training/testing sets (70/30 split).

2. Model

      Algorithm: Linear Regression
      
      Training: Fit model on training data.
      
      Prediction: Evaluate performance on test set.

3. Results
      Metric	Score
      Mean Absolute Error	3.07
      Mean Squared Error	13.84
      R² Score	0.95

The model explains 95% of the variance in writing scores, showing strong correlation between reading and writing performance.

4. Visualizations

      Correlation heatmap between scores.
      
      Scatter plots: reading vs writing score.
      
      Residual plots to analyze model errors.

