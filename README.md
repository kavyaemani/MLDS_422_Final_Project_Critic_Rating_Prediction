# MLDS_422_Final_Project_Critic_Rating_Prediction

Project Overview
- This project is part of the MLDS course at Northwestern University. The goal is to develop a machine learning workflow to predict movie critic ratings using a movie dataset from a PostgreSQL database. The workflow covers the entire machine learning process, including data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Repository Contents
- Code: Includes Jupyter notebooks and Python scripts for all steps in the machine learning workflow.
- Data: Contains a .csv file with the processed data used for analysis and modeling.
- Environment: A requirements.txt file lists the dependencies required to run the project.
- Ignore: A .gitignore file is included to avoid uploading unnecessary files.

Steps to Run
- Clone the repo.
- Install the dependencies from requirements.txt.
- Connect to the PostgreSQL database to extract the raw data.
- Run the Jupyter notebooks or scripts in order for data cleaning, EDA, feature engineering, and modeling.

Highlights
- Data Cleaning and EDA
- Visualized movie releases per year and fixed errors in the dataset.
- Identified top-rated movies pre-2010 by critics and audiences.
- Filtered popular movies based on above-average audience reviews.

Feature Engineering
- Created features like kid_friendly and dummy variables for genres.
- Designed custom features to improve the prediction of critic ratings.

Modeling
- Built six linear regression models using different feature combinations.
- Evaluated each model with R², MAE, and RMSE metrics.
- Found the best model and analyzed its performance and key features.

Future Work
- Experiment with more advanced models and regularization techniques.
- Try additional features to further improve prediction accuracy.

Note: Access to the PostgreSQL database or the provided .csv file is required to replicate this project.
