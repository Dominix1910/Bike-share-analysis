# Bike-share-analysis
This is a portfolio project for Google Analytics capstone. I will be analysing a fictional company “Cyclistic” where I will try to answer a few questions asked by stakeholders.


## Dominik Scibor

 How does a bike-share navigate speedy success?
# OVERVIEW

 This is a portfolio project for Google Analytics capstone. I will be analysing a fictional company “Cyclistic” where I will try to answer a few questions asked by stakeholders.
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
   


# GOALS
1.Maximizing the number of annual memberships

2.Understand how casual riders and annual members use Cyclistic bikes differently.


# Prepare the data	

Data was downloaded from “https://divvy-tripdata.s3.amazonaws.com/index.html”
And stored in: D:\Cyclist Data as Cyclistic Data.xlsx

I will be working with data for January 2024 (202401-divvy-tripdata.csv)

The dataset contains over 100k rows and 13 columns. Each row represents individual journey records and columns detailing it. We have Ride_id,  ride type, date of start and finish, name of starting and ending station , coordinates for each station and also information about raider type (casual or member)

# Data cleaning

The dataset contains a lot of information but at the same time a lot of missing information.
To make data valuable and able to work with it, I had to remove any missing data.
I used Microsoft Excel to clean and manipulate data.
Here is an example of missing data:
<img width="1894" height="679" alt="image" src="https://github.com/user-attachments/assets/30333c24-5691-494c-bd51-3b980e4fd147" />


Most of the missing data comes from bad data. In this case coordinates are wrong and this lead to missing end station name and station_id.
Using Power Query editor I was able to remove any row with empty cells, this way I had only data that was correctly stored.
I added columns to calculate the length of a ride and day of a week.
For better visibility I deleted columns that are not important for further analysis like name of a station or coordinates
<img width="1173" height="708" alt="image" src="https://github.com/user-attachments/assets/36765d40-e18a-4bdd-813d-aaf81b31a816" />


# Further analysis
Take a look at some basic information:
 What is a distribution of riders between casual and members?
<img width="575" height="319" alt="image" src="https://github.com/user-attachments/assets/7edce017-3636-4c01-b040-0a284dab5152" />

<img width="244" height="81" alt="image" src="https://github.com/user-attachments/assets/568d3d7e-9f93-4f29-addd-a233d6d405c2" />

 Here we can see that raiders with membership did most of the rides during January.

<img width="708" height="291" alt="image" src="https://github.com/user-attachments/assets/091c4677-c4d2-45b8-808b-a12d2e0e0e4d" />

If we look at what riders prefer, classic bikes are a more preferable type than electric for both groups.

 Now take a look at how long riders use bikes:


<img width="320" height="61" alt="image" src="https://github.com/user-attachments/assets/4e43cbbf-60e5-4580-becf-567b72790b25" />


Here we can see that casual riders use bikes for longer journeys than members.

 Take a look at bikes usage distribution across whole week

<img width="839" height="335" alt="image" src="https://github.com/user-attachments/assets/71191544-4d7f-4cf5-9ed4-f0c77f5f9515" />

 What about each group?

<img width="830" height="335" alt="image" src="https://github.com/user-attachments/assets/5115fe1d-8d29-48eb-95eb-d105da08196e" />

<img width="833" height="335" alt="image" src="https://github.com/user-attachments/assets/65f449d7-ca7a-4d70-bacc-336c6244d9c7" />

 From these graphs we can see that Tuesday is the most popular day for both groups and usage pattern is the same for both groups.


# Summary

 Let’s back to our questions and try to answer them:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?
 

 From my analysis we can see that both groups prefer classic bikes over electronic, also the most popular day is Tuesday and Casual bikers on average use bikes for longer journeys.
 Casual riders could benefit from cheaper rides with membership, since they are used for more further rides.
 Cyclistic can use digital media to promote membership that can save money for longer journeys at every station or mobile phone app that is required to unlock bikes at the station.
 A good option would be a summary after a ride and how much cheaper it would be, if the user had a membership.
