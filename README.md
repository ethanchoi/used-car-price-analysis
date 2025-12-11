# 🚗 What Drives Used Car Prices?
### A Data Science Project Using CRISP-DM & Machine Learning

This project explores which factors influence used car prices and uses machine learning models to identify what consumers value most in the used-car market.  
The analysis follows the CRISP-DM framework: business understanding, data exploration, data preparation, modeling, and evaluation.

## Project Overview
Used-car pricing depends on many factors—vehicle age, mileage, brand reputation, condition, drivetrain, and more.  
A used-car dealership wants to understand:

> “What factors make a car more or less expensive?”  
> “What do buyers care about most?”

This project analyzes a dataset of used car listings and builds predictive models to reveal the key drivers of price.

## Repository Contents
| File | Description |
|------|-------------|
| what_drives_price_car.ipynb | Main notebook with full analysis, preprocessing, modeling, and insights |
| vehicles.csv | Dataset used for analysis (if included) |
| README.md | Project documentation |

## CRISP-DM Steps

### 1. Business Understanding
Identify what consumers value in used cars so the dealership can make smarter purchasing and pricing decisions.

### 2. Data Understanding
Dataset features include:
- Year, odometer (mileage)  
- Manufacturer, condition, fuel type  
- Drive type, title status  
- Vehicle category (SUV, truck, sedan)  
- Price (target)

### 3. Data Preparation
- Removed invalid/missing values  
- Created vehicle_age  
- Log-transformed price and mileage  
- Encoded categorical variables  
- Scaled numeric features  
- Built sklearn preprocessing pipelines  

### 4. Modeling
Models trained:
- Linear Regression  
- Lasso Regression  

Metrics used: RMSE, R² Score

### 5. Evaluation & Insights
Key factors influencing price include:
- Vehicle age (newer → higher value)  
- Mileage (lower → higher value)  
- Brand reputation (Toyota, Honda, Subaru, Lexus, BMW)  
- Condition & title status  
- Vehicle type & drivetrain  
- Regional pricing differences  

## Recommendations for the Dealership
- Prioritize newer, low-mileage vehicles  
- Focus on high-value brands  
- Invest in minor reconditioning  
- Match inventory to regional needs  
- Consider buying & selling across state lines to maximize margin  

## Tools & Technologies
- Python, Jupyter Notebook  
- pandas, NumPy  
- seaborn, matplotlib  
- scikit-learn  

## How to Run

```
git clone <your-repo-url>
cd <your-repo-folder>
jupyter notebook what_drives_price_car.ipynb
```

Install dependencies:

```
pip install -r requirements.txt
```

## License
MIT License

## Contributions
Issues and pull requests are welcome.
