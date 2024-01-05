# How does a bike share achieve rapid success?

## Overview
This case study revolves around Cyclistic, a fictional bike-share company, whose goal is to maximize annual memberships, a key factor for the company's future success. The marketing director believes in converting casual riders into annual members and has an interest in understanding the differences in how annual members and casual riders use Cyclistic bikes. The analysis involves exploring historical bike trip data to uncover insights that will inform a new marketing strategy. The comprehensive data analysis process involves querying and processing data using Google BigQuery, ensuring privacy and security throughout the process.

## Objectives
* Maximize the number of annual memberships
* Understand casual riders and annual members use Cyclistic differently.
* Convert casual riders into annual members

## Analysis
### Data Source
I curated the dataset for this analysis by transforming Excel tables into a structured format. The process involved meticulous data cleaning, where I removed null values to enhance data integrity. Additionally, I created multiple tables that serve as valuable assets in validating and reinforcing the findings of my analysis.
For access to the data that I compiled and cleaned, kindly refer to [this link](https://console.cloud.google.com/bigquery?project=unified-gift-318816&ws=!1m4!1m3!3m2!1sunified-gift-318816!2scyclistic_data_2023) which is publicly available on Google BigQuery.

### Financial Performance Analysis: Revenue Dissection by Membership Type
In alignment with the primary objective of optimizing annual memberships for enhanced profitability, a comprehensive analysis was undertaken to ascertain the financial returns associated with distinct ride types. The results unequivocally underscored that riders with annual memberships significantly contribute to the company's revenue. This strategic insight emphasizes the pivotal role of annual memberships in augmenting the financial viability of the organization.
![visualization_of_annual_profits](/images/annual_profits_by_ride_category.jpg)

### Main Differences Between Casual Riders And Annual Members
#### Day of Highest Usage by Member Type
![visualization_of_days_of_highest_use_by_member_type](/images/days_of_highest_use_by_member_type.jpg)
#### Month of Highest Usage by Member Type
![visualization_of_months_of_highest_use_by_member_type](/images/months_of_highest_use_by_member_type.jpg)
#### Top 5 Stations Preferred By Casual Riders
![visualization_of_top_5_stations_preferred_by_casual_riders](/images/top_5_stations_preferred_by_casual_riders.jpg)
#### Top 5 Stations Preferred By Annual Members
![visualization_of_top_5_stations_preferred_by_annual_members](/images/top_5_stations_preferred_by_annual_members.jpg)
## Conclusion

