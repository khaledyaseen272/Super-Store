# Super Store Sales)
## by (Khaled Yaseen)
## Project in Tableau: https://public.tableau.com/app/profile/khaled.yaseen/viz/SuperStore_16449743620740/GenralDashboard

## Datasets

> I analyzed and explored Superstore Dataset which contains about 17000 observations and 26 variables From Jan 2010 to Dec 2013 for 3 departments: furniture, technolgy, and office suppliers throughout 50 Countries and 1523 cities around the world in total orders quantities about 440,000 orders with total profit about 15,000,000 million dollars. I used this dataset for practice. In this project. I gathered the dataset from the CSV file to the jupyter Notebook then I did the wrangling process to handle the limitations and started to explore the data programmatically with Python. After cleaning the data to be ready for the explanatory process, I exported the cleaned data to CSV File then dropped it into Tableau. In the notebook, I checked the data cleaning and consistency then I did the exploratory and Explanatory Processes through Tableau.



## Almost, The datasets were redy and I did small cleaning operations. After cleaning the data i started to pose questions and analyze data Throght Tableau, visualization and dashboards in tableau via this link: https://public.tableau.com/app/profile/khaled.yaseen/viz/SuperStore_16449743620740/GenralDashboard


### Here are the questions and the findings after answering these questions:

##### Q1: What is the most Country in total Profit?
- USA is the highest country made the largest total profit for the super store with about 4.1 million dollars then China with about 1.8 million dollars.

##### Q2: USA is the largest Country in Total orders in different Cities, Is USA Is the largest Country in Avg profit Also?
- No, USA is not the largest, USA has Avg profit 437 dollars per order for 9426 Orders, The largest in Avg is Moroco with 2383 dollars per order for only 22 orders then 2284 dollars per order for only 45 orders then norway with 2162 dollars per order for only 11 orders. From the map the middle east and the eauropean countries  have high avg profit values, Also China has 1429 Avg profit per order for 1257 orders and that is a high order Count so I think the superstore should make a true interest for other countries like the interest for USA! . But there is an important queation for the shipping cost for these countries!

##### Q3: What is the Avg shipping cost for countries and is there a gap difference in the cost from USA?
- The Avg shipping cost for USA 12.81 dollars per order, For Moroco 12.86 dollars!, For iraq 15.8, For Norway 24.09, For china 13.28, For ukraine 11.25 dollars which has Avg profit 2027 dollars per orders for only 24 orders, For algeria only 8.17 dollars which has Avg profit 1379 dollars per order for only 18 orders. so, I think the superstoere should to target other markets beside the united states!.

##### Q4: What are the cities with the highest profit?
- The first one is Buenos Aires from Argentia with total profit 560,000 dollars then Guangzhou From China with 535,000 dollars, Cairo comes in the 5th place with 366,000 dollars!. the first city comes from USA is Los Anglos in the 11th place with total profit 286,000 dollars. And that is another evidence that the superstore should expand to another marketplaces.

##### Q5: Which item has the largest in the profit and in which department?
- The item of global troy of excutive leather low back tilter in the furniture department has the most totaal total profit of 277,000 dollars and its orders count are 34 orders with Avg product base margin is 0.6. The department of furniture has the biggest share in the highest items in profit!

##### Q6: What is the largest category and department in profit?
- The telephones and communications in the technology department has the largest profit with 2,436,000 dollars and its order counts are 1766 orders with avg product base margin 0.58.

##### Q7: What are the order count perctiles for departments?
- The furniture has 39.61%, the technolgy has 38.68%, and the office suppliers has 21.71%.

##### Q8: What is the total profit for each departmesnt?
- The furniture has 5,870,000 dollars, the technolgy has 5,731,000 dollars, and the office suppliers has 3,217,000.

##### Q9: What is the Avg product margin for each department?
- The furniture has 0.5837, the technolgy has 0.5515, and the office suppliers has 0.4468.

##### 10: What is the Avg Unit Price for each department?
- The technolgy is the largest with 181.4 dollars then the furniture with 121.5 dollars then the office suppliers with 36.1 doolars per order.

##### 11: What is the category is the largest in the Avg Unit Price?
- It is copiers and fax from the technolgy department with 746 dollars then technolgy&oofice machines also from the technolgy department with 565.7 dollars per order.

##### 12: When did the largest profit happen and in each category? In that perid, Is this category has the largest number in order count?
- The largest profit happened in Nov 2012 with total profit 164,000 dollars and only 20 orders in tables category but in this month paper has the largest number in order counts with 54 orders and 6874 dollars!.The largest order count happened in Oct 2013 with 95 orders and only total profit 12,882 dollars! but in this month telephones and communication has the largest profits 82,299 and only 38 orders!. In general paper has the largest order counts over years, the largest profit varies between furniture and technology categories over years, and almost the largest profit happens in Nov from every year!. Wow, This led me to check is there are discounts in december?

##### 13: How the discounts were over year and there were special discounts in november?
- Another surprise for me, Tables has largest discounts over years with a gab from other categories!. But i didn't found any special discounts in november!. (See Q15)

##### 14: For Departments, What was the time anlaysis?
- Like the output from Categories, Office suppliers has the largest number in order counts, the most happened in Oct 2013 with 299 orders. The furniture and technology have the largest number in profit and the largest profit happened for furniture in Nov 2012 With total 365,000 dollars.

##### 15: What are the average discount profit and order counts for different discounts?
- Another insight supporst the insight from Q13, Only tables and furnishings have discounts over than 10% . All other categories thier discounts less than 10%.

##### 16: What are the largest category in Avg Shipping cost per orders?
- As expexted, Furniture categories are the largest With Avg 30.89 dollars for order, Tables is the highest in Avg Shipping cost with 57,36 dollars. Technology and office supplies almost the same in avg Shipping cost

##### 17: What are customer segment percentiles?
- Corporate with 36.8% of order counts, Home Office with 24.1%, Small business with 19.74%, then Consumer with 19.36%.

##### Q18: What is the total profit from each custome segment?
- Superstore got from Corporate with 5,453,000 dollars, From Home Office customers 3,572,000 dollars, From Small business 2,925 dollars, From Consumer 2,869,000 dollars. 
##### 19: When did the largest profit happen from customers and from which customer? In that perid, Is this customer has the largest number in order count?
- The Largest profit came from Corporate in Nov 2012 with total profit 274,000 dollars more little than small business in the same month which has 267,000 dollars, And Yes Corporate has the largest order counts in the same month with 197 orders. In general corporate has the largest profit and order counts over years.

##### 20: Who is the customer with the largest profit ?
- It is Joan Oakley Shaafer corporate with total profit 107,000 dollars and it has 26 orders. 

##### 21: What are the average delivery periods for different order priorities ?
- Low Priority takes more than 4 days to deliver the orders. Other priorities took form 1 to 2 days.

##### 22: What are the percentiles for different order priorities ?
- Almost the same range from 19 to 21% for the 4 priorities.

##### 23: What are the profit percentiles for different order priorities ?
- It ranges from 17 to 23.5% for the 4 priorities.

##### 24: What are the containers percentiles ?
- Small Box is the largest with more than 50% in compared to the other containers.

##### 25: What are the value and the average unite price for goods inside containers ?
- large box contain the most valuable goods with average unite price 347.5 dollars.

##### 26: What are the ship mode percentiles ?
- Regular air is the largest with almost 75%.

##### 27: What are the  avg shipping cost for ship modes ?
- Delivery Truck is the largest with 45.39 Dollars for Avg cost.

##### 28: What do the  ship mode and department  occur most?
- It is small box in regular air happened almost 750 times.

##### 29: What are the correlations between order quantity, shipping cost and profit?
- They are postive correlations.

##### 30: What Is the most popular Unit Price range?
- It is from 0 to 1000 dollars.

##### 30: What Is the most popular Product base margin range?
- It is from 0.35 to 0.65 and the most profit occurres on products base margin from 0.55 to 0.6.

##### 31: What Is the relation between product margins and Avg discount?
- I finish the report with the last insightful finding, the product with high margins above 0.6 release high discounts to encourage buying especially in the furniture department. 

