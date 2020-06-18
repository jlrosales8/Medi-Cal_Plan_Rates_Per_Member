# Medi-Cal_Plan_Rates_Per_Member
Medicaid in California is called Medi-Cal. When a person is below a certain income limit they qualify for Medi-Cal. The majority of the population has to then enroll into a Managed Care Plan once they have been approved for Medi-Cal. Depending on the county that you are in, you will have a couple of options. In order to keep health care costs low. The state pays a certain amount to each health plan who enrolls into their plans while having Medi-Cal. These amounts are dependant on the Category of Aid that you receive. 


The data collected from CHHS shows the rates that are distributed to health plans. This project goes into detail on the rates that are distributed to health plans based on the 2018 rates. These were the most current data sheets that were available. 

The four main plan models are the Two Plan, County Organized Health Systems (COHS), Regional Model/Rural Expansion, Geographic Managed Care (GMC).

# Data Collected From

https://data.chhs.ca.gov/organization/department-of-health-care-services

# Medi-Cal_Plan_Rates_Per_Member
Reviewing the each Category of Aid section by the specific Plan Model reveals that on average the County Organized Health Systems (COHS) Model has higher rates that are paid out to the health plan. One more thing to note is that the Category of Aid that consists of Pregnancy Services was not shared in the data. 

The graph and table below shows the Category of Aid broken down by Plan Model. 



![GitHub Logo](https://user-images.githubusercontent.com/66391137/84869122-7d952080-b032-11ea-9792-d38170405b69.png)

|Model                     |Category_of_Aid      |Amount     |
| -------------------------- | ---------------------| ----------- | 
| COHS                     |Adult                |  26.428571|
|                          |BCCTP                | 108.000000|
|                          |Child                |   8.428571|
|                          |LTC                  | 706.785714|
|                          |LTC/Full-Dual        | 473.000000|
|                          |OBRA                 |  28.333333|
|                          |Optional Expansion   |  34.571429|
|                          |SPD                  |  81.714286|
|                          |SPD/Full-Dual        |  18.571429|
| GMC                      |Adult                |  20.923077|
|                          |BCCTP                |  98.000000|
|                          |Child                |   6.769231|
|                          |Maternity            | 630.384615|
|                          |Optional Expansion   |  30.307692|
|                          |SPD                  |  65.307692|
|                          |SPD/Full-Dual        |  11.000000|
| Regional Rural Expansion |Adult                |  21.440000|
|                          |BCCTP                | 102.220000|
|                          |Child                |   6.320000|
|                          |LTC                  | 609.000000|
|                          |LTC/Full-Dual        | 503.000000|
|                          |Maternity            | 753.071429|
|                          |Optional Expansion   |  30.600000|
|                          |SPD                  |  77.660000|
|                          |SPD/Full-Dual        |  11.700000|
| Two Plan                 |Adult                |  18.821429|
|                          |BCCTP                |  95.285714|
|                          |Child                |   6.642857|
|                          |Maternity            | 606.000000|
|                          |Optional Expansion   |  26.392857|
|                          |SPD                  |  63.285714|
|                          |SPD/Full-Dual        |  11.928571|

When we further review the Rates paid to the health plan per mnoth, we can see that the COHS plan model ranks highest compared to all the other Models by Category of Aid. The table below shows the highest rate paid out by Model. Notice COHS Model plan ranks among the highest for each Category. 

| Rank | Model	| Category_of_Aid	| PayMonth
| ---    | --- | ---  | --- |
| 1	 | COHS	| Adult	              | 30
| 2	 | COHS	| BCCTP	              | 191
| 3	 | COHS	| Child	              | 12
| 4	 | COHS	| LTC	                | 1002
| 5	 | COHS	| LTC/Full-Dual	      | 578
| 6	 | Two Plan  | Plan	Maternity	    | 785
| 7 | COHS	| OBRA	              | 50
| 8 | COHS	| Optional Expansion	| 45
| 9 | COHS	| SPD	                | 96
| 10 | Two Plan	| SPD/Full-Dual	| 40

The COHS model is based on their only being one plan in that specific county. So the question can be asked: since in those counties there is only one health plan, is the lack of competition to that one health plan the reason why the rates are so high?

When we view the same table but focusing on the least capitation payout per month we can see two things. 
1. The COHS model still appears but this is due to the fact that in the data provided, the state only shares the rates for LTC, LTC/Full-Maternity, and OBRA for COHS and not other health plans. 


| Rank | Model	| Category_of_Aid	| PayMonth
| --- | --- | --- | --- |
| 1	 | Regional Rural Expansion	| Adult |	13
| 2	 | COHS	| BCCTP	| 68
| 3	 | Two Plan |	Child	| 5
| 4	 | Regional Rural Expansion	| Child	| 5
| 5	 | COHS	| LTC	| 333
| 6	 | COHS	| LTC/Full-Dual	| 367
| 7	 | Two Plan	| Maternity	| 488
| 8 | COHS	| OBRA	| 15
| 9 | Two Plan	| Optional Expansion	| 21
| 10 | Two Plan	| SPD	| 47
| 11 | GMC	| SPD/Full-Dual	| 9
| 12 | Two Plan	| SPD/Full-Dual	| 9
| 13 | Regional Rural Expansion	| SPD/Full-Dual	| 9

Once we remove the fields where COHS is the only data provided we can see the second obervation. 

| Rank | Model	| Category_of_Aid	| PayMonth
| --- | --- | --- | --- |
| 1	 | Regional Rural Expansion	| Adult |	13
| 2	 | COHS	| BCCTP	| 68
| 3	 | Two Plan |	Child	| 5
| 4	 | Regional Rural Expansion	| Child	| 5
| 5	 | Two Plan	| Maternity	| 488
| 6 | Two Plan	| Optional Expansion	| 21
| 7 | Two Plan	| SPD	| 47
| 8 | GMC	| SPD/Full-Dual	| 9
| 9 | Two Plan	| SPD/Full-Dual	| 9
| 10 | Regional Rural Expansion	| SPD/Full-Dual	| 9

On average the Regional Rural Expansion model and the Two Plan Model produce the lowest rates paid out to the health plan. 

When viewing the Category of Aid across all the counties we can see that that not all the counties report the Capitation Rates that are provided to the health plans. This can be seen on how some counties are missing complete rates for those counties. This can be attributed to those counties not producing members with that Category of Aid or if the state is not providing that information.  

![GitHub Logo](https://user-images.githubusercontent.com/66391137/85070605-f1d2df80-b16a-11ea-817c-1d825ccd38e0.png)

Lastly, one thing to note is when comparing the counties to the Category of Aid, the counties that provide information for the LTC population will usually not supply information for the Maternity population and vice versa. 

![GitHub Logo](https://user-images.githubusercontent.com/66391137/85070576-e67fb400-b16a-11ea-97b2-ed259eb890c5.png)

