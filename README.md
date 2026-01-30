. Methodology
The project follows a structured data analytics workflow:

1. Data Acquisition: The dataset is downloaded from Kaggle using the Kaggle API.
2. Data Loading: The CSV file is loaded using Pandas.
3. Data Cleaning: Missing values are handled using replacement strategies. Duplicates are removed, and invalid ADR values are filtered out.
4. Feature Engineering: New features such as total nights and total guests are created.
5. Outlier Treatment: Extreme values are handled using quantile-based clipping.
6. EDA: Visualization libraries (Seaborn and Matplotlib) are used to explore patterns.
7. Probability Analysis: Cancellation probability and confidence intervals are calculated.
8. Hypothesis Testing: T-tests and Chi-square tests validate statistical significance.
9. PCA: Numerical features are standardized and reduced using PCA.
10. Data Export: The cleaned dataset is exported to Excel for Power BI.
