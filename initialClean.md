#This file will be used to clean our data 


- age_cat has 547 missing values, it is 5.75% of the data
- bmi has 308 missing values, it is 3.24% of the data
- bmi_cat has 578 missing values, it is 6.08% of the data
- weight_kg has 252 missing values, it is 2.65% of the data
- race has 189 missing values, it is 1.99% of the data
- sex has 368 missing values, it is 3.87% of the data
- alcohol_frequency has 215 missing values, it is 2.26% of the data

Rows containing missing value(s) are about **12%** of the total data.

On the other hand, rows only have invalid BMI/BMI_cat are **6%** of the total data. -- must drop as the tasks are to predict those values

One of the ideal methods is to **drop** any row who has one or more missing values. 
Also because records which have at least one missing value, have other columns with weird values that cannot be employed.

The relationship between the above cols to be discussed. (to determine whether or not the age/race/sex has significant impact on BMI)


Click here to download [clean data](https://drive.google.com/file/d/1IAd1WUgJvsPLNOfyp78PLqVHv8JqeTmp/view?usp=sharing), 
with all missing values dropped. Noted that this csv file is tab delimited other than comma.

-- *Ashley*

