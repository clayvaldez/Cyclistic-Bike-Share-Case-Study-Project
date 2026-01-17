# Cyclistic-Bike-Share-Case-Study-Project
![Case Study 1_How does a bike-share navigate speedy success (1)](https://github.com/user-attachments/assets/1374e219-d65a-4129-b836-5e372fdf61f3)

## Table of Contents
* About the Company
* The Problem
* The Questions
* Business Task
* Data Source
* Project Roadmap
* Data Findings
* Conclusion
* Recommendations

## About The Company
Cyclistic is a successful bike-share company that launched in 2016. They have grown to over five thousand bicycles and over six hundred stations across Chicago.

## Problem
How to convert casual riders into annual members. 
The stakeholders need a better understanding of how annual members and casual riders differ. Also, how digital media could affect their marketing tactics. 
### Questions
There are three main questions that the company is seeking to answer to help with the marketing strategy. 
1) How do annual members and casual riders use Cyclistic bikers differently?
2) Why would casual riders buy Cyclistic annual memberships?
3) How can Cyclistic use digital media to influence casual riders to become members?
## Business Task
Design a marketing strategy aimed to convert casual riders into annual members. 

## Data Source
I will be using the historical data from 2020 Q1 that will cover from January to March of 2020. 
I will be using excel to do a base cleaning and will be using BigQuery(SQL) for all the data exploration.
### Data Schema
<img width="464" height="536" alt="cyclistic_data_schema" src="https://github.com/user-attachments/assets/b79fd246-ea58-4c57-b528-46c2a7c94f98" />

## Project Roadmap
* Remove duplicates/Remove null cells in excel.
* Create a ride_length and day_of_week column in excel to help find out how long a ride was and what day was it.
* Move everything to BigQuery SQL for more data exploration.
* Create data visualization/charts to help read through the data.
* Create recommendations to help answer the questions/problem and grow the business.

## Data Findings
During the data discovery phase, several key insights were identified that help address the company's three primary business questions:
* Membership Composition
  * Annual Members account for 89% of total riders, while Casual Riders represent 11%.
* Usage by Day of Week
  * Annual Members primarily use Cyclistic bikes on weekdays Mon-Fri, with usage dropping significatly on weekends. In contrast, Casual Riders show peak usage on weekends and lower activity during the week.
* Ride Duration
  * Annual Members have a substantially shorter average ride lenght with 11 minutes compared to Causual Riders with 43 minutes. Indicating different trip purposes.
* Seasonal Trends
  * Annual Member ridership has steadily decreased from January to March, while Casual Riders have increased over the same period.
* Station Preferences
  * The most frequently used start and end stations differ between Annual Members and Casual Riders, suggesting distinct travel patterns and destinations.

## Conclusion
The data shows a distinct usage patterns between Annual Members and Casual riders. Annual Members primarily use Cyclistic on weekdays, with an average ride duration of 11 minutes, indicating that their trips are largely point to point in nature. This pattern is consistent with commuting for transportation purposes.
Casual Riders, by contrast, exhibit higher usage on weekends and have a substantially longer average ride duration of 43 minutes. This suggests that casual riders are more likely engaging in recreational or fitness oriented trips rather than transportation focused. 
Seasonal trends further differentiate the two groups. From January to March, Annual Member usage declines while Casual Riders usage increases. This inverse relationship suggests that as weather conditions improve, Annual Members may substitute biking with other short distance transportation options, such as walking.
Conversely, the increase in casual riders during warmer months indicates that favorable weather conditions are a key driver for recreational and fitness related bike usage. 


## Recommendations
Based on the data insights the following recommendations aim to drive conversion from Casual Riders to Annual Members.
* Target Casual Riders During Peak Usage
  * Marketing campaigns should be concentrated on weekends and warmer motnths, using in-app notifications or station-based messaging when casual riders are most engage.
  * Emphasize on fitness and lifestyle as is appears Casual Riders are using Cyclistic for more recreation and fitness purposes.
  * Highlighting goal tracking and health benefits. 
* Highlight Cost Savings for Long-Duration Riders and Loyalty Incentives
  * Offer incentives such as ride credits, free unlocks, or loyalty points after a certain number of rider or distance is reach.
* Seasonal or Trail Memberships
  * Offer seasonal membership or one month trails that allows casual riders to expericence member benefits without a full annual commitment.
  





