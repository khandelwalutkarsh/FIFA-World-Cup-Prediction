# FIFA World Cup 2026 Prediction Project

An end-to-end machine learning pipeline that uses historical match data (1930–2022) and current international ratings to forecast the 2026 tournament match outcomes.

## Summary of Model Performance
* **Best Performing Model:** Logistic Regression achieved the highest classification accuracy of **~58.7%** on the 2022 World Cup validation split.
* **Alternative Model Assessment:** The Random Forest Classifier heavily overfit the historical training sets, dropping down to **~41.3%** accuracy on the test set.
* **Data Pipeline Integrity:** Built a custom mapping dictionary (e.g., standardizing "USA" to "United States") to handle structural string mismatches, ensuring a 0% missing value rate post-merge.