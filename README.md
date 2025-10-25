# Gradious-Final-Machine-Learning-Project

# Automobile Performance ML Project
📌 Project Overview:
This project demonstrates a complete end‑to‑end Machine Learning workflow using an automobile performance dataset.
The primary objective is to predict fuel efficiency of vehicles based on their engine, design, and manufacturing attributes.
The project is structured to reflect the core ML pipeline:
- Data Preprocessing – cleaning and preparing raw data
- Feature Engineering – encoding, scaling, and handling outliers
- Model Training – applying multiple regression algorithms
- Model Evaluation – comparing performance with metrics and visualizations
- Insights & Future Work – interpreting results and suggesting improvements
This workflow mirrors real‑world ML projects, ensuring reproducibility, clarity, and scalability.

# Dataset
- File: automobile_performance.csv
- Target Variable: fuel_efficiency (continuous)
# Features
- engine_config → categorical (number of cylinders)
- engine_volume → numeric (engine displacement)
- power_output → numeric (horsepower)
- vehicle_mass → numeric (weight of vehicle)
- accel_capability → numeric (acceleration time)
- release_year → numeric (year of release)
- manufacture_region → categorical (region code)

# Methodology
1. Data Preprocessing
- Missing Values: Replaced ? with NaN, imputed using median strategy.
- Categorical Encoding: Applied LabelEncoder for engine_config and manufacture_region.
- Feature Scaling: Standardized features using StandardScaler.
- Outlier Detection: Removed extreme values using Z‑score threshold.
2. Feature Engineering
- Checked correlations between features and target.
- Considered transformations (log/Box‑Cox) for skewed variables.
- Ensured features were interpretable and relevant.
3. Model Training
Implemented and compared three regression algorithms:
- Linear Regression – baseline model
- Decision Tree Regressor – non‑linear, interpretable model
- Gradient Boosting Regressor – ensemble method for higher accuracy
4. Model Evaluation
Evaluated models using:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score (Coefficient of Determination)
5. Visualization
- Bar chart comparing R² scores of models
- Scatter plot of Actual vs Predicted fuel efficiency for the best model



