
---

## Exercises

### Section 1: Handling Missing Data
- Identified missing values using `pandas`.
- Handled missing data by **dropping** or **imputing** values using `SimpleImputer`.
- Compared strategies: `mean`, `median`, `most_frequent`.

### Section 2: Handling Categorical Data
- Mapped **ordinal features** using manual mapping.
- Encoded class labels with `LabelEncoder`.
- Applied **one-hot encoding** for nominal features.
- Discussed multicollinearity and why dropping one column helps.

### Section 3: Partitioning a Dataset
- Split dataset into **training** and **testing** sets with `train_test_split`.
- Used `stratify` to preserve class proportions.
- Observed effect of changing `test_size`.

### Section 4: Feature Scaling
- Applied **Min-Max normalization**.
- Applied **Standardization (Z-score scaling)**.
- Compared feature distributions before and after scaling.
- Discussed the impact on algorithms like KNN and SVM.

### Section 5: Selecting Meaningful Features
- Used **L1 Regularization** in Logistic Regression to induce sparsity.
- Implemented **Sequential Backward Selection (SBS)** for feature subset selection.
- Computed **feature importance** using Random Forests.
- Compared top features from different selection methods.
- Observed how selecting important features impacts model accuracy.

---

## Key Learnings
- Preprocessing improves **model performance** and **stability**.
- Handling missing data ensures **complete datasets** for training.
- Encoding categorical data correctly prevents **misinterpretation by models**.
- Scaling features is essential for **distance-based and gradient-based algorithms**.
- Feature selection methods (L1, SBS, Random Forests) reduce overfitting and highlight **important features**.

