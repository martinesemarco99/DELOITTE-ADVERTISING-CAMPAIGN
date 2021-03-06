# DELOITTE - ADVERTISING - CAMPAIGN
<p> This report refers to the study conducted on the business case: “Evaluating the impact of an advertising campaign”. Our direct attention was into analysing the impact of an advertising campaign on the sales of a company that sells perfumes online. So the main goal was to verify if the ad campaign was effective or not. The advertising campaign started on December 3rd, 2019 and ended on December 24th of the same year.
Particular attention was paid to the seasonality of the time series and the difference between correlation and causation.
The ideal way to estimate advertising effectiveness is to get an estimate of the counterfactual: what would have happened without ad exposures. More generally, there is likely to be confounding factors that affect both exposure to ads and website visits (and the propensity of purchase), which make causal interpretations of observed relationships problematic.
Furthermore, if data at hand were in fact generated by ad managers who increase ad expenditure in periods of the year when the purchase probability is higher, then the observed relationship between ad campaigns and sales could be highly predictive for the historical data but not useful in predicting the causal impact of explicitly assigning additional resources to an ad campaign.

  
 ## Methodology and modelling approach 
 <p> In order to conduct this analysis we performed a general data analysis through a Multivariate Linear Regression, Decision Tree and Correlation plots between sales and visits. For the particual time series we used the ARIMA, SARIMAX and FBPROPHET models. Finally we performed a causality analyisis using the Google's Causality Impact Model. 
   
