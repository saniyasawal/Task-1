# Task-1
Task 1: Data Cleaning &amp; Preprocessing

The Titanic dataset was imported and explored to check data types and missing values.

Missing values in the Age column were filled with the median.

Missing values in Embarked were filled with the mode.

The Cabin column was dropped due to too many missing values.

The Sex column was converted into numeric form.

The Embarked column was one-hot encoded.

The numerical features Age and Fare were standardized using StandardScaler.

Outliers in Fare were detected using boxplots and removed with the three-standard-deviation rule.

The final dataset is cleaned, encoded, scaled, and ready for machine learning models.
