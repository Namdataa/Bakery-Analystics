# Bakery Analystics
![image](https://github.com/user-attachments/assets/1db3bcaa-ae27-4bc0-a212-65b3d77f1357)

## Introduction

A is the owner of a bakery.
A's store has about 15 different items.
Customers who come to buy goods are recorded with their phone numbers and the types of goods purchased in the data system.
The store has been in operation for 1 year, but A has only tracked monthly sales.
Currently, A needs to manage the store with available data, and at the same time wants to increase sales.
## Business Problem

Based on the data from A's store, help A have an overview of the store's operations and suggest ways to increase sales based on the data.

![image](https://github.com/user-attachments/assets/7aa45436-4a74-49be-a526-3fc847749226)

## Dataset
https://docs.google.com/spreadsheets/d/1W8YCvhcn3xP8tNC7ULB7ruSjKsEmv3uRyuIFLJHKZ7s/edit?usp=sharing
![image](https://github.com/user-attachments/assets/b74cc551-5ec6-4ad5-a1f0-ca7199d9a5d6)

## Technology Used
- **Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - requests
  - datetime
  - csv
## Approach

The following approach was taken:
- **Clean Data**
  - Load data and clean data with null values
  - Transform necessary columns and remove redundant columns
  - Calculate some additional columns for the problem objective
                                                                                               
- **Exploratory Data Analysis**
  - Plot histograms of features to understand distributions
  - Calculate summary statistics of data
  - Conduct statistical analysis to find insights from data
  - Present comparison charts across time periods to gain insight into overall business performance

- **Preprocessing**
  - Reselect data that affects business results using correlation matrix
  - Determine model coefficients

- **Modeling**
  - Set the correct train and test index to help the model avoid overfitting
  - Apply multivariate linear regression to see the impact of independent variables on dependent variables.

- **Evaluation**
  - Review the results of comments on the dependence of the dependent variable on the independent variable
  - How much of the impact of the independent variable on the model can the model explain
  - Give the dependent function and comments

![image](https://github.com/user-attachments/assets/1b0fa80b-0cbd-4546-b156-09d75d39a7e9)
## Business insights
![image](https://github.com/user-attachments/assets/93de16a2-2ae6-4bc4-a562-897e7985eb24)

- **Revenue Overview**
  - The chart shows a clear trend of revenue growth
  - Revenue growth in the early and mid-year months is not strong
  - Starting from August to the last months of the year, revenue increases significantly, maybe this is the transition period from warm to cold weather, so people tend to snack and eat more fast food.
  - **Store Locations**
    - Throughout the year, the ranking of store locations by revenue remained unchanged.
    - Recommended Focus: Businesses should further develop the following locations: Vu Trong Phung, Dinh Tien Hoang, Tran Phu, Hung Vuong, and Ho Tung Mau.
    - Areas for Improvement: Businesses should consider improving the performance of these locations: Nguyen Trai, Le Loi, Quang Trung, Bui Thi Xuan, and Phan Dinh Phung.
  - **Best-Selling Products**
    -Over the year, the best-selling products remained the same, with only minor changes in ranking.
    - Recommended Products to Prioritize: Chocolate cake, ice cream cake, donut cake, salted egg sponge cake, and almond tile cake should be produced and displayed more prominently.
    - Low-Performing Products to Address: Mouse bread, sweet bread, and milk-butter bread require improvement. Additionally, cacao was relatively popular during the first seven months, but its popularity was later surpassed by brown rice cake. Both cacao and brown rice cake should be carefully considered for further enhancement. 
  - **Revenue by Day of the Week**
    - Low Revenue Days: The first and last days of the week typically see fewer purchases and lower revenue.
    - High Revenue Days: Mid-week days, especially working days for office workers and students, consistently generate higher revenue.
  - **Customer Age**
    - The majority of the company’s customers are aged between 25 to 60 years old, with most having stable jobs and many being married.
  - **Time Frame for Purchases**
    - The most popular time for customers to purchase products is between 10 AM and 2 PM, which surpasses other time frames.
  - **Buying Patterns by Month**
    - First Seven Months: Customers mainly make purchases during the first half of the month.
    - Remaining Months: Customers tend to buy products during the first 10 days and the last 10 days of the month.
# Bakery Dashboard
## Performance KPIs
![image](https://github.com/user-attachments/assets/1673247b-2e23-4c19-bcb2-6fec5d3a53d8)

## Revenue Overview
![image](https://github.com/user-attachments/assets/4075095e-c5c0-47d4-b0f1-29a02999e1ce)

**Link DB:** https://app.powerbi.com/reportEmbed?reportId=efddb24f-bd73-44ec-b538-91d73f22a7d4&autoAuth=true&ctid=5b98a1d4-abc3-42cd-896e-2e1b240dc662

**Note:** Viewers must use a Microsoft account ending in "due.udn.vn"
