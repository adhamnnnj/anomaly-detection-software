# anomaly-detection-software
This Python program performs data preprocessing, statistical analysis, visualization, anomaly detection, and model training on a labeled dataset (normal vs anomaly). It uses techniques like Z-score filtering, Probability Density Function (PDF) fitting, and Naive Bayes classification.

# -Key Features
Data Cleaning:
Detects and reports missing and infinite values.
Handles categorical and numerical data properly.

# -Statistical Analysis:
Calculates mean, variance, and quartile-based summaries.
Computes and plots PMF, PDF, and CDF for key features.

# -Visualizations:
Scatter plots, 2D histograms, correlation matrices.
PDF fitting to determine the best statistical distribution for each feature using MSE.
Anomaly Detection:
Uses Z-score based filtering to detect outliers.
Annotates rows as anomaly or normal.

# -Classification:
Trains and evaluates multiple Naive Bayes models: Gaussian, Multinomial, and Bernoulli.
Uses accuracy, precision, recall, and confusion matrix for evaluation.
Custom Naive Bayes Probability Estimation:
Implements a manual Naive Bayes classifier that combines Gaussian likelihood for numeric features and PMF for categorical ones.

# - Why Recall Matters
In anomaly detection, recall is more critical than accuracy. Catching rare but impactful events (like fraud or attacks) is the priority, even if it leads to more false positives.
