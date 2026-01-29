
# Principal Component Analysis (PCA) on Financial Returns

## Project Description

This project applies Principal Component Analysis (PCA) to real financial data with the goal of reducing dimensionality, identifying latent market factors, and facilitating exploratory analysis of high-dimensional financial information.

The project is designed as a professional portfolio piece, showcasing key skills in data preprocessing, statistical analysis, dimensionality reduction, and results interpretation using real-world financial data.

---

## Objectives

- Transform historical prices into logarithmic returns.
- Prepare and standardize financial data for PCA.
- Reduce dimensionality while preserving most of the variance.
- Identify dominant factors driving market behavior.
- Communicate results clearly through visualizations.

---

## Dataset

The data consists of daily adjusted closing prices of stocks that are part of the S&P 500 index.

The dataset was obtained from Kaggle, a widely used platform in both industry and data science projects, ensuring open access, reproducibility, and a well-structured format.

From the adjusted prices, daily logarithmic returns were calculated. These returns represent continuous percentage changes and serve as the main input for the PCA model.

Data source: Kaggle – *S&P 500 Stock Data*

---

## Methodology

### 1. Data Preprocessing
- Calculation of logarithmic returns from prices.
- Removal of missing values.
- Feature standardization to avoid scale bias.

### 2. Principal Component Analysis (PCA)
- Initial model fitting to analyze explained variance.
- Selection of the optimal number of principal components.
- Projection of data into the PCA space.

### 3. Visualization & Interpretation
- Explained variance analysis (scree plot).
- Projection of observations onto the first principal components.
- Evaluation of component loadings to interpret latent factors.

---

## Key Results

- A small number of principal components explain a large proportion of the total variance.
- The first principal component (PC1) captures behavior consistent with overall market movement.
- Additional components reveal internal market structures and relative differences between stocks.
- PCA effectively reduces multicollinearity and noise in financial data.

---

## Conclusion

The analysis demonstrates that PCA is an effective technique for simplifying complex financial data and extracting latent factors that describe aggregated market behavior.  
The resulting components can be used as inputs for risk analysis, predictive modeling, or quantitative investment strategies.

---

## Limitations

- PCA is a linear method and does not capture non-linear relationships.
- Economic interpretation of components requires additional analysis.
- Results depend on the selected time period.
- Sensitivity to outliers.

---

## Future Work

- Relate principal components to economic sectors.
- Use PCA components as input features for machine learning models.
- Apply clustering techniques in the PCA space.
- Compare PCA with non-linear dimensionality reduction methods.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## Repository Structure

```
├── data/
│   └── sp500_prices.csv
├── notebooks/
│   └── pca_financial_returns.ipynb
├── README.md
```

---

## Author

**Immani Navor Trejo Rojas**  
Data Science | Analytics | IT Background  
Experience in data analysis, applied statistics, and Python-based modeling.

---

⭐ **Recruiter Note**  
This project demonstrates strong technical judgment, real-world data handling, correct PCA implementation, and the ability to interpret and communicate analytical results.
