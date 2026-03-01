## LAB 4 Answers:-
# 1.
- One missing value in the *email* column
- 127 duplicate records
- Raw unstructured text requiring preprocessing
- Limited numerical features

# 2.
To handle missing values, the row containing the missing email value was removed. Since only one row was affected, dropping it ensures data quality without significantly reducing dataset size. Imputing text data was avoided because it could introduce noise and reduce reliability.

# 3.
The IQR method was applied to the numerical column *label*. Since the column contains only binary values (0 and 1), all values fall within the calculated IQR bounds. THerefore, no outliers were detected, and no handling was required.

# 4.
Min-Max and Z-score normalization were applied to the *label* column. Since the column is binary, Min-Max normalization did not change the values. Z-score normalization standardized the values but did not provide meaningful information.

# 5.
PCA could not be applied directly because the dataset originally contained only one numerical feature. The explained variance ratio shouwed how much information each principal component captured, and cumulative variance indicated how many components were needed to retain most of the dataset's information.
