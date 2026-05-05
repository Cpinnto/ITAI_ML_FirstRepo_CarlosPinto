# Annual Medical Cost Prediction - Final Project
**Student:** Carlos Mariano Pinto Alfaro  
**Course:** ITAI-1371 - Machine Learning  
**Date:** May 4, 2026

## Project Overview
This repository contains the final project for the Machine Learning course. The objective is to predict annual medical costs for patients based on demographic and lifestyle factors using various regression techniques. 

This final version builds upon the Midterm work by implementing critical technical feedback, including outlier handling and data normalization.

## Key Findings & Results
* **Champion Model:** The **Voting Regressor** (an ensemble of XGBoost, Random Forest, and Linear Regression) was the top performer.
* [cite_start]**Accuracy:** Achieved an **R² score of 0.81** on the unseen test set, explaining 81% of the cost variation[cite: 166].
* [cite_start]**Error Rate:** The Mean Absolute Error (MAE) was approximately **$2,518**, showing high predictive reliability for healthcare budgeting[cite: 166].

## Repository Structure
To keep things organized, I have structured the files as follows:

* [cite_start]**[Final Project ML Carlos Pinto.ipynb](./Final%20Project%20ML%20Carlos%20Pinto.ipynb):** The main Jupyter Notebook with the end-to-end pipeline (Preprocessing, Training, and Evaluation)[cite: 154].
* **[final_clean_dataset.csv](./final_clean_dataset.csv):** The dataset used for training and testing.
* [cite_start]**[Analysis_Report_Carlos_Pinto.pdf](./Analysis%20Report%20Carlos%20Pinto.pdf):** A detailed technical report explaining the methodology and model selection [cite: 1-37].
* [cite_start]**[Model_Comparison_Table_Carlos_Pinto.pdf](./Model_Comparison_Table_Carlos_Pinto.pdf):** A clean summary table of the performance metrics for all 7 models tested [cite: 155-172].
* [cite_start]**[Contribution_Summary_Carlos_Pinto.pdf](./Contribution%20Summary%20Carlos%20Pinto.pdf):** Individual statement of work and contribution for this final stage [cite: 38-54].
* [cite_start]**[Final Project - Presentation.pdf](./Final%20Project%20-%20Presentation.pdf):** The slide deck for the final class presentation [cite: 55-154].

## Technical Improvements (Feedback Implementation)
Following the instructor's recommendations from the Midterm:
1. [cite_start]**Outlier Filtering:** Removed records with costs above $30,000 to improve model generalization[cite: 16, 170].
2. [cite_start]**Log Transformation:** Applied `log1p` to the target variable to address the right-skewed nature of medical expenses[cite: 18, 169].
3. [cite_start]**Feature Cleanup:** Dropped flawed interaction terms to ensure data integrity[cite: 20, 171].

