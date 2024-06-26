**ShopSmart Inc.** is an e-commerce platform that sells a variety of products online. The company aims to optimize its website and enhance customer satisfaction by understanding customer behavior and preferences. To achieve this goal, ShopSmart Inc. plans to analyze the data collected from its website to gain insights into customer interactions, purchasing patterns, and product preferences.

**Project Objective**: The objective of this project is to utilize data from ShopSmart Inc.'s website to understand customer behavior and preferences. By analyzing the data, the company aims to:

1. Segment customers based on their preferences, geographic location, and purchasing behavior.
2. Enhance website usability and user experience based on insights gained from customer interactions.
3. Optimize product offerings and marketing strategies to improve customer satisfaction and retention.

**Data Sources:**
The data for this project will be sourced from ShopSmart Inc.'s website and will include various attributes such as customer IDs, device IDs, transaction details, product information, and timestamps of customer interactions.
 
**Methodology:**
The project will involve data wrangling to pre-process the dataset, followed by exploratory data analysis (EDA) to uncover patterns and trends in customer behavior. Visualization techniques will be used to present the findings effectively.
Expected Outcome:

By understanding customer behavior and preferences, ShopSmart Inc. aims to optimize its website, product offerings, and marketing strategies to increase customer satisfaction, retention, and ultimately, revenue.
 
You are provided with 5 datasets from different tables, your first task is to merge the datasets, clean and wrangle the dataset, engineer new features from event data. Then identify the following:

**a.     Visit Frequency:**
How often does this customer visit the website, based on the provided data?
Can you identify any patterns or trends in the customer's visit frequency?

**b. 	Location Analysis:**
What is the customer's location based on the provided data?
How might the customer's location influence their purchasing behavior?

**c.  	Overall Purchase Behavior:**
Based on the data provided, what insights can you draw about this customer's overall behavior on the website?
How might these insights inform marketing strategies or personalized recommendations for this customer?

#
**Findings**


Total **interactions (652958)** with the website
- **added to cart (46%)**
- **visit (26%)**
- **removed from cart (23%)**
- **checked out (5%)**

Total number of customers is **10000**
    - Customers that only visited - **853 (8.35%)**

Total devices used on the sites is **10000**

**10000 customers visited the website**

shows that each customer used 1 device to interact with the website

#

**Location**
- 243 Countries including Islands
- 7 continents
- Most Number of Customers Continent: **Africa**
- Most Number of Customers Country that Visited: **Korea**

ShopSmart Inc has customers from all around the world

#


**Visits** <br>

- **50.31%** of the customers visited the website for just **one day** while there was a huge drop on day 2 (1.07%) and after day 2 there was a steady little increase till **day 11 (12.95%)**.
This means that some customers took up to 11 days visiting products on the website to make a decision on the products they want to purchase.

- **Saturday** is the day all Customers (10000) visited the website and also the day most interaction **(>115 000)** occurred.

- Though **Sunday** is the least day with interactions **(5602)** but the data shows that Monday is the actual day the least amount of customers **(1302)** visit the website
#
**Products**

- Most Visited Product:
    - **Canon EOS R5 Camera**

- Most Checked out Product:
    - **Canon EOS R5 Camera**

- Least Checked out Product: 
    - **Nintendo Switch**

- Most Combined Product: 
    - **Sony PlayStation 5 and Fitbit Charge 4**


- Max Day of Transaction: **12**

- Min Day of Transaction: **1**

#

**Checkouts**
- Customers that checked out: **2998**

- Most Checked out Success, Country: **Korea** (0.83%)

- Most removed from cart Product: **Fitbit Charge 4 (2,122)**

#

**Revenue**
- Total Revenue: **$22,760,347.19**

- Most Revenue Product/Purchase(quantity): **Canon EOS R5 Camera** (2,231)

- Most Revenue Country: **Singapore** ($252,274.67)

- Least Revenue Country: **Slovenia** ($180.00) 


#
#### Sony PlayStation 5 and Fitbit Charge 4 have the highest correlation when it comes customers choice of complementary products


# 
**Suggestions** 
- sending of reminders to remind customers of products in their carts so as to checkout the products
- Creating of discount/vouchers which will help them to complete transactions should be introduced, Customers from Continents and Countries that take less time should be able to improve their service e.g. speeding up support in case there is a required service from the support department can help keep these customers in making purchase in little timescale

- NGN currency failed the most in all checkout transaction, Improving the payment platform can help retain customers who do not have another means of payment

- Customers from Korea have the highest rate of successful order due to the number of **Canon EOS 56** bought but are ranked second in top list high revenue generating countries, while Singapore with the highest generating Revenue **($505,450)** are not in the list of the Top 10 countries with successful checkout.

- The most purchased product in Korea is Samsung 55-Inch 4K Smart TV (40 pieces) and they purchased the most purchased product, Canon EOS R5 Camera (18 pieces) while the most purchased product in Singapore is Samsung Galaxy S21 (34 pieces) and Canon EOS R5 Camera (28 pieces)


