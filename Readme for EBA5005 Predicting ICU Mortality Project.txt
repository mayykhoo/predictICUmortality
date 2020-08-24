Below is a summary of the submission package for EBA5005 Specialized Predictive Modelling and Forecasting:

Dataset Source: https://physionet.org/content/challenge-2012/1.0.0/

Group Report: EBA5005 Report - Team Chocolates.pdf

Presentation Slides (Revised to incorporate presentation feedback): Predicting ICU Mortality - Team Chocolate.pptx

Python Codes:
	(1) 01 Data Extraction.ipynb (Data extraction) 
	(2) 02 Data Cleaning and Feature Engineering.ipynb (Data cleaning and feature engineering)
	(3) 03 Feature Selection Under.ipynb (Feature selection and binary classification)
	(4) 04 Random Survival Forest.ipynb (Survival analysis using random survival forest)
	(5) 05 KMF Plots.ipynb (Kaplan Meier Estimator plots)
	(6) 06 Survival Analysis lifelines.ipynb (Survival analysis using cox proportional hazard model)

Instructions: 
Step 1. Due to large file size, please download the dataset from https://physionet.org/content/challenge-2012/1.0.0/ 

The definition of the files are as follows:
set - #: independent variables for each patient
Outcomes-#.txt: dependent variables

Train Set
a. set - a 
b. Outcomes-a.txt 

Test Set
a. set - b
b. Outcomes-b.txt

Unseen Set
a. set - c
b. Outcomes-c.txt

Step 2. Create a data folder and unzip set - a (individual patient's data) into the data folder (i.e. final directory: data/set-a/######.txt)
Step 3. Place the Outcomes-a.txt in the data folder (i.e. final directory: data/Outcomes-a.txt)