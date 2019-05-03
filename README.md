# Analyze_AB_Test_Results
Udacity Data Analyst Degree - Project 3

## Overview

A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these.

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

## What Software Do I Need?

To complete this project, i'll require the following softwares:

- Python (Numpy, Pandas, Matplotlib, StatsModels)
- Jupyter Notebook

## Part I - Probability

Statistics were computed to find out the proportions of converting. The results have being used to analyse if one page or the other led to more conversions.

## Part II - A/B Test

Next, hypothesis testing was conducted assuming the old page is better unless the new page proves to be definitely better at a Type I error rate of 5%. 

The data was bootstrapped and sampling distributions were determined for both pages. Conclusions were drawn on conversions for both pages by calculating p-values.

## Part III - Regression

Logistic regression was then performed to confirm  results of the previous steps.  Null and alternative hypotheses associated with this regression model were stated and verified using statsmodel.

Next, along with testing if the conversion rate changes for different pages, I added an effect based on which country a user lives. Statistical output using logistic regression was provided to check if country had an impact on conversion.


## Conclusions

1) There was no evidence suggesting that those who visited either page will necessary lead to more conversions
2) The country of the user did not impact the rate of conversion between the two pages
3) The interaction of country and page did not  impact the rate of conversion between the two pages
