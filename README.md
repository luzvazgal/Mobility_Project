# Mobility_Project
Project to determine the lag people have to leave their home before arriving late to their destination

In order to visualize results, you need to run the project as follows:

Cleansing
Analysis
Delta Traffic Analysis
Statistics

Cleansing
Takes 'Zona Metropolitana' survey data, converts it to a data frame merged with all referenced catalogs. Once all of them are merged, it does cleansing process: removing columns not required for analysis, validating if columns are not entirely having NaN values, change NaN by zero value.
Renaming columns to be more user friendly

Analysis
It does all the behavioral analysis of survey: mean time it takes to arrive to any date (from 50-60 mins), average per trip given a certain time of Labor Day type.

It also creates data frame of the routes having more traffic of the survey (9 routes) to be taken as a sample and get their real time information using Google Places API.

Delta Traffic Analysis
Getting clean data set to narrow search to people traveling from Mexico City or State of Mexico, and using Analysis Dataframe to get the most important routes to get Google real time traffic information

Statistics
Showing normal distribution, mean, median, mode of all trip duration time coming from survey
Showing behavior for real time traffic information 
 
