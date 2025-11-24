# LendingClub-DefaultPrediction
Predicting loan outcomes using logistic regression, random forest, and XGBoost models 
This project builds an **ensemble machine learning model** to predict loan outcomes using data from LendingClub.  
It combines logistic regression, random forest, and XGBoost models to identify key drivers of loan performance and improve predictive accuracy.

## Project Overview
The goal of this project was to explore how different modeling techniques can be combined to better predict whether a loan will default or be fully paid.

Key steps included:
- Data exploration and cleaning  
- Detecting and addressing **data leakage**  
- Engineering features for categorical and numeric data  
- Training multiple models (Logistic Regression, Random Forest, XGBoost)  
- Automating hyperparameter tuning  
- Combining models into a simple **ensemble**  
- Visualizing model performance and feature importance  

## Results & Insights
- The ensemble model outperformed individual models on accuracy and recall.  
- Feature importance revealed strong relationships between credit history, interest rate, and loan grade.  
- The workflow highlights end-to-end **modeling discipline**: from data handling to evaluation and visualization.

## Tools & Libraries
- Python  
- pandas, numpy  
- scikit-learn, XGBoost  
- matplotlib, seaborn  

## Skills Demonstrated
- Ensemble modeling  
- Feature engineering  
- Data leakage detection  
- Model tuning and evaluation  
- Data visualization and storytelling  

## Repository Structure
- `Lending Club Default Prediction.ipynb` – main analysis notebook  
- `lending_club_data` – dataset files    
- `README.md` – project overview and documentation 
