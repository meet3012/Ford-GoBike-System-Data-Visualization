﻿# Project Table of Contents : 

* Introduction of the topic and dataset
* Dataset Investigation and preliminary wrangling
* Further Data Wrangling
* Univariate Exploration and Analysis
* Bivariate Exploration and Analysis
* Multivariate Exploration and Analysis
* Conclusions and answers

# Why this project?

Data visualization is an important skill that is used in many parts of the data analysis process. 
Exploratory data visualization generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. 
This understanding will help you approach any statistical analyses and will help you build conclusions and findings. 
This process might also illuminate additional data cleaning tasks to be performed. 
Explanatory data visualization techniques are used after generating your findings, and are used to help communicate your results to others. 
Understanding design considerations will make sure that your message is clear and effective. 
In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

# What will I learn?

After completing this project, I will be able to:

Supplement statistics with visualizations to build understanding of data.
Choose appropriate plots, limits, transformations, and aesthetics to explore a dataset, allowing you to understand distributions of variables and relationships between features.
Use design principles to create effective visualizations for communicating findings to an audience.


### Data source :

Ford GoBike System Data : https://www.fordgobike.com/system-data
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area .

### Features :

The Features included in the Data are as follows :

- Member Year of Birth
- Member Gender
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Trip Duration(in seconds)
- Bike ID
- Start Time and Date
- End Time and Date
- Start Station ID
- End Station ID
- Start Station Name
- End Station Name
- End Station Latitude
- End Station Longitude
- Start Station Latitude
- Start Station Longitude

### Questions to be answered: 

1. What is the average duration of trips?
2. Does weather(with regard to months or seasons) impact the trip duration?
3. What is the impact or dependency of the above insights on whether a user is a subscriber or a customer?

### Summary of findings :

Since the trip duration has a close relationship with bike share company's revenue, I tried to find out what are the key factors affecting trip duration. 
It turns out that Weather does not have a big effect on the trip duration but user type does have an impact on trip duration. 
According the analysis, I found subscribers tend to rent the bikes for longer trips ( generally above 300 minutes ). 
One possible way to increase revenue is to attract more potential customers and convert more exiting customers to subscribers.  
