# Predicting-customer-subscription to promotion (i.e choosing to upgrade to three-meal plan)
This dataset consists of data collected as part of an upselling promotional discount offered on March 5, 2018 where 10% of customers who were on a ‘two-meal-per-week plan’ of a meal preparation and delivery service(QuickKits) were offered a promotional discount of 40% for a three-meal-per-week plan, for two weeks. At the end of the two-week period, subscribers to the promotion would remained on the three-week plan at regular price unless they opted out.   


DATA DICTIONARY:  Variables in the Data Set QK.csv:

* SUBSCRIBE: Customer signed up for the promotion or not: “Y” if signed up, “N” if not.
* Custid: 7 digit customer identification number
* Disc: Class of customer for standard discounts: “Student” or “Senior” 
* Title: “Mr”  “Ms”  “Mrs”  or “Dr”
* LastOrder:  Date of last order:  year/month/day 
* Pcode:  Postal Code (*)
* DA_Income:  Mean Income of households in customer’s Census Dissemination Area, thousands of dollars
* DA_Under20:   Number of households in customer’s Census Dissemination Area with individuals under 20 years of age
* DA_Over60:  Number of households in customer’s Census Dissemination Area with individuals over 60 years of age
* DA_Single:  Number of households in customer’s Census Dissemination Area with only 1 person
* NumDeliv: Number of deliveries ordered in last 6 months
* NumMeals: Number of meals ordered in last 6 months (each delivery can have several meals)
* MealsPerDeliv:  Average number of meals per delivery (NumMeals/NumDeliv)
* Healthy: Number of healthy meals ordered last 6 months
* Veggie: Number of vegetarian meals ordered last 6 months
* Meaty: Number of meaty meals ordered last 6 months
* Special: Number of specialty meals ordered last 6 months
* TotPurch:  Amount purchased last 6 months in dollars
* Weeks3Meals: Number of weeks that a customer that signed up for the promotional offer stayed with the three-meal-plan, after the promotion was over.

(*) Canada has 850,000 postal codes, which are combined into 54000 Dissemination Areas. A Dissemination Area typically has between 400 and 700 households. 

