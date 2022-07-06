#  Goggle Data Analytics Captsone Project
This is the repository for my goggle data analytics capstone project.

# Cyclistic-Analysis
by Fathatulkhayr

# About the Dataset
Cyclistic is a bike sharing company launched in 2016. It started with 5,824 bicycles which geotracked and locked into a network of 692 stations across chicago. The bike can be unlocked and locked from one station and return to any other station in the system anytime. The Datasets are available https://divvy-tripdata.s3.amazonaws.com/index.html

There are four different datasets(spread across 12 months in four quarters) which have been combined into a single datasets called the all_trips. The dataset contains 15 columns and 3258796 rows. The columns names are:

ride_id: The unique identifier for each rides
start_time: The datetime which each ride is started
end_time: The datetime which each ride ends
bikeid: The unique identifer for every bikespreadinning station
from_station_name: The name of every station where each rides are started
to_station_id: The unique identifer for ending station
to_station_name: The name of every station where each rides are ended
usertype: The type of users for each trip
gender: The type of genders for each trip
birthyear: The birth year for every riders

# Data Processing
The tool used for the analysis is R. 
The packages used for this analysis are tidyverse, janitor, Tmisc, and lubridate.

