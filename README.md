# Health Analysis Project

This project analyzes the prevalence and incidence of diabetes in the United States using data maintained by the Centers for Disease Control and Prevention (CDC). The dataset covers records from 2000 to the present and includes various health indicators related to obesity, inactivity, and diabetes at the county level.

## Dataset Overview

The dataset contains the following columns:
- **Year:** The year of record
- **FIPS Code:** The unique identifier for each county
- **County:** The name of the county
- **State:** The name of the state
- **% Obese:** The percentage of the population classified as obese in each county
- **% Inactive:** The percentage of the population classified as inactive in each county
- **% Diabetic:** The percentage of the population diagnosed with diabetes in each county

## Key Findings

1. **Diabetes and Its Correlates:**
   - **Diabetes** is more prevalent in populations with higher rates of **obesity** and **inactivity**.
   - **Alabama** has the highest percentage of diabetic problems, with a prevalence rate of **9.4%**.
   - **Wyoming** is identified as the state with the healthiest population, achieving a health score of **69.3**.

2. **Variability in Diabetic Rates:**
   - **Arkansas**, **Louisiana**, and **North Carolina** show higher variability in diabetic rates, as indicated by their higher standard deviations.

3. **State-Level Trends:**
   - **Wyoming** had the lowest obesity rate, while **Washington** had the highest.
   - Surprisingly, **New York** had the highest rate of inactivity, while **Washington** had the lowest.
   - **Alabama** was identified as the state with the greatest diabetes prevalence, while **Wyoming** had the lowest.

4. **Correlation Analysis:**
   - The correlation between **% Obese** and **% Diabetic** is positive, indicating that states with higher obesity rates tend to have higher diabetic rates.
   - The correlation between **% Inactive** and **% Diabetic** is weaker, suggesting that inactivity alone might not be a strong predictor of diabetes.

## Conclusion

Based on the data from the CDC, our analysis confirms that diabetes is closely linked to obesity and inactivity. By analyzing and predicting diabetes prevalence across various counties, we found that our predictions were very close to the actual values, highlighting the strong relationship between these health indicators.

## Repository Contents

The following files are included in this repository:
1. **Obesity and Diabetes Patterns.ipynb**  
   This Jupyter Notebook contains the code used to analyze the dataset and identify patterns related to obesity, inactivity, and diabetes.
   
2. **Health Analysis.pdf**  
   This PDF document presents a comprehensive analysis of the health indicators and their impact on diabetes prevalence.


## Final Remarks

This project sheds light on the critical public health issue of diabetes in the United States and emphasizes the importance of addressing obesity and inactivity as key factors in reducing the prevalence of this disease.
