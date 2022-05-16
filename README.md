# Bike Purchace Data Analysis and Visualisation

## Introduction
The aim of the sales data analysis is to uncover invaluable information that can help us decide whether to adjust prices or increase or decrease supply of products on the basis of various factors.

If a particular product’s sales are lagging, consider the targeted audience distance and age bracket. You may need to reposition products or target a specific customer demographic.

If you do a sales analysis and look at the products that are not selling, that doesn’t mean that you get rid of them. It may also tell us to correct something, such as ineffective marketing tactics, to get the sales you need.

## Project 
In this repository Data Analysis and Visualisation is done on the bike purchase customers' background information in different demographics. 

## Data

The data for this assignment can be viewed from the link given below:

   - [Bike Purchase dataset](https://github.com/kracdek/Bike-Sales-Excel-Project/blob/main/Excel%20Project%20Dataset.xlsx)
   
The file contains the data frame with all the customer background information For each customer the table contains their income, education and occupation,commute distance and whether they purchaced a bike or not differentiated on the basis of country, region, gender and age. Here are the first few rows:

| ID    | Marital Status | Gender | Income     | Children | Education       | Occupation     | Home Owner | Cars | Commute Distance | Region  | Age | Purchased Bike |
|-------|----------------|--------|------------|----------|-----------------|----------------|------------|------|------------------|---------|-----|----------------|
| 12496 | M              | F      | $40,000.00 | 1        | Bachelors       | Skilled Manual | Yes        | 0    | 0-1 Miles        | Europe  | 42  | No             |
| 24107 | M              | M      | $30,000.00 | 3        | Partial College | Clerical       | Yes        | 1    | 0-1 Miles        | Europe  | 43  | No             |
| 14177 | M              | M      | $80,000.00 | 5        | Partial College | Professional   | No         | 2    | 2-5 Miles        | Europe  | 60  | No             |
| 24381 | S              | M      | $70,000.00 | 0        | Bachelors       | Professional   | Yes        | 1    | 5-10 Miles       | Pacific | 41  | Yes            |



Original Data is modified by 
- adding Age Bracket colomn using the function: `=IF(AGE,"Old",IF(AGE,"Middle Age",IF(AGE,"Adolescent","Invalid")))`
- formating the Income colomn to Currency in $
- in changing the Marital Status colomn format from `M -> Married` `S -> Single` 
- in the Gender column `M -> Male` `F -> Female`  
- and in Commute Distance colomn `10+ miles -> More than 10 miles`   for better visualisation. 

