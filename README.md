# MechaCar_Statistical_Analysis-

## Linear Regression to Predict MPG

<img width="449" alt="linear_regression" src="https://user-images.githubusercontent.com/93399107/164127018-f8894a67-698c-4a62-ae5a-fba627b5eedd.PNG">


The variables/coefficients that provided a non-random amount of variance to the mpg values in the dataset were Vehicle Length and the Ground Clearane. The intercept was also significant, and we can assume that other variables had an impact on our results. The slope of the linear model is not considered zero since the p-value is 5.35e-11 which is well below our normal level of significance of 0.05. This linear model does predict mpg of MechaCar prototypes effectively with an r-squared value of 0.7149, or 71% accuracy.


## T-Tests on Suspension Coils

### Total Summary

<img width="320" alt="total_summary" src="https://user-images.githubusercontent.com/93399107/164126665-b7d87168-459f-4391-9e13-2634c05dbb58.PNG">

### Lot Summary

<img width="457" alt="lot_summary" src="https://user-images.githubusercontent.com/93399107/164126694-ccc9d80a-28b5-47ab-8834-af1afc6502e6.PNG">

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data does meet this design specification for all manufacturing lots at a variance of 62. Although lot 1 and 2 fall within the specification, lot 3 exceeds the threshold at a variance of 170 pounds.

## Summary Statistics on Suspension Coils

<img width="311" alt="t_test" src="https://user-images.githubusercontent.com/93399107/164129201-07482110-8355-452f-8279-4231a1c20455.PNG">

The T-test for the suspension coils across all manufacturing lots shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis. 

<img width="302" alt="lot_1" src="https://user-images.githubusercontent.com/93399107/164129782-07f24675-7b3c-43d4-9c5a-bdeea6aad4ff.PNG">

The T-test for the suspension coils for Lot 1 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis. 

<img width="300" alt="lot_2" src="https://user-images.githubusercontent.com/93399107/164129793-37d652fc-186c-4bf8-aee8-20b29b7ccd2b.PNG">

The T-test for the suspension coils for Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough for us to reject the null hypothesis. 

<img width="280" alt="lot_3" src="https://user-images.githubusercontent.com/93399107/164129813-0ac3230a-14b3-42e3-805c-153f0d348077.PNG">

The T-test for the suspension coils for Lot 3 shows that they are slightly statistically different from the population mean, and the p-value is low enough for us to reject the null hypothesis. Lot 3 could be investigated further or removed from our dataset for more accuracy.

## Study Design: MechaCar vs Competition

### What metric or metrics are you going to test?

-Fuel Efficiency (city)

-Fuel Efficiency (highway)

-Safety Rating

-Cost

-Vehicle Emissions

-Average Maintenance Cost
    
### What is the null hypothesis or alternative hypothesis?

Null Hypothesis: MechaCar is priced correctly based on its performance of key variables.

Alternative Hypothesis: MechaCar is NOT priced correctly based on performance of key variables.

### What statistical test would you use to test the hypothesis? And why?

To test this hypothesis I would use a multiple linear regression to determine which variables have the highest correlation/predictability.
    
### What data is needed to run the statistical test?

I would need to collect all of the data for the other car companies as well as the data in my metrics that was not collected by MechaCar.

