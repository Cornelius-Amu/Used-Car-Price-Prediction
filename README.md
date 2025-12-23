# Used-Car-Price-Prediction

![Image](https://github.com/user-attachments/assets/e11e3164-61ca-49a8-81f4-a75839ee05a9)


The dataset, sourced through web scraping from the well-known U.S. used car marketplace Truecars.com, comprises of six columns that can be feature engineered into several more . This dataset is particularly suitable for constructing regression models.

# Used Car Price Prediction Dataset

## Overview
This dataset is provided by an establishment that sells used cars. It includes various independent variables that influence vehicle pricing, such as production year, mileage, color, condition, and number of previous owners. The goal is to analyze these factors for insights into pricing trends and to make predictions about future vehicle prices.

## Dataset Features
The dataset includes the following columns:

- **Year of Production**
- **Mileage**
- **Exterior Color**
- **Interior Color**
- **Condition of the Vehicles**
- **Number of Owners**
- **Price**

## Questions & Answers

### 1. What is the average price of the vehicles in the dataset?
The dataset reveals that vehicles were sold at varying prices influenced by factors like geographical location and seasonal trends. Through visualizations, the average price was calculated for different vehicle models.

### 2. Which brand has the highest average price?
From the analysis, the Ram brand emerged with the highest average price, followed closely by Mazda and Audi.

### 3. How does the average price compare between vehicles with different conditions?
Consumer tendencies show a preference for reliable, low-maintenance vehicles. Our analysis confirms that vehicles with no reported accidents sold for higher prices compared to those with accidents. The recommendation is to focus on acquiring vehicles with no or minimal accident history for better market value.

### 4. Which vehicle models have the best resale value over time?
Models from the Ram brand have demonstrated higher resale values, indicating consistent consumer demand and brand reliability.

### 5. Is there a correlation between the number of owners and the vehicle price?
The correlation coefficient of **-0.2758** indicates a negative relationship, suggesting that as the number of previous owners increases, the vehicle price tends to decrease, albeit the correlation is not very strong.

### 6. Based on current trends, what predictions can be made for future pricing in the next couple of years?
**Regression Analysis Results**:
- **R-squared value**: 0.21 indicates that about 21% of the variability in vehicle prices can be explained by the vehicle's year.
- **P-value**: 8.81E-146 shows strong statistical significance, allowing us to reject the null hypothesis.
- **Intercept**: -3520060.25 signifies the baseline price position.
- **Slope**: 1756.36 indicates that each additional year increases the price by approximately $1,756.36.

**Predictions for 2025 and 2026**:
- For a vehicle aged 5 years (2025): Price predicted = -3511278.433
- For a vehicle aged 6 years (2026): Price predicted = -3509522.07

### Regression Statistics Summary Output
| Metric                  | Value               |
|-------------------------|---------------------|
| Multiple R              | 0.4585              |
| R Square                | 0.2102 (21%)        |
| Adjusted R Square       | 0.2099              |
| Standard Error          | 12112.84            |
| Observations            | 2840                |

### ANOVA
| df          | SS              | MS              | F                  | Significance F       |
|-------------|-----------------|-----------------|--------------------|----------------------|
| Regression   | 1               | 1.10842E+11     | 755.46             | 1.1611E-147          |
| Residual     | 2838            | 4.16394E+11     | 146720780.1        |                      |
| Total        | 2839            | 5.27236E+11     |                    |                      |

### Coefficients
| Coefficients | Standard Error      | t Stat          | P-value            | Lower 95%           | Upper 95%           |
|---------------|----------------------|------------------|---------------------|----------------------|---------------------|
| Intercept     | -3520060.25          | 129005.7446      | -27.29              | -3773014.743         | -3267105.756        |
| Year          | 1756.36              | 63.90102255      | 27.49               | 1631.07              | 1881.66             |

### Correlation Statistics
| Metric                | Value               |
|-----------------------|---------------------|
| Correlation Coefficient| -0.2758            |
| Interpretation        | Negative correlation: as the number of owners increases, the vehicle price tends to decrease. |

### Conclusion
The regression analysis demonstrates a significant relationship between the vehicle's age and its price, as evidenced by strong p-values. Although the model explains only a fraction of the price variance, it is still a meaningful predictor, and the pricing predictions for 5 and 6 years are reasonable based on current trends.

## Getting Started with the Dataset in Excel
1. **Download the Dataset**: [Link to dataset]
2. **Open in Excel**: Launch Microsoft Excel and load the dataset.
3. **Data Analysis**: Utilize Excel's built-in functions to explore trends, create charts, and conduct further statistical analysis.

## Contributing
Contributions to improve the dataset or analysis are welcome! Please share your insights or improvements as issues or pull requests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to modify any sections as needed, and replace placeholder information such as the dataset download link with actual URLs or file paths.
i am open to collaborate on data analyisi and visualization rlated lprojects. you an reach me
