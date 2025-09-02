# data-cleaning-and-clustering
Data cleaning, feature engineering, and unsupervised clustering of subscriber app usage to extract actionable user segments.
Dataset
CSV with subscriber_id, app_name, app_category, volume, duration, event_date.

Steps:

Data cleaning: duplicates, missing values, category mapping, low-frequency app grouping, export of cleaned CSV.

Feature engineering: averages, ratios, log transforms, pivot by category.

Clustering: StandardScaler + OneHotEncoder, KMeans, silhouette evaluation, interpretation of clusters.

Results:

Cleaned dataset: data_cleaned_final.csv

Defined segments (clusters):youth,middle and old users

Prediction function for new app usage input.

Tools
Python, pandas, numpy,matplotlib and scikit-learn.
