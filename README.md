# Premier League Match Outcome & Standings Prediction

### CMSE 492: Applied Machine Learning Final Project
### Michigan State University

## Project Overview 
This project applies machine learning techniques to predict outcomes for the 2024–2025 Premier League season using historical match data obtained from Kaggle. As part of Michigan State University's CMSE 492: Applied Machine Learning course, the project involves data preprocessing, feature engineering, and the development of multiple predictive models. Models are evaluated and compared using performance metrics including MAE, MSE, RMSE, and R². The objective is to identify the best-performing model and use it to predict match outcomes and generate projected final league standings for the 2024–2025 Premier League season 

## Project Objectives 
- Understanding different trends in Premier League data to identify key factors that have influence on match outcomes.
- Utilizing feature engineering to improve model prediction accuracy.
- Train and test for multiple models in order to predict match outcomes, optimizing for low errors and high variability (r^2).
- Evaluate each model to assess performance and make imporvemets as needed. 
- Use the best performing model to predict a finalized league standing for the 2024-2025 season.
- Provide visualizations to represent model predictions and performance.

## Project Structure
```plaintext
├── data/                     
│   └── Premier_League.csv
├──docs/
    └── Premier_League_Machine_Learning_Predictions.pdf
├── notebooks/                
├── src/                      
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── train_model.py
│   └── evaluate_model.py
├── README.md               
└── requirements.txt 
```

## Setup 
- Clone Repository using git clone https://github.com/morgan-fox/cmse492_project.git and cd cmse492_project
- Install nececssary dependencies using pip install -r requirements.txt
- Download the Premier_League.csv dataset located in the data folder

## Requirements 
Required Libraries:
- Numpy
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib


## Updated Results 

[View Full Project Presentation](docs/Premier_League_Machine_Learning_Predictions.pdf)

Best performing model:
- XGBoost

Predicted League Standings
![image](https://github.com/user-attachments/assets/105db2a6-659a-4f59-a80e-1aa4e59d607f)
