# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
Ground clearance is statistically unlikely to provide random amounts of variance to the linear model; as a result, ground clearance has a significant impact on mpg. The R-squared value of 0.522 tells us that about 50% of the variability of our dependent variable is explained using the linear model. Moreover, the p-value of our linear regression is considerably smaller than the assumed significance level of 0.05%. There is sufficient evidence to reject our null hypothesis. However, the model does not accurately predict the mpg of MechaCar prototypes because the R-squared value is 0.522 which indicates that roughly 50% of the variability of the outcome data cannot be explained by the model. The results are displayed below:

<img width="535" alt="Screen Shot 2022-04-05 at 4 23 08 PM" src="https://user-images.githubusercontent.com/92702922/161851944-f97e6347-6e79-4564-bed3-73a8c248ecad.png">

## Summary Statistics on Suspension Coils
While the manufacturing data meets the design specifications for all manufacturing lots in total, Lot 3 has a high variance of 170, which is above the design specifications for the MechaCar suspension coils of 100.

<img width="495" alt="Screen Shot 2022-04-05 at 4 30 08 PM" src="https://user-images.githubusercontent.com/92702922/161852972-2654d76a-6545-48e4-8a8d-9129fc86318e.png">
<img width="334" alt="Screen Shot 2022-04-05 at 4 30 32 PM" src="https://user-images.githubusercontent.com/92702922/161853023-cad82d77-3402-4356-98dd-6c524a86c5a3.png">

## T-Tests on Suspension Coils
According to our results, the p-values for Lot 1 and Lot 2 are higher than the significance level of 0.05. Therefore, we do not have sufficient evidence to reject the null hypothesis and the two means are statistically similar. Additionally, Lot 3 has a p-value of about 0.04 and is statistically different from the population mean. Therefore, we have sufficient evidence to reject the null hypothesis and the two means are statistically different.

<img width="410" alt="Screen Shot 2022-04-05 at 4 47 23 PM" src="https://user-images.githubusercontent.com/92702922/161855239-9cbf5bee-55ba-4fc1-8e4c-26f9e2eb3cb9.png">
<img width="590" alt="Screen Shot 2022-04-05 at 4 47 36 PM" src="https://user-images.githubusercontent.com/92702922/161855251-d78f07c1-16c1-4a21-b605-b762fcd41d4a.png">

## Study Design: MechaCar vs. Competition
It might be interesting and very useful to analyze a study of the MechaCar versus the competitors. The study would analyze the cost of the vehicle and how it is correlated to important factors that are usually considered, such as maintenance cost, horsepower, fuel efficiency, and safety rating. The study would set the cost as the dependent variable and the other auto features as independent variables, and could be compared to the competition for further insight.
