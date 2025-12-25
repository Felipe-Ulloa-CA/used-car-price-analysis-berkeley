# Used Car Price Analysis – UC Berkeley ML & AI (Practical Application 11.1)

This repository contains the deliverables for the **Practical Application 11.1 – What Determines the Price of a Car**, part of the UC Berkeley Professional Certificate in Machine Learning & Artificial Intelligence.

---

## Project Overview

The goal of this analysis is to identify the key factors that influence the price of used cars.  
Using CRISP-DM as a guiding framework, the project includes data understanding, cleaning, preprocessing, visualization, modeling, evaluation, and final recommendations for a group of used-car dealerships interested in optimizing their inventory strategy.

## Repository Structure

```
used-car-price-analysis-berkeley/
│
├── notebooks/
│   └── used_car_price_analysis.ipynb     # Full Jupyter Notebook with CRISP-DM, EDA, modeling, evaluation
│
└── README.md                             # Summary of findings for non-technical audience
```

## Key Findings Summary

- **Vehicle Year** and **Odometer** reading are the strongest predictors of price.
- Newer cars with lower mileage command a significantly higher value.
- Certain manufacturers (Toyota, Honda, Subaru) retain higher resale prices.
- **Condition** category strongly affects the price — “excellent/good” vehicles perform best.
- Among the tested models, **Random Forest** and **Ridge Regression** showed the best performance.
- Cross-validation revealed that simple linear regression tends to overfit without regularization.

---

## Techniques Used

- **Python Libraries:** Pandas, NumPy, Seaborn, Matplotlib  
- **Models:** Linear Regression, Multiple Regression, Ridge, Lasso, Random Forest  
- **Tools:** GridSearchCV, train/test split, cross-validation  
- **Evaluation Metrics:** RMSE, MAE, R²  

---

## Business Recommendations

- Prioritize purchasing **newer cars with lower mileage** for best resale value.
- Focus on **high-resale manufacturers** (Toyota, Subaru, Honda).
- Avoid inventory with **poor condition**, as value recovery is low.
- Use predictive models to optimize buying decisions and pricing strategies.
- Continue collecting data to refine pricing and demand forecasting.

---

## Notebook Link

View the full analysis here:  
`/notebooks/used_car_price_analysis.ipynb`

---

## Author

**Felipe Eduardo Ulloa Orellana**  
UC Berkeley Professional Certificate in Machine Learning & AI  
Silicon Valley, California









