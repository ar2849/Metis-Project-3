# Project-3

### Citibike Classification Project

Citibike is a bike share system in NYC that uses docking stations throughout the greater NYC area in all borough except Staten Island. The project is attempting to develop a model that will detect the correct number of customer in relation to the number of subscribers. Subscribers are members of the system that live area or within the system and make up the majority of trips within citibike's network. Customers use the system in a one-off or 3 day pass. They don't typically live in the area meaning they are visiting or testing the system out before becoming subscribers. This project tested four different models to each bring different results and insights into the data. 

- Logistic Regression
- Naive Bayes
- Random Forest
- XGBoost

All of the models predicted for the smaller class **customers** that number 1:3 in relation to **subscribers**. This allows our metrics to adequately reflect the imbalance in the data. After analyzing possible scores for evaluation: fbeta with _beta_ at 0.25 offered the best balance between recall and precision. The model's goal was the reduce the number of inaccurately classified subscribers as customers instead of customers labeled as subscribers. 

---

### Files

- Database-Build
    - Python Notebook: Walk through of the files uploaded from Citibike's database that were uploaded to a local SQL database. Use SQL to filter data into one dataset for cleaning and preprocessing. 
    
- Logistic Regression
    - Python Notebook: Logistic Regression scores 
    
- Naive Bayes
    - Python Notebook:
    
- Random Forest
    - Python Notebook:
    
- XGBoost
    - Python Notebook: