![alt text](https://d2guulkeunn7d8.cloudfront.net/assets/Instacart_Share_Banner_3-ac2a938e3883925100a5439a87191d6f.jpg)

# Insta-hour: Identifying Peak Instacart Order Times

## Blog Version


# Summary
My name is Christian Rios-Chambi and I am a Data Analyst working for the grocery delivery and pick-up service Instacart. My project will be on identifying peak Instacart order times. It will be an in-depth analysis of the relationship between time and Instacart order. 

## How Instacart works

You’re busy, so every minute counts. Let us connect you with Shoppers in your area to shop and deliver items from your favorite stores in as fast as an hour. It’s just that easy. Instacart partners with the most popular national and regional retailers such as Albertsons, ALDI, Costco, CVS, Kroger, Loblaw, Publix, Sam's Club, Sprouts, and Wegmans, among others. The Instacart marketplace offers more than 300 retailers and trusted local grocers that customers love. Shop from your favorite national and regional grocers with your computer or mobile device. Schedule delivery for as fast as an hour, or for later in the day or week to fit your schedule. Delivery windows start as early as 9 am and run as late as midnight. Check local store hours. Delivery hours are subject to store operating hours, which includes holidays. The Instacart platform also offers a pickup option. You simply shop on Instacart’s website or app, select a pick up time, then pick up your groceries at the store. Available at select locations.

## The Dataset 

Instacart is excited to announce our first public dataset release, “The Instacart Online Grocery Shopping Dataset 2017”. This anonymized dataset contains a sample of over 3 million grocery orders from more than 200,000 Instacart users.
For each user, we provide between 4 and 100 of their orders, with the sequence of products purchased in each order. We also provide the week and hour of the day the order was placed and a relative measure of time between orders.

## **Main Points**
- **What are the most popular times for ordering on Instacart?**
- **Is there a difference in the number of orders during AM and PM hours?**
- **What are the ordering times of some popular products?**


# Project Steps & Further Questions:

## Data Cleaning:

- Remove duplicates or records with missing or mismatched values.
- Removing unnecessary columns. 
- Replacing certain null values with appropriate zero values.
- Created new columns for better analysis.
- Creating functions to help label features.

## Exploratory Data Analysis (EDA):

- Creating visualizations
- Variable identification
- Outlier treatment
- Univariate analysis
- Bi-variate analysis

## What are the most popular times for ordering on Instacart?:
- Popular ordering times for orders were between 9 am - 4 pm. The most popular time was 10 am.
- Most popular days for ordering were Sunday and Monday.
- Sunday's at 2 pm and Monday's at 10 am. 

## Is there a difference in the number of orders during AM and PM hours?:
- Grouped all orders as either AM or PM orders.
- Developed my null hypothesis. Group AM and Group PM have the same average orders placed (per user).
- Ran a Welch's t-test. Decision: Reject the null hypothesis.

## What are the ordering times of some popular products?:
- The highest peaks for AM orders are from 10 am to 11 am. The most popular products are yogurt, milk, and nuts/dried fruits.
- The highest peaks for PM orders are from 4 pm to 5 pm. The most popular products are ice cream, frozen meals, and frozen pizza. 


## Recommendations and Next Steps:
- We can use this information to help triangulate an advertisement campaign for a specific product (during a specific hour of the day).
- We can improve customer outreach by offering specific coupons for products often purchased at a specific time.
- I would like to analyze specific products and/or coupon distribution rates.


# Contact Information 
- **Name:** Christian Rios-Chambi
- **Email:** crioschambi@gmail.com
- **LinkedIn:** linkedin.com/in/christian-rios-chambi/
- **Github:** github.com/criosch1
- **Website:** crioschambi.com
