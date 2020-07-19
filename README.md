# Starbucks-EDA-Capstone-Project
Answering Business  questions of customer behaviour based on starbucks app data 

## Introduction
For the Capstone Project, I chose the “Optimizing App Offers With Starbucks” project, which basically trying to solve the problem on 
how to send the offer to the right customers.

## Datasets
You can download the dataset uploaded in the data folder.
Data files: Compressed Data.zip file contains 3 files:
portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed

## Business Questions:
I have carried out data abalysis to answer foloowing questions:
1. How much we loss because of the offers?
2. What kind of customers that often completed the offer without viewing it?
3. How is the income distributes between customers type?

## Data Analysis and Cleaning: 
Starbucks_Capstone_notebook.ipynb notebook contails all the data analysis and data cleaning.



## Dependencies: Python 3.6, pandas, matplotlib, seaborn

## Conclusion:
1. With the unplanned offer, we can "loss" up to USD 49,032 of revenue in a month or USD 588,384 of revenue in a year. So the target marketing of our promo is 
very important and plays a huge roll.
2. Female customers tend to spend more than Male customers, with the average spending per transaction is USD 16,3 compared to USD 10,4 
respectively. Female customers also have tendency to complete the offer even without viewing it first, so we might want to be more careful in sending the offer to them.
3. Customers who complete the offer without viewing the offer first have the higher average income, especially in discount offer where 
those who complete the offer without viewing it and those who viewed it have average income USD 71,060 and USD 67,642 respectively.

## Future Improvements:
We need to be more careful in sending the offer, especially the BOGO offer where it contributes USD 31,230 loss in this experiment. One thing we can do is to 
stop giving the BOGO offer to the customers with the average purchase > 2 cups per transaction, because without giving them the offer they tend 
to purchase > 2 cups anyway so the BOGO offer seems not to important for them.Send less offer to the Female customers, especially discount offer. 
We can see from the data that the average spending of Female customers is USD 16,3. So we might want to increase the minimum spending for the offer we send to them, 
because it won't make sense if we send them the offer with "difficulty" of USD 10, they would accomplish it anyway. So increase the minimum purchase to USD 20 or 
USD 25 would be better.We might want to customize the "difficulty" based on the level of income for each customer, so that people with the higher income have the 
higher "difficulty" as well.



