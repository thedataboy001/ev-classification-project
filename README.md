## Problem

How can vehicle and geographic characteristics be used to classify electric vehicles into Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs), and what do adoption trends over time reveal about the transition from hybrid to fully electric technology in Washington State? 

### Objectives

1. Develop a model to predict wheather a vehicle is a BEV or PHEV based on their features
2. Identify key predictors that distinguish BEV from PHEV
3. Analyze temporal trends in BEV vs PHEV adoption to understand technology shifts
4. Examine geographic patterns of BEV vs PHEV dominance (urban vs rural, county-level distribution).
5. Forecast future market composition of BEVs vs PHEVs using time-series and diffusion models.

### Methodology

#### Data Collection

EV Population dataset (Washington State) 

https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data

#### Data Preparation

Define the target variable: EV Type (BEV vs PHEV)
Encoding categorical variables
split dataset into train/test sets

#### Classification Analysis

Apply Random Forest and KNN classification model
Evaluate performance (accuracy, precision, recall, F1-score)
Use feature importance to interpret key drivers of BEV vs PHEV classification

