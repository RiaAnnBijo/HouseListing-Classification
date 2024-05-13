# Project Name: House Listing Website Data Analysis

## Description:
This project aims to extract and analyze data from a house listing website. The primary objectives include data extraction through web scraping, preprocessing techniques such as cleaning, standardizing, and feature engineering, classification of addresses into specific street types, and model evaluation using various machine learning algorithms. 

## 1.Data Extraction:

* Utilize web scraping techniques with Selenium to gather data from the house listing website.
* Convert the extracted data into a DataFrame using Pandas and save it as a CSV file for easier access in subsequent analyses.
  
## Data Preprocessing:

* Perform standard data preprocessing techniques:
* Clean the data to handle missing values, duplicates, and inconsistencies.
* Standardize the data to ensure uniformity across features.
* Conduct feature engineering to extract relevant information from the address column, such as street names.
* Encode categorical data to convert textual information into numerical form, facilitating model training.

## Classification Models:
* Implement five classification models using Scikit-learn:
  * Random Forest
  * Decision Tree
  * K-Nearest Neighbors (KNN)
  * Support Vector Classifier (SVC)
  * Naive Bayes
* Utilize grid search to optimize model hyperparameters and improve accuracy.
* Employ cross-validation techniques to enhance the robustness of the models and obtain reliable accuracy estimates.

## Dependencies:

* Python 3.x
* Jupyter Notebook
* Selenium
* Pandas
* Scikit-learn

## Contributors:
Ria Ann Bijo

## Acknowledgements:
* Selenium: https://www.selenium.dev/
* Pandas: https://pandas.pydata.org/
* Scikit-learn: https://scikit-learn.org/
