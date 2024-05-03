# Q1-TO-Q4-Credit-Card-and-Financial-dashboard
**PowerBI Dashboard**
**Project Objective:**
To develop a comprehensive credit card weekly dashboard that provides real-time insightsintokey performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.
**Dax-Queries:**
**Revenue **= 'credit_card'[Annual_Fees]+'credit_card'[Total_Trans_Amt]+'credit_card'[Interest_Earned]
**Week_num2** = WEEKNUM('credit_card'[Week_Start_Date])
****AgeGroup** = **SWITCH(TRUE(),'customer'[customer_age]<30,"20-30",'customer'[customer_age]>=30&& 'customer'[customer_age]<40,"30-40",'customer'[customer_age]>=40&& 'customer'[customer_age]<50,"40-50",'customer'[customer_age]>=50&& 'customer'[customer_age]<60,"50-60",'customer'[customer_age]>=30&& 'customer'[customer_age]>=60,"60+",'customer'[customer_age]<40,"30-40","unknown")
**IncomeGroup** = SWITCH(TRUE(),'customer'[income]<35000,"Low",'customer'[income]>=35000&&'customer'[income]<70000,"Med",'customer'[income]>=70000,"High","unknown")
**Project Insights-Week 53  (31 Dec)**
WoW Chandge: 
-Revenue increased by 28.8%
Overview YTD:
Overall revenue is 57M
Total interest is 8M
Total Transaction amount is 46M
Male Customers are contributing more in revenue 31M, female 26M
Blue & Silver credit card are contributing to 93& of overall transactions
TX,NY & CA is contributing to 68%
Overall Activation rate is 57.5%
Overall Delinquent rate is 6.06%
