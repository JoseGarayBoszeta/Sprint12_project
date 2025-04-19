# Car Price Prediction for Rusty Bargain: Optimizing Performance and Efficiency

## Project Overview
This project develops a machine learning solution for Rusty Bargain, a used car sales service that wants to create a mobile app to quickly determine the market value of used cars. The goal is to build a prediction model that balances accuracy with computational efficiency.

## Key Objectives
- Analyze and prepare used car data containing technical specifications and prices
- Compare different machine learning models for price prediction
- Optimize hyperparameters to improve prediction accuracy
- Evaluate models based on prediction quality, training time, and prediction speed
- Select the most practical model for deployment in a mobile application

## Methods Used
- Data preprocessing and feature engineering
- Missing value imputation
- Categorical variable encoding
- Machine learning model training and comparison
- Hyperparameter tuning
- Cross-validation
- Performance evaluation using RMSE

## Models Implemented
- Linear Regression
- Decision Tree
- Random Forest
- LightGBM
- XGBoost
- CatBoost

## Results
After extensive experimentation and tuning, the LightGBM model provided the best balance of accuracy and efficiency:
- Tuned LightGBM achieved RMSE of 1671.09 with only 10.06 seconds training time
- While Random Forest had slightly better RMSE (1690.02), its training time was 651.13 seconds
- The optimized model demonstrated good generalization capabilities on the test set

## Appendices
- Appendix A: Native categorical feature handling in LightGBM
- Appendix B: Native categorical feature handling in CatBoost

## Technologies
- Python
- pandas
- scikit-learn
- LightGBM
- XGBoost
- CatBoost
- matplotlib
- seaborn

## Project Structure
1. Data preparation and EDA
2. Baseline model training
3. Hyperparameter tuning
4. Model comparison and selection
5. Final model evaluation
6. Appendices on advanced categorical encoding

This project demonstrates how to develop a practical machine learning solution that balances technical performance with real-world deployment constraints.
