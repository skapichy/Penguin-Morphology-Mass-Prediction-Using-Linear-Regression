# Penguin-Morphology-Mass-Prediction-Using-Linear-Regression
This project uses the penguins dataset to predict body mass from bill depth using linear regression. It includes data cleaning, EDA, model building with statsmodels, and diagnostic checks like Q-Q plots and residual analysis. Insights support ecological research and highlight key morphological relationships.
The goal is to demonstrate how statistical modeling can be used to understand biological traits and support ecological research, while also showcasing best practices in regression diagnostics.

# Project Summary
- Dataset: Seaborn’s penguins dataset (Adelie and Gentoo species only; Chinstrap excluded)
- Target Variable: body_mass_g
- Predictor Variable: bill_depth_mm
- Model Used: Simple Linear Regression (OLS via statsmodels)
- Diagnostics:
- Q-Q plot for normality of residuals
- Histogram of residuals
- Residuals vs. fitted values plot for homoscedasticity

# Tools and Technologies
 - Python - Programming Language
 - pandas, NumPy - Data Manipulation
 - seaborn, matplotlib - Data Visualization
 - statsmodels (OLS regression, diagnostics)- Statistical Modeling
 - Jupyter Notebook - Project Environment

# Project Objectives
- Clean and preprocess the penguins dataset
- Visualize relationships between morphological features
- Build a regression model to predict body mass
- Validate model assumptions (normality, linearity, homoscedasticity)
- Interpret model coefficients and statistical significance
- Provide actionable insights for ecological and biological studies

# Business & Scientific Insights
- Bill depth is negatively correlated with body mass, suggesting that deeper bills may be associated with lighter penguins in this sample.
- The model explains 23.4% of the variance in body mass (R² = 0.234), indicating moderate predictive power.
- Residuals are approximately normally distributed, but heteroscedasticity is present, which may affect reliability of standard errors.
- The p-value for bill depth is highly significant, confirming its relevance as a predictor.

# Recommendations
- Model Enhancement: Incorporate additional predictors like flipper length and bill length to improve model accuracy.
- Multivariate Regression: Transition to multiple linear regression to capture more complex relationships.
- Ecological Application: Use findings to support field studies on penguin health, feeding behavior, and habitat adaptation.
- Statistical Rigor: Apply robust standard errors or transformation techniques to address heteroscedasticity.
