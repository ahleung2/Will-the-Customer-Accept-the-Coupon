# Will the Customer Accept the Coupon?
## Overview:
The goal of this project is to utilize data visualization and exploration techniques to distinguish between customers who accepted a driving coupon versus those that did not.

## Data:
The data used in this project comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. In short, the data consists of various attributes related to different driving scenarios such as passenger, weather, and time. Based on these attributes drivers are then asked whether they will accept the coupon. For more details on the dataset, please refer to the following notebook: [Notebook](https://github.com/ahleung2/Will-the-Customer-Accept-the-Coupon/blob/main/Leung_Aaron_coupon_acceptance.ipynb) 

## Findings 
In this project, I first examined the distribution of all coupon types, then investigated the following coupon types: bar and coffee house. Described below are the summary of the findings for each respective group as well as conclusions that can be derived based on these findings.

### 1. All Coupon Types:
If we take into account all coupon types, we find that 56.9% of drivers accepted the coupon. It seems that distributing coupons is still a great method for promoting business.

### 2. Bar Coupon:
For bar coupons, I found that drivers with the following characteristics were more likely to accept the coupon:
1. they are within the age range: 25 - 30
2. frequent the bar more than once a month
3. do not have passengers that were kids
4. not widowed
5. do not have occupation in farming, fishing and forestry
6. have income greater than 50K

In general, drivers who accept the coupon are more likely young adults who are married but without kids. Additionally, these drivers tend to have occupations that perhaps involve more social gatherings. Finally, these drivers most likely come from background of higher socioeconomic status, meaning they have greater dispoable income to spend at the bar. Therefore, I would recommend targeting young married couple with no kids and who are holding white collar jobs.

### 2. Coffee House Coupon:
For coffee house coupons, I fount that drivers were the following characteristics were more likley to accept the coupon:
1. Driver is with Friends
2. Driver has no urgent place to be
3. Driver is single and is in the age groups: below 21, 21 and 26
4. Time of day is 10 am and 2pm
5. Driver frequents Coffee House more than once a month
6. Drivers are students or unemployed
7. Coupon expires after a day

Similar to bar coupons, drivers who accept the coupon are more likley young adults who are either students are unemployed. Additionally, coupons that are sent at 10am or 2pm are more likley to be accepted. Finally, sending coupons that don't expire immediately are more likely to be accepted. This gives the driver more time to plan when to use the coupon.

## Conclusion and Recommendations
Based on the findings, I would recommend targeting young adults with higher dispoable income with bar coupons. On the other hand, I would recommend targeting young adults who are either students or unemployed with coffee coupon. Additionally, with coffee coupon, it is essential to send the coupon at a appropriate time (between 10am and 2pm) and ahead of expiration date.
