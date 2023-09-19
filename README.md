# Data-Prep


The project is an individual project done as a part of a Data Science course. The data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). It contains information about individual factors that might affect personal income. The project is divided into these parts:
## Iteration 1:
### Part 1: 
- Describes the variables in the dataset and contextualizes the dataset
- Drops categories in the dataset that are redundant
- Shows summary statistics for the data
- Univariate analysis is performed on each variable
- Justifies why each variable is kept or removed from the dataset 
- Generates attribute descriptors for all variables (decision for any descriptor statistics or plot is justified)
- Discusses the data distribution
### Part 2:
- Outliers are added to the data as it was a part of the project requirements
- Procedure is created to remove or simulate data to replace outliers and missing data
- Effects of the data cleaning procedures are evaluated
## Iteration 2:
### Part 1:
- Instructor comments from Iteration 1 are addressed
### Part 2:
- Encodes the data in order to scale it
- Data scaling techniques are used to scale the data (Min-max scaling, Max-abs scaler, Robust scaler, Quantile transform scaler)
-  Data discretization is done (equal-width descretization, equal-frequency discretization)
-  Data standardization is odone (Z-score, Log)
-   The effects of the data scaling techniques on the data are observed and discussed
### Part 3
- Outliers are removed
- Missing data and outliers are handled by evaluating various techniques and choosing the best one (Linear Regression, KNN), median is used as the baseline strategy to improve upon for missing data and upper and lower quartiles are used as the baseline strategy for outliers
- Best scaler + regression combination is found using the evaluation technique, Mean Squared Error
- Every decision is discussed in depth and justified


## Author
Apurva Acharya
