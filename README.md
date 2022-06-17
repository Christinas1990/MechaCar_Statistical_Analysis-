# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Screen Shot 2022-06-15 at 8 41 33 PM](https://user-images.githubusercontent.com/100255000/173965400-8e9f6783-7263-418c-9468-ead386f614c8.png)

According to the result, there are fice variables/coefficients provided a non-random amount of variance to the mpg values; vehicle_length, weight, spoiler angle, ground clearance and AWD. 
The slope of the linear model is not zero. The linear model predicts 68% as the R-squared value is 0.6825. 
Also the P-Value 5.35e-11 tells the null hypothesis is falase negative error which is not significant and probability of being its wrong is high. 

## Summary Statistics on Suspension Coils

<img width="687" alt="Screen Shot 2022-06-16 at 6 50 44 PM" src="https://user-images.githubusercontent.com/100255000/174191170-ba07746c-f116-4635-837c-d0bcfb005d86.png">
<img width="695" alt="Screen Shot 2022-06-16 at 6 51 05 PM" src="https://user-images.githubusercontent.com/100255000/174191189-492d9071-5882-4eb1-ba6b-9758face6da9.png">
<img width="727" alt="Screen Shot 2022-06-16 at 6 51 18 PM" src="https://user-images.githubusercontent.com/100255000/174191198-0ba3b03f-0725-416d-ae0d-afa68b1f213c.png">
<img width="669" alt="Screen Shot 2022-06-16 at 6 51 25 PM" src="https://user-images.githubusercontent.com/100255000/174191202-7f5ec869-f052-414e-b2fa-42e6c3c14ed0.png">

All lot summary table indicates that variance of the suspension coils does not exceed 
100 pounds per square inch.(Image 3) 
On the other hand by lot table shows lot3 weights more than 100 pounds, which should be looked close into. 

## T-Tests on Suspension Coils

<img width="631" alt="Screen Shot 2022-06-16 at 9 29 50 PM" src="https://user-images.githubusercontent.com/100255000/174204366-0d15cc74-c9d5-406c-bf1b-8018788f8b49.png">
<img width="673" alt="Screen Shot 2022-06-16 at 7 46 50 PM" src="https://user-images.githubusercontent.com/100255000/174195961-c063e5f5-a1e6-4778-9cae-acac8f8db8d5.png">
<img width="630" alt="Screen Shot 2022-06-16 at 7 00 12 PM" src="https://user-images.githubusercontent.com/100255000/174191997-380c636b-904b-404b-9258-494b5f16e538.png">
<img width="677" alt="Screen Shot 2022-06-16 at 6 58 28 PM" src="https://user-images.githubusercontent.com/100255000/174191863-d2629e83-92f2-41ee-8f0c-436d85fa47e2.png">

These results show the paried t-tests of each and all manufacturing lots against mean PSI of the population.

* All Lots are not signifiantly different from the population mean with a p-value of 0.06 meaning we fail to reject null hypothesis. 
* For Lot 1 we also fail to reject null hypothesis since it has a p-value of 1 which is not significantly different. 
* Same thing goes to Lot 2, with p-value of 0.61, we fail to reject null hypothesis. 
* Lastly, for the Lot 3, it has P-value of 0.04 meaning which is significantly smaller than the other two lots. However, the confidence interval for the this Lot excludes the predicted population mean. 


## Study Design: MechaCar vs Competition

In my opinion, metrics can be tested are; fuel effiency, cost and capacity, as they are the most great concerns when people decide what car they want to buy.  Null hypothesis will be Mechacar would be statistically similar to other car brands on those 3 metrics and Alternate would say the opppsite. I would recommand ANOVA which can give us outcomes from large datasets. We are comparing Mechacar with various companies and brands cars. Its a mean to compare single dependent variable across a single independent variable with multiple groups. For the test we need datas from many car companies, which can be easily collected from. 

