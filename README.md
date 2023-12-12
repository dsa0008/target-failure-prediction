# target-failure-prediction
The dataset records various parameters associated with weather conditions and location, including temperature, wind direction, speed, and atmospheric pressure,
among others. The target variable is "Failure_today," indicating whether a machine failure occurred on a given day. The features encompass meteorological and
environmental factors, such as temperature, wind, and pressure, along with historical failure data ("Fail_tomorrow"). The challenge involves predicting machine
failures ("Failure_today") based on these parameters, providing valuable insights for preventive maintenance. The "RISK_MM" variable may serve as an additional
risk indicator. The dataset covers a range of dates, allowing for a time-series analysis to identify patterns and trends influencing machine failures over time.

# Metric 1: Classification Accuracy
KNN = 0.8283
Random Forest = 0.8521
Decision Tree = 0.8315
Logistic Regression = 0.8292

# Metric 2: Precision
KNN = 0.6461
Random Forest = 0.7285
Decision Tree = 0.6701
Logistic Regression = 0.6683

# Metric 3: Recall
Random Forest = 0.5265
Decision Tree = 0.4671
KNN = 0.4924
Logistic Regression = 0.4502

# Metric 4: F1 Score
Random Forest = 0.6112
Decision Tree = 0.5505
KNN = 0.5589
Logistic Regression = 0.5380

# Growth/Next Steps
While predictive accuracy was relatively high - other modelling approaches could be tested, especially those somewhat similar to Random Forest, for example
XGBoost, LightGBM to see if even more accuracy could be gained.
From a data point of view, further variables could be collected, and further feature engineering could be undertaken to ensure that we have as much useful
information available for predicting whether the machine fails today.
