# Complete-EDA-Process
## Complete EDA - Exploratory Data Analysis

This is a Google Colab notebook by **Arvind Kumar** (MBA Business Analytics, Chandigarh University, Uttar Pradesh) that demonstrates a full EDA workflow on an **Employee Dataset** containing 49,653 records.

The notebook covers three levels of analysis:

**Univariate Analysis** — examining single variables at a time using histograms (e.g., age distribution) and countplots (e.g., gender breakdown via `sns.countplot`), plus pie charts for category proportions like STATUS_YEAR distribution.

**Bivariate Analysis** — exploring relationships between two variables across all three variable-type combinations: bar plots for Categorical vs Numerical (department vs. length of service), scatter plots for Numerical vs Numerical (age vs. length of service showing a clear positive trend), and grouped countplots for Categorical vs Categorical (active vs. terminated employees by year, 2006–2015).

**Multivariate Analysis** — using PCA (Principal Component Analysis) via scikit-learn on the Iris dataset to reduce dimensionality to 2 components, visualized as a scatter plot, and a **correlation heatmap** revealing notable findings: age and length of service are strongly positively correlated (0.91), while EmployeeID shows strong negative correlation with both age (−0.93) and length of service (−0.90).

The key libraries used are `pandas`, `numpy`, `matplotlib`, `seaborn`, and `sklearn`.
