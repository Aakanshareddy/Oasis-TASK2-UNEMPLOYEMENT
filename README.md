# Oasis-TASK2-UNEMPLOYEMENT

# Unemployment Analysis with Python

## Overview
This project analyzes unemployment data in India, focusing on unemployment rates, labor participation, and regional trends. The study uses Python for data cleaning, exploration, and visualization.

---

## Key Steps and Observations

### 1. **Data Overview**
- Dataset contains 768 rows and 7 columns.
- Columns: 
  - `Region`, `Date`, `Frequency`, `Estimated Unemployment Rate (%)`, `Estimated Employed`, `Estimated Labour Participation Rate (%)`, `Area`.
- Initial dataset had missing values in some rows.

### 2. **Data Cleaning**
- Missing values were removed (`df.dropna(inplace=True)`).
- Extra spaces in column names were stripped for consistency.

### 3. **Dataset Statistics**
- **Unemployment Rate (%)**:
  - Mean: 11.79%
  - Std Dev: 10.72%
  - Min: 0.00%
  - Max: 76.74%
- **Labour Participation Rate (%)**:
  - Mean: 42.63%
  - Std Dev: 8.11%
  - Min: 13.33%
  - Max: 72.57%

### 4. **Visualizations**
#### a) **Distribution of Unemployment Rate**
- Used a histogram (`sns.histplot`).
- Insights:
  - Rates are mostly concentrated below 20%, with a few outliers.

#### b) **Regional Distribution**
- Count plot of data entries per region.
- Revealed uneven data distribution across regions.

#### c) **Unemployment Rate Trends by State**
- Line plot showing variations over time (`sns.lineplot`).
- Highlights regional disparities in unemployment trends.

#### d) **Unemployment vs. Labor Participation**
- Scatter plot to explore relationships.
- Observed some correlation between labor participation and unemployment rates.

### 5. **Key Findings**
#### a) Average Unemployment Rate by Region
- **Highest**: Tripura (28.35%)
- **Lowest**: Meghalaya (4.80%)

#### b) Overall Trends
- Some regions exhibit consistently higher unemployment rates, highlighting potential structural challenges.

---

## Visualizations Summary
- **Histogram**: Shows unemployment rate distribution.
- **Bar Chart**: Average unemployment rates by region.
- **Line Plot**: Temporal unemployment trends across regions.
- **Scatter Plot**: Relation between unemployment and labor participation rates.

---

## Future Work
- Incorporate more recent data to analyze post-COVID trends.
- Perform predictive modeling using machine learning to forecast unemployment rates.
- Investigate external factors like industry and demographics to enhance insights.

---

## Tools Used
- **Python Libraries**: `numpy`, `pandas`, `seaborn`, `matplotlib`.
- **Visualization Techniques**: Histograms, bar charts, line plots, and scatter plots.

---

## Conclusion
This analysis highlights regional disparities in unemployment rates across India, uncovering critical insights into labor market dynamics. It sets a strong foundation for further exploration into socioeconomic factors influencing unemployment.
