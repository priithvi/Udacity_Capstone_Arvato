## Project Name: Udacity Data Science Nano Degree: Arvato Project

## Description
As part of the Udacity Data Science Nano Degree program, the capstone project is for data provided by 'Arvato Financial Services'. The project consists of two tasks:
1. Customer Segmentation followed by profiling of the created segments
2. Binary classification to predict probability of each customer to respond to a marketing campaign


## Tool and softwares
All data analysis is done using Jupyter Notebook based on Python 3.8.3. A standard Anaconda distribution (https://www.anaconda.com/products/individual) can be used to install Python and use Jupyter Notebook. In addition the following packages are required in Python for the project:
- lightgbm
- xgboost

## Data source and types of data
The data is downloaded from Udacity's Workspace. The following datasets are provided:
1. customers.csv: This file contains list and some characteritics of the company's customers
2. azdias.csv: This file contains the same characteritics as of the customers.csv file for Germany's general population which are not the company's customers yet
3. DIAS Information Levels - Attributes 2017.csv: This file contains the description of each of the variables/customer characteristics present in the customers.csv and azdias.csv files
4. DIAS Attributes - Values 2017.csv: This file contains the description of each of the variables present in the customers.csv and azdias.csv files, along with the dewscription of each of the categorical values taken by the variables
5. mailout_train.csv: It contains a list of customer ids of the company's customers along with a flag "RESPONSE" to indicate whether they responded to a marketing campaign in the past or not. Customer attributes are also present
6. mailout_test.csv: It contains a list of new customer ids of the company's customers. It also contains customer attributes, but the "RESPONSE" indicator is not present


## Code file
The Python code file created used to do all the analysis is available by the name: Arvato_analysis.ipynb

## Licensing, Authors, and Acknowledgements
Technical repose of the project is also create on Medium here:
This same report is present in the repository by the name: Arvato_analysis.pdf
Apart from those licensing information, anyone if free to use and reproduce the code as they like.



