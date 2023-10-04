# coupon
https://github.com/rfisher133/coupon.git

<b> Project:</b> This is a project assignment that seeks to answer the equestion “Will a customer accept the coupon?”. For this project
survey data was used and the coupon acceptance rate for coupons for restaurants with meals less than $20 was investigated. 

<b>Data Source:</b> UCI Machine Learning repository, data collected via a survey on Amazon Mechanical Turk and costumers acceptance of coupons 
while driving in the vicinity of merchants. The data file "coupons.csv" should be utilized to load the survey data. 

<b>Data Cleaning:</b> The null data was removed based on still retaining a significant amount of the data for the investigations. 

<b>Investigation Process:</b> The accepted and non-accepted coupons were graphed for visual observation of correlation of acceptance of the coupons. The categories graphed included; Income, Age, Gender, Marital Status, Weather, Time of Day. 

<b>Findings:</b> 
- Income had some correlation on the acceptance rate with higher on the < $75,000 income. 
- Age had some correlation on the acceptance rate with lower on the 50 years plus category.
- Gender was not a factor on the acceptance rate
- Martial status was not a significant factor on acceptance rate. 
- Weather was a large factor with sunny weather significantly increasing the acceptance rate. 
- Time of Day was a factor with lower acceptance before 7 am and after 10 pm. 

<b>Target Groups:</b>
Two target groups were setup to test the change in acceptance rate compared to the average. 
Target Group 1 was based on demographics with income < $75,000 and age < 50 yrs. The acceptance rate went up from 70.9% to 74%
Target Group 2 was based on weather and time with sunny weather and after 7 am and before 10pm. The acceptance rate went up from 70.9% to 80.9%

<b>Next steps:</b>
Next steps would be to convert the identified categories (income, age, weather & time) from strings to numerical values.
The numerical substitutions would allow for use in ML.
