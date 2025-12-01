# E-commerce-Furniture-Analysis
## Introduction
This project explores the E-commerce Furniture Dataset 2024, performs data cleaning, exploratory analysis, feature engineering, and machine learning modeling to predict product sales (sold).
The goal is to identify meaningful patterns in pricing, discounts, product descriptions, and shipping tags, and then evaluate regression models to forecast demand.
# Project Objectives

- Clean and preprocess raw e-commerce data
- Explore patterns using visual analysis
- Engineer meaningful predictive features
- Apply and compare regression models
- Identify improvements for future enhancement

| Category                | Tools                                                      |
| ----------------------- | ---------------------------------------------------------- |
| Programming Language    | Python                                              |
| Data Processing         | Pandas, NumPy                                              |
| Visualization           | Matplotlib                                                 |
| Feature Engineering     | Scikit-learn preprocessing                                 |
| Machine Learning Models | RandomForestRegressor, Linear Regression, Ridge Regression |
| Evaluation Metrics      | RMSE, R² Score                                             |
| Environment             | Jupyter Notebook                                           |

# Insights & Interpretation

- High price does not strongly correlate to higher/lower sales — market demand is diverse.
- Discounts show slight positive effect but not dominant.
- Product naming length has minimal but noticeable influence.
- Shipping tags (e.g., free shipping) show impact though category distribution is skewed.

# Conclusion

This project successfully demonstrates a complete ML workflow — from raw scraped data to modeling and evaluation. While baseline models show modest predictive power, the findings highlight clear paths for improvement, especially in text-based feature enrichment and advanced modeling.

The Random Forest (after log transformation) remains the best-performing baseline, proving the value of non-linear modeling in noisy real-world e-commerce datasets.
