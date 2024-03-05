# ADS-508-Final-Project

# ADS508-CATraffic

# Table of Contents:

# Data retreiving:

clone address:

# Project contributors:

Minsu Kim\
hjavadnia\
UE Wang https://github.com/UE-Wang

Company Name: Goldendrive, LLP
Company Industry: Navigation & Traffic
Company Size: 10 ~ 50

# Applicants:

Python (AWS Sagemaker)\
AWS (Sagemaker, Athena, S3)\
Word\
Powerpoint

# Abstract:

California, as the most populated state in the nation, is filled with heavy traffic highways. The currently available navigation applications can only provide ETA based on the real-time data associated with the regular highway lanes. This left the drivers who use HOV lanes with inaccurate ETAs. We at Goldendrive are to help develop an additional feature to a navigation application that aims to address this issue by calibrating ETAs for HOV and Express lanes. 


# Problem Statement:

“California was the state with the highest resident population in the United States in 2022, with 39.03 million people.” (Duffin, 2023) The huge population in California results in the biggest transportation demand. “In 2019, California had the most automobile registrations: almost 14.2 million such vehicles were registered in the most populous U.S. federal state. California also had the highest number of registered motor vehicles overall: more than 30 million registrations.” (Carlier, 2022) In order to better assist Californian drivers, our team is working to develop an app that more accurately depicts real-time traffic conditions, adding the HOV/Express lane traffic feature on top of the already existing traffic navigation app, which currently only predicts regular freeway traffic.

# Goals:

Building a model which can predict driving time in the navigation app when the HOV lane are used\
Identifying driving time using the HOV lane different times in a day\
Delivering the result to end users by the navigation app update deadline

# Non-Goals:

This project is focused on the HOV Lane traffic solely and will not predict driving time in general traffic and/or when using regular lanes\
The scope is to predict the driving time and will not suggest means to increase or decrease the time for the user. Based on the navigation app’s results, the user can make an informed decision on which route to take and on whether or not to use the HOV Lane\
It is not in the scope of this project to fix any issues with traffic.

# Data Sources:

Data will be loaded on AWS S3 Bucket and used with AWS Sagemaker.\
The data of interest includes three separate CSV files (HOV, Traffic Volume, Speed) that were obtained from Data.gov.\
The  Express Lanes dataset is a CSV file including 17 columns. \
Traffic Volumes AADT is a csv file containing 14 columns . \
Pems-8w csv file (from zip file California-data-set) contains 16,128 columns. 

https://catalog.data.gov/dataset/hov-70c14
https://zenodo.org/record/3939793#.ZA_nsnbMJD9
https://data.ca.gov/dataset/traffic-volumes-aadt

The risk may include small size of some of the used datasets.

# Reference: 

Duffin, E. (2023, Jan 3). Resident population of the U.S. in 2022, by state (including the District of Columbia). Statista. Retrieved from: https://www.statista.com/statistics/183497/population-in-the-federal-states-of-the-us/

Carlier, M. (2022, Jan 18). Automobile registrations in the United States in 2020, by state. Statista. Retrieved from: 
https://www.statista.com/statistics/196010/total-number-of-registered-automobiles-in-the-us-by-state/

