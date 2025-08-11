# CheonAn-Old-man-driver-license (Enhancing License Renewal Procedures for Elderly Drivers & Traffic Policy Suggestions)
Won the Grand Prize in the 2024 Cheonan City Data Analysis Contest.

## Overview :
This projret develops a prediction model fo accident severity involving elderly drivers. By analyzing accident data,
it forecasts yhe severity level, identifies high-risk road segments, and proposes policy recommendations for driver license
renewal procedures and traffic safety improvements.

## Key Features (Accident Severity Prediction Model)
- Data Preprocessing : One-hot encoding of categorical features.
- Modeling : XGBoost, LightGBM, and CatBoost withhyperparameter tuning via Optuna
- Ensemble Optimization : Minimizing MSE
- Prediction Refinement :  Value clipping to realistic ranges

## Implementation
- 'Buffer_add' : Creates 200m buffers around elderly driver activity points and records major facilities within each buffer (data preprocessing)
- 'Transfer_coordinatesESPG5181' : Converts geographic coodinates from ESPG:4236 to WSPG:5181 (data preprocessing)
- 'CheonanModel_final.ipynb' : Trains Gradient Boosting models on accident severity, optimizes ensemble weights, and generates final predictions

## HTML Result
- 'ChenanModel_final.html'

## More Details
https://www.notion.so/1bb79f19815e813eb18bf8ee1f143a0b?source=copy_link

> This repository is intended for portfolio viewing purposes. The raw data is not disclosed due to size and licensing constraints.
> Instead of full reproducibility, code outputs (COLAB/HTML/MP4) are provided.
