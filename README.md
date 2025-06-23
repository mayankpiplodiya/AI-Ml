Data Preprocessing Summary
Imported the dataset using pandas and explored basic structure using df.info() to check data types.
Handled missing values:
Numerical columns → filled using mean or median.
Categorical columns → filled using mode.
Encoded categorical features using Label Encoding or One-Hot Encoding, then confirmed all features are numerical.
Normalized numerical features using MinMaxScaler to scale values between 0 and 1.
Detected outliers using boxplots for visualization.
Removed outliers using:
Z-Score Method: Removed rows with Z-score > 3.
Quantile Method: Dropped values above the 95th percentile.
IQR Method: Kept values within Q1 − 1.5×IQR to Q3 + 1.5×IQR.
Final dataset is clean, scaled, outlier-free, and ready for machine learning
