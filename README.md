# Healthcare-Disparities-in-the-United-States


## Overview
The folders and files are:

1. **Data_Visualization.ipynb**: a .ipynb file includes the codes for urban scaling, inequality anlysis, and diversity analysis.
- function _scaling_iloc_ outputs the confidence intervals, residuals, scaling exponent, R^2, and fit model
- function _getGini_ outputs the Gini index for the per capita values 
- function _get_FAMIs_ 
** input: multivariate (for example, population, GDP, and college education)
** output the residuals, scaling exponents, and model 
- Visualization of medical intra-specialty network: the categorization of medical specialties is detailed in dictionary named _groupedict_
- function _differential_evolution_ outputs the fit result of diversity from the model by Youn \textit{et al} (2016)


2. **Statistical_analyses.ipynb**: a .ipynb file includes the codes for statistical analyses
- function _silhouette_score_ output score of silhoutte analysis
- funtion _f_oneway_ outputs statistical results of one way ANOVA
- function _pairwise_tukeyhsd_ post-hoc comparisons using tukey's HSD test

3. **Data**: a list of datasets and zipped shapefiles.
- _patient_data.csv_: city-level patient data includes:
** number of healthcare spending (_spend_mean_) **//
** per capita healthcare spending (_spend_per_capita_mean_) **//
** number of health encounters (_vol_mean_) **//
** per capita health encounters (_vol_per_capita_mean_) **//
- _Specialty_Count_cbsa.csv_: city-level count of specialties 
- _SCALING_RESULT.csv_: results for 75 medical specialties

