# Project: Bankruptcy Prediction
_note: this is a sand box project_

## Data Science Process Model
All projects are carried out using Cross-Industry Standard Process for Data Mining (CRISP-DM)  method with the following steps (iterations among steps may be required)
	-1. Business Understanding
	-2. Data Understanding
	-3. Data Preparation
	-4. Modelling
	-5. Evaluation against business objective
	-6. Deployment

## Business Problem
An investment bank specialize in arranging corporate debt financing by finding large-scale institutional investors for corporate bonds. The bank is looking to use machine learning to predict corporate bankruptcy two years into the future for any future clients they may secure financing for

## Objective: 
To develop a machine learning model to predict whether a company would declare bankruptcy within the next 2 years

## Data: 
- The data contains 12 features ((EPS, Liquidity, Profitability, leverage Ratio etc), 100,000 instances. 
- 0.5% declared bankruptcy --> This is a small and unbalanced data set. The algorithm must be able to handle small data effectively. Data set should be manipulated to produce a balanced data set to ensure the minority class is represented. 
- Features varies in magnitudes and ranges which will skew the model.--> scaling is required
- Outliers / Missing values --> manipulation / imputation is required


