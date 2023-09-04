# Hackathon-Data-Analysis

# Ride Sharing Data

This repository contains data on ride sharing trips. The data includes the following columns:

ride_id: Unique identifier for each ride
fare_amount: Amount of the fare
pickup_datetime: Date and time of the pickup
pickup_longitude: Longitude of the pickup location
pickup_latitude: Latitude of the pickup location
dropoff_longitude: Longitude of the dropoff location
dropoff_latitude: Latitude of the dropoff location
passenger_count: Number of passengers in the ride

# Data Cleaning
The data was cleaned to remove any rows with missing values. 

The haversine_distance column was also calculated, which is the distance between the pickup and dropoff locations, calculated using the Haversine formula.

# Analysis

The median haversine_distance was also found to be 2.12 miles. This means that half of the rides are less than 2.12 miles long, and half are more than 2.12 miles long.

There were 5632 rides where the haversine_distance was 0.0. These rides are essentially no-trips, as the driver did not move from their starting location.

The fare amount for the rides with a haversine_distance of 0.0 was found to be higher than the fare amount for the overall data.The distribution of the fare amount for the rides with a haversine_distance of 0.0 can be visualized using a histogram.

