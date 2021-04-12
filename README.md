# MechaCar_Statistical_Analysis-

## Linear Regression to Predict MPG
- From our analysis, we determined that the intercept, vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the mpg values in the dataset.

- Our p-value is 5.35e-11, which is significantly lower than our assumed significance level of 0.05%. This means that there is enough evidence to reject our null hypothesis and assume that the slope of the linear model is not zero.

- Our multiple r-squared value is 0.7149. This tells us that roughly 71.5% of all mpg predictions will be correct when using this linear model.

## Summary Statistics on Suspension Coils

Based on our results, we can see that the pounds per square ince (PSI) variance is 62.29, which meets design specifications. 

However, when we break the results down by lot, we can see that lot 3 fails to meet design specifications, as the variance is 170.29, which is exceeds the 100 pounds per square inch limit.

## T-Tests on Suspension Coils

H0 : There is no statistical difference between the observed sample mean and its presumed population mean.
Ha : There is a statistical difference between the observed sample mean and its presumed population mean.
Significance Level: 0.05

### T-Test: All Manufacturing Lots
- Our p-value is 0.06 which is higher than our significance level. Therefore our null hypothesis passes and we can conclude that the two means are similar.
### T-Test: Lot 1
- Our p-value is 1.00 which is higher than our significance level. Therefore our null hypothesis passes and we can conclude that the two means are similar.
### T-Test: Lot 2
- Our p-value is 0.61 which is higher than our significance level. Therefore our null hypothesis passes and we can conclude that the two means are similar.
### T-Test: Lot 3
- Our p-value is 0.04 which is lower than our significance level. Therefore our null hypothesis fails and we can conclude that the two means are not similar.
