# EDA_study_1
SUPERMARKET SALES ANALYSIS

Information regarding attributes:
Invoice id: Computer generated sales slip invoice identification number 
Branch: Branch of supercenter (3 branches are available identified by A, B and C). 
City: Location of supercenters 
Customer type: Type of customers, recorded by Members for customers using member card and Normal for without member card. 
Gender: Gender type of customer 
Product line: General item categorization groups - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel 
Unit price: Price of each product in $ 
Quantity: Number of products purchased by customer 
Tax 5%: tax fee for customer buying 
Total: Total price including tax 
Date: Date of purchase (Record available from January 2019 to March 2019) 
Time: Purchase time (10am to 9pm) 
Payment: Payment used by customer for purchase (3 methods are available – Cash, Credit card and Ewallet) 
COGS: Cost of goods sold 
Gross margin percentage: Gross margin percentage 
Gross income: Gross income 
Rating: Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)


Conclusion:
I conducted an exploratory data analysis (EDA) on the supermarket sales data. Here are some key findings:

1) A perfect positive correlation (correlation) was found between the variables Tax 5%, Total, cogs, gross income.
2) The average of customer classification degrees (Rating) was found to be approximately 7, lower limit4, upper limit 10.
3) Tax 5%, Total, COGS, gross income variables show a right skewed distribution; Unit price, Quantity, Date, Rating variables are close to uniform distribution. It was found that the gross margin percentage variable took a single value.
4) The number of branches is very close to each other (almost equal).
5) In general, when payment methods are examined by gender; women prefer "Credit Card" and "Cash Payment", while men prefer "Ewallet".
6) The relationship of tax 5% and Total variables with a correlation relationship of 1 was shown on the graph and a linear relationship was found. A few linear correlations were found between Unit Price and Total variables with a correlation of 0.63. Products with a low "Unit Price" were found to have a low "Total".
7) Among the branches, the C branch is the most profitable in terms of gross income. Across the sexes, women earn more in terms of gross income.
8) When the product groups are examined, "home and lifestyle" brings the highest amount and "fashion accessories" brings the lowest amount.
9) When the purchases made are analyzed as "total"; women earned the most in "home and lifestyle", the lowest in "health and beauty", men earned the most in "health and beauty", and the lowest in "food and beverages" categories. Despite this, when the purchases made are examined in number; women bought products mostly from "fashion accessories", least "health and beauty", men mostly "health and beauty", and lowest "sport and travel" categories.
10) When the expenditures made in terms of genders are examined; The total expenditure of women is higher than that of men.
11) Gross income is in the highest "food and beverages" category, and the lowest in "health and beauty" category. The highest tax is in the "home and lifestyle" category, and the lowest in the "fashion accessories" category.
