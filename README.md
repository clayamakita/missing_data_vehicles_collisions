# Project from Dataquest: Working with Missing Data

In this mission from the Dataquest platform, the main goal is to learn the basics on how to handle missing data without having to drop rows and columns. The techniques used include: 

- imputation: filling in a missing value with a replacement value
  - verification of totals through the sum of the individual columns
  - most common value in a column
  - placeholder (ex: Unknown)
  - supplemental data which correlates with part of the actual data set
- plotting the missing values (ex: with a heatmap, for example): to understand visually how the missing values are distributed
- correlating missing values: to find out if there's any pattern among the missing values.

The given dataset is comprised of vehicle collisions in New York City and published on the [NYC OpenData website](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95). We'll work with an extract of the full data: crashes from the year 2018. Several modifications were made to the data for teaching purposes, including randomly sampling the data to reduce its size.

The data set is in a csv called __nypd_mvc_2018.csv__ and the project is presented on a Jupyter Notebook called __Working with Missing Data.ipynb__.

Below is a summary of the columns and their data:

- __unique_key__: a unique identifier for each collision
- __date__, __time__: data and time of the collision
- __borough__: the borough, or area of New York City, where the collision occurred
- __location__: latitude and longitude coordinates for the collision
- __on_street__, __cross_street__, __off_street__: details of the street or intersection where the collision occurred
- __pedestrians_injured__: number of pedestrians who were injured
- __cyclist_injured__: number of people traveling on a bicycle who were injured
- __motorist_injured__: number of people traveling in a vehicle who were injured
- __total_injured__: total number of people injured.
- __pedestrians_killed__: number of pedestrians who were killed.
- __cyclist_killed__: number of people traveling on a bicycle who were killed
- __motorist_killed__: number of people traveling in a vehicle who were killed
- __total_killed__: total number of people killed.
- __vehicle_1__ through __vehicle_5__: type of each vehicle involved in the accident
- __cause_vehicle_1__ through __cause_vehicle_5__: contributing factor for each vehicle in the accident
