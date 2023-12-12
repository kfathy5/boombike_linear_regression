# The bikes rental prediction for BoomBikes Company
> The bike rental prediction for BoomBikes aims to model the demand for shared bikes using independent variables. This will help the management understand how demand varies with different features, enabling them to adjust the business strategy accordingly. The model also provides insights into the demand dynamics of a new market, allowing the company to meet customer expectations effectively.


## General Information
This is Linear Regression Assignment to build ML model using Python to predict the bikes rental prediction for BoomBikes company

## Conclusions

The model has an R-squared value of 0.844, indicating that around 84.4% of the variability in the dependent variable can be explained by the independent variables included in the model. The adjusted R-squared value is 0.839, which takes into account the number of predictors in the model.

The F-statistic is 178.3, and the corresponding p-value is very low (3.23E-188), suggesting that the overall model is statistically significant.

The coefficients of the independent variables indicate the strength and direction of their relationship with the dependent variable. The constant term (intercept) has a coefficient of 0.1558.

The coefficients of the other independent variables are as follows:

"yr" (year): 0.2344
"workingday": 0.0542
"temp" (temperature): 0.4396
"windspeed": -0.1648
"season_Summer": 0.0781
"season_Winter": 0.1322
"mnth_Aug" (month August): 0.0446
"mnth_Dec" (month December): -0.054
"mnth_Feb" (month February): -0.0463
"mnth_Jan" (month January): -0.0797
"mnth_Nov" (month November): -0.0434
"mnth_Sep" (month September): 0.0978
"weekday_Sun" (Sunday): 0.0646
"weathersit_Light Snow": -0.2953
"weathersit_Mist + Cloudy": -0.0822
Each coefficient is associated with a standard error, t-value, and p-value. The t-value measures the significance of each coefficient, and the p-value indicates the probability of observing such a coefficient by chance alone.

The confidence intervals [0.025, 0.975] provide a range within which we can be confident that the true population value lies for each coefficient.

Findings:
Based on this OLS model, we can infer that several independent variables have a significant impact on the dependent variable "cnt."

Positive relationships:

The year ("yr") variable has a positive coefficient of 0.2344, suggesting that as the year increases, the count also tends to increase.
Temperature ("temp") has a positive coefficient of 0.4396, indicating that higher temperatures are associated with higher counts.
Negative relationships:

Windspeed has a negative coefficient of -0.1648, suggesting that higher windspeeds are associated with lower counts.
Various month variables (e.g., "mnth_Dec," "mnth_Feb") have negative coefficients, indicating that counts tend to be lower in these months compared to a reference month.
The weather variables ("weathersit_Light Snow" and "weathersit_Mist + Cloudy") also have negative coefficients, indicating that unfavorable weather conditions are associated with lower counts.
Other variables:

The variables "workingday," "season_Summer," "season_Winter," and "weekday_Sun" have positive coefficients, suggesting that these factors are associated with higher counts.
Overall, this model provides insights into the relationships between the independent variables and the dependent variable, allowing for predictions and further analysis of count patterns.

## Technologies Used
- pandas
- numpy
- seaborn
- matplotlib
- statsmodels
- sci-kit learn
