# An Analysis of Istanbul using airbnb Data

## Project Motivation
This analysis was completed as part of the Udacity Data Science Nanodegree program. The dataset and business problems were chosen based on past experiences of visiting the city of Istanbul.

## Library Requirements
For a full list of all requirements to run the code in this repository, please see the requirements.txt file.

## CRISP-DM
The CRISP-DM framework was adopted for this analysis project.

##### 1. Business Understanding
The project was to be centered around using airbnb data to analyse listings in the city of Istanbul. Three questions were identified that could be answered using data science methods. These questions were:

    1. Which side of the city has cheaper accommodation?
    2. Which month of the year has the best deals on accommodation?
    3. What do customers say in accommodation reviews?
  
##### 2. Data Understanding
To be able to answer the business questions above, opensource airbnb data was extracted from http://insideairbnb.com. Listings data, calendar data and review data were used from the latest version of Istanbul data found on the website.

##### 3. Prepare Data
For the first two questions above, the raw data was prepared into a dataset called DataPrepQ1.csv. This file was too large to store on GitHub but by downloading the raw data from the link provided, the DataPrep.ipynb file can be used to obtain this dataset. Likewise the raw data was prepared for the final question and this was saved as DataPrepQ2.csv. This data can be obtained in the same steps described earlier.

##### 4. Data Modelling
Data analysis and modeling were applied to answer the business questions listed above. The relevant code files for these can be found in the Code folder of this project. Each file has been documented to show the steps involved in obtaining the end results.

##### 5. Evaluating the Results
The results of the analysis were evaluated and discussed in a Medium blog post, the link of which can be found in the Summary section below. 

## Treatment of Missing Values
There were a small fraction of rows in the dataset that either had missing values for the price of a listing or had missing values for review comments. For the respective analysis, these rows were removed from the dataset as they would not have contributed to any results from the analysis.

## Main Methods of Analysis
The first two questions below were analysed and answered using statistical analysis and data visualisation methods. The final 
The final question was analysed and answered using NLP and unsupervised learning methods. In particularly TF-IDF, K-means and Word2Vec. 

## Summary
Analysis was performed on opensource airbnb data for the city of Istanbul. Three questions were considered as aprt of the analysis:

1. Which side of the city has cheaper accommodation?
2. Which month of the year has the best deals on accommodation?
3. What do customers say in accommodation reviews?

Findings from the analysis can be found on Medium blog linked below.

This repository contains the code that was used to develop analysis for the Medium blog post https://medium.com/@d.grewal1503/how-to-choose-your-accommodation-on-your-next-airbnb-getaway-7e0711eae51b. Data has not been uploaded due to size restrictions. However the data can be downloaded from http://insideairbnb.com/get-the-data.html and then used as input for the Code/DataPrep.ipynb file to produce the datasets used in the analysis files.

Some pieces of code have been copied and adapted for use from other published resources such as https://towardsdatascience.com/unsupervised-sentiment-analysis-a38bf1906483 and https://medium.com/analytics-vidhya/automated-keyword-extraction-from-articles-using-nlp-bfd864f41b34. Where this is the case, it has been stated in the docstring of the relevant functions.
