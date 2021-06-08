# Predicting the Chance of Getting Into Graduate School

Applying to graduate school can be quite the challenging journey. From GPA, standardized test scores, to writing your statement of purpose, and asking for letters of recommendation, the process of getting into graduate school is far from easy (and costly too). And at times, students may wonder if they are even competitive enough to apply to graduate school. 

This present analysis aims to build a multilinear regression model to predict the chance of being admitted into graduate school. The model can help students determine if they are competitive enough to start applying to graduate school or if there's still room for improvement.

## Dataset

The dataset was obtained from [Kaggle.com](https://www.kaggle.com/mohansacharya/graduate-admissions):

Mohan S Acharya, Asfia Armaan, Aneeta S Antony : A Comparison of Regression Models for Prediction of Graduate Admissions, IEEE International Conference on Computational Intelligence in Data Science 2019

The dataset contains 6 features:
1. GRE Score (out of 340; old score format)
2. TOEFL Score (out of 120; old score format
3. University Rating (out of 5)
4. Statement of Purpose Strength (out of 5)
5. Letter of Recommendation Strength (out of 5)
6. Undergraduate GPA (out of 10; CGPA)

## Model Building

Both the full model (6 features) and a reduced model (3 features; GRE Score, TOEFL Score, and GPA) are considered. The final model is the reduced model due to it's simplicity and small difference in model metrics (R-Squared, MAE, MSE, RMSE) from the full model.

## Key Findings
- GPA is the most important feature for predicting chance of admit
- GRE and TOEFL scores are also important features for predicting chance of admit
- Research is the least important feature for predicting chance of admit
- Thus, students should focus heavily on keeping or improving their GPA and maximizing their score on the GRE and TOEFL.
