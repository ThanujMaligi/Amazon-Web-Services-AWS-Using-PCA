## 🌟 Overview of the Project

This project demonstrates how to **import, process, and analyze data** using MATLAB, focusing on **Principal Component Analysis (PCA)** for dimensionality reduction.

The data is imported from an **Excel spreadsheet** (`Book2`), with the import options specifying the sheet name, data range, column names, and variable types. Numerical variables such as sales, quantity, discount, and profit are normalized to a range of `0 to 1` for uniformity. Categorical variables like order ID and country are converted to `categorical data types` for easier handling.

After importing and preparing the data, the script computes the **covariance matrix** of the numerical variables. PCA is performed by calculating **eigenvalues** and **eigenvectors** from the covariance matrix. The eigenvalues are sorted in descending order to determine the **principal components**, and the top two eigenvectors are selected for dimensionality reduction. The centered data (mean-subtracted) is then projected onto these principal components.

For visualization, a **scatter plot** is generated to display the data along the first two principal components. Additionally, a **loading plot** highlights how the original variables (sales, quantity, discount, profit) contribute to the principal components, enabling easier interpretation of the results.

---

🎯 This project offers a comprehensive demonstration of **data preprocessing** and **dimensionality reduction**, making it a valuable tool for analyzing real-world datasets.
