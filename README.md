# UC Berkeley – Professional Certificate in Machine Learning & Artificial Intelligence Practical Application 11.1 – What Determines the Price of a Car?

This repository contains the deliverables for the **Practical Application 11.1 – What Determines the Price of a Car**, part of the UC Berkeley Professional Certificate in Machine Learning & Artificial Intelligence.

---

## Project Overview

The goal of this analysis is to identify the key factors that influence the price of used cars.  
Using CRISP-DM as a guiding framework, the project includes data understanding, cleaning, preprocessing, visualization, modeling, evaluation, and final recommendations for a group of used-car dealerships interested in optimizing their inventory strategy.

## Executive Summary

This project applies supervised machine learning methodologies to investigate underlying causes of used car prices in order to facilitate data-driven pricing and inventory decisions at used-car dealerships. This exploratory data analysis shows strong and intuitive economic relationships. Visual examination indicates a significant negative correlation between vehicle price and odometer mileage, and a robust positive connection between vehicle year and price, mirroring typical depreciation trends in the auto market. More visualizations also show that when it comes to price formation, car condition is highly important, with “excellent” and “good” condition cars having higher prices, irrespective of manufacturers. Brand-level analysis also shows resale values by brand are high with Toyota, Honda, and Subaru. Cross-validation was used to evaluate multiple regression-based models. The top models that achieved the best compromise between prediction accuracy, stable performance, and interpretability were regularized linear models, particularly Ridge Regression. Consequently, the model is feasible for real-world deployments in business environments that require explainability and transparency.

## Repository Structure

- `notebooks/`
  - `used_car_price_analysis.ipynb` — Full Jupyter Notebook with CRISP-DM, EDA, modeling, and evaluation
- `README.md` — Project summary and business-oriented conclusions


## Key Findings Summary

- **Vehicle Year** and **Odometer** reading are the strongest predictors of price.
- Newer cars with lower mileage command a significantly higher value.
- Certain manufacturers (Toyota, Honda, Subaru) retain higher resale prices.
- **Condition** category strongly affects the price — “excellent/good” vehicles perform best.
- Among the tested models, Ridge Regression showed the best overall performance, providing slightly improved stability compared to standard linear regression.
- Cross-validation revealed that simple linear regression tends to overfit without regularization.

---

## Techniques Used

- **Python Libraries:** Pandas, NumPy, Seaborn, Matplotlib  
- **Models:** Linear Regression, Ridge Regression, Lasso Regression.  
- **Tools:** GridSearchCV, train/test split, cross-validation  
- **Evaluation Metrics:** RMSE, MAE, 

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
https://github.com/Felipe-Ulloa-CA/used-car-price-analysis-berkeley/blob/main/notebooks/used_car_price_analysis.ipynb


---

## Author

**Felipe Eduardo Ulloa Orellana**  
UC Berkeley Professional Certificate in Machine Learning & AI  
Silicon Valley, California

---

### 📄 License
This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
© 2025 **Felipe E. Ulloa**








