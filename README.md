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
#### Peak Usage Days Across Member Types
An initial differentiator observed during the analysis reveals distinct usage patterns between members with annual memberships and casual riders. Specifically, members with annual memberships exhibit heightened application utilization on Tuesdays, Wednesdays, and Thursdays. Conversely, casual riders demonstrate a pronounced preference for utilizing the application during the weekends, specifically on Fridays, Saturdays, and Sundays. This nuanced disparity in usage trends provides valuable insights into the distinct behavioral patterns of these user segments, facilitating targeted strategic decisions for maximizing engagement and conversion.
![visualization_of_days_of_highest_use_by_member_type](/images/days_of_highest_use_by_member_type.jpg)

#### Peak Usage Months Across Member Types
A noteworthy finding in the analysis indicates a consistent trend among both membership types, wherein increased application utilization is observed during the months of July, August, and September. This shared peak in usage signifies a seasonal pattern transcending membership distinctions. Understanding this collective surge in application engagement during these summer months holds strategic significance for planning and implementing targeted initiatives aimed at both annual members and casual riders
![visualization_of_months_of_highest_use_by_member_type](/images/months_of_highest_use_by_member_type.jpg)

#### Top 5 Stations Preferred Among Casual Riders
![visualization_of_top_5_stations_preferred_by_casual_riders](/images/top_5_stations_preferred_by_casual_riders.jpg)

#### Top 5 Stations Preferred Among Annual Members
![visualization_of_top_5_stations_preferred_by_annual_members](/images/top_5_stations_preferred_by_annual_members.jpg)

## Conclusion
In the analytical endeavor to maximize annual memberships and effectively convert casual riders into permanent members, several key insights stand out. The foremost is the crucial contribution of annual members to the company's revenue, underscoring the strategic importance of this membership category.

A distinctive aspect lies in the clear disparity in usage patterns between annual members and casual riders. While the former exhibit higher engagement on weekdays, particularly from Tuesday to Thursday, the latter show a marked preference for weekend usage, specifically on Fridays, Saturdays, and Sundays. This variation in usage habits presents significant strategic opportunities for maximizing engagement and facilitating effective conversion.

Another noteworthy finding is the consistent upward trend in application utilization during the summer months of July, August, and September. This seasonal peak transcends membership differences and suggests the need for specific seasonal approaches to optimize engagement strategies for both groups.

The identification of the top five preferred stations for each user type provides valuable insights for strategically localizing marketing efforts. Casual riders favor locations such as Streeter Dr & Grand Ave, DuSable Lake Shore Dr & Monroe St, Michigan Ave & Oak St, Millennium Park, and DuSable Lake Shore Dr & North Blvd. Meanwhile, annual members prefer stations such as Clinton St & Washington Blvd, Kingsbury St & Kinzie St, Clark St & Elm St, Clinton St & Madison St, and Wells St & Concord Ln.

In summary, the analysis supports a weekend-focused marketing strategy during the summer months, with an emphasis on the identified preferred stations. This approach, backed by robust analytical conclusions, lays the groundwork for an effective, results-oriented marketing strategy.
