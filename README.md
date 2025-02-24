# ML-Project >> Wine prediction

Project Description >> A Wine Quality Prediction System is a machine learning-based system designed to evaluate the quality of wine based on various physicochemical properties. The system uses historical data of wine samples, including features like acidity, alcohol content, pH level, residual sugar, and more, to predict the quality of new wine samples on a predefined scale (usually 1 to 10).

Dataset Description >> Wine Quality Dataset Description
The Wine Quality Dataset is a well-known dataset available in the UCI Machine Learning Repository. 
It contains physicochemical attributes of red and white wine samples, 
along with their quality scores, rated by wine tasters. The dataset is commonly used 
for regression and classification tasks in machine learning.

Dataset Overview
Number of Samples:
Red wine: 1,599 samples
Number of Features: 11 (numerical)

Target Variable: Wine Quality Score (integer value ranging from 0 to 10)
Type: Multivariate dataset

Dataset Attributes
Feature	Description	Data Type
Fixed Acidity	Concentration of non-volatile acids (e.g., tartaric acid)	Float
Volatile Acidity	Concentration of volatile acids (e.g., acetic acid)	Float
Citric Acid	Amount of citric acid present (adds freshness)	Float
Residual Sugar	Amount of sugar left after fermentation	Float
Chlorides	Salt content in the wine	Float
Free Sulfur Dioxide	SO₂ available to prevent microbial growth	Float
Total Sulfur Dioxide	Total SO₂ (free + bound), used as a preservative	Float
Density	Mass per unit volume, affects wine body	Float
pH	Measure of acidity or alkalinity	Float
Sulphates	Sulfur compounds contributing to antimicrobial properties	Float
Alcohol	Alcohol content (% volume)	Float
Quality (Target Variable)	Wine quality score (scale 0–10)	Integer
Target Variable (Quality Score) Distribution

The wine quality is rated on a scale of 0 to 10, but most scores range from 3 to 9.
The majority of wines have quality scores between 5 and 7, 
making it an imbalanced dataset where extreme quality ratings (0, 1, 9, 10) are rare.
    
Dataset Usage
Regression Task: Predicting the exact quality score as a continuous variable.
Classification Task: Converting scores into categories (e.g., Low Quality (≤5), Medium (6), High Quality (≥7)).
Feature Analysis: Understanding how different physicochecal properties affect wine quality
