# Bikesharing Trip Analysis
October 6, 2022

This is personal portfolio project by Thamilini P.

This project involves a fictional bikesharing company called Cyclistic. This company offers different pricings plans that targets two groups: casual riders and annual members. Financial Analysts have determined that annual memberships bring in higher profits for the company. Therefore, the marketing team aims to persuade casual riders into becoming members. This project will analyze the differences in how casual riders and members use cyclistic bikes.

## Purpose/Objective
Recommend strategies to convert casual riders into annual members by analyzing differences in bike usage.

## Datasets License

Since Cyclistic is a fictional company, data was collected from Lyft Bikes and Scooters, LLC (“Bikeshare”). Bikeshare manages Chicago City's Divvy Bikesharing service. All Datasets was made available by the Bikeshare under this [License](https://ride.divvybikes.com/data-license-agreement). 

The datasets includes trip data from September 2021 to August 2022 (i.e. 12 months). Datasets were downloaded from [Link](https://divvy-tripdata.s3.amazonaws.com/index.html). Each csv file contained one month of trip data, therefore 12 csv files were downloaded in total. 

## Methodology

Since each of the 12 csv files contained one month of trip data, I had twelve separate data tables. Each data table has the same column names and data types. 

Since each data table contained the same columns, I used SQL UNIONS (in Google BigQuery) to combine all the rows as one data table. Below is the SQL Query:

![SQL Union Query](https://github.com/Thamilini/Bikesharing-Trip-Analysis/blob/main/SQL_Union_QUERY.png)

The datasets were cleaned, processed and transformed using R. The following libraries were used:
* tidyverse
* skimr
* janitor
* lubridate
* ggplot2

A dashboard and its visualizations were created using Tableau. 

Below is an image that outlines the phases used in this process. Image Source: [Google Data Analytics Professional Certificate Program](https://www.coursera.org/professional-certificates/google-data-analytics)
![Process](Process.jpg)
