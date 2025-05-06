# Assi-1-ML-Statistical-Measures


This project analyzes property prices using `house_price.csv`. The focus is on exploring and transforming the `price per square feet` feature using various statistical methods.

---

##  Dataset

- **File**: `house_price.csv`

---

## 📌 Objectives

### Q1. Basic EDA
- Load and inspect data
- Handle missing values
- Create `price_per_sqft = (price * 100000) / total_sqft`
- Explore basic statistics and distribution

### Q2. Outlier Detection & Removal
Outliers in `price_per_sqft` are identified and treated using:
- a) Mean & Standard Deviation
- b) Percentile Method (5th–95th)
- c) IQR (Interquartile Range)
- d) Z-Score Method  
**Techniques used**: Trimming / Capping / Imputation with mean or median

### Q3. Box Plot Comparison
- Box plots created for each method
- Visually compare effectiveness in removing outliers

### Q4. Normality Check
- Use `histplot` to visualize distribution
- Calculate **skewness** and **kurtosis**
- Apply **log transformation** if needed
- Compare before and after transformation

### Q5. Correlation Heatmap
- Compute correlation between numerical columns
- Visualize using heatmap

### Q6. Scatter Plots
- Visualize relationships using scatter plots between:
  - `price`, `total_sqft`, and `price_per_sqft`

---

