# Prediction-Classification-on-Freddie-Mac-Single-family-loan-data

This repository contains files for analysis on FreddieMac's Single family-loan-data for prediction of interest rates and classification of delinquent loans http://www.freddiemac.com/research/datasets/sf_loanlevel_dataset.html 

### This repository contains:
* Data wrangling : 
  * Data Download : Programmatically download the data files (python script for auto sign in)
  * Preprocessing :  prileminary data analysis to detect bad data and summarize key information
  * Exploratory Data Analysis : jupyter notebook to graphically represent different summaries of data varying during 2007-2008 financial 
                                crisis, market stability during 2009 
* Prediction of interest rate : Python script in jupyter notebook to programmatically download and preprocess the data, perform variable                                   selection using Recursive Feature Elimination and predict interest rates for rolling quaters using Random                                 Forest & Neural Network algorithms.
                               *What-if analysis : (Financial crisis test) Test algorithm on four rolling quaters of 2007-2008. 
                                 (Economic boom (1999, 2013)): Test the algorithm during the economic boom period
                                 
 * Classification of Delinquent Loans : jupyter notebook to programmatically download and preprocess the data, build a regression                                                 model to classifiy the delinquent loans.
 * Docker : Build Docker images to execute the project run
