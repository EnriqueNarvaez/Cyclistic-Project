# Main Data

Check the data in the following link and replace de data according to the following instructions:

df_202301 -> https://divvy-tripdata.s3.amazonaws.com/202301-divvy-tripdata.zip
df_202302 -> https://divvy-tripdata.s3.amazonaws.com/202302-divvy-tripdata.zip
df_202303 -> https://divvy-tripdata.s3.amazonaws.com/202303-divvy-tripdata.zip
df_202304 -> https://divvy-tripdata.s3.amazonaws.com/202304-divvy-tripdata.zip
df_202305 -> https://divvy-tripdata.s3.amazonaws.com/202305-divvy-tripdata.zip
df_202306 -> https://divvy-tripdata.s3.amazonaws.com/202306-divvy-tripdata.zip
df_202307 -> https://divvy-tripdata.s3.amazonaws.com/202307-divvy-tripdata.zip
df_202308 -> https://divvy-tripdata.s3.amazonaws.com/202308-divvy-tripdata.zip
df_202309 -> https://divvy-tripdata.s3.amazonaws.com/202309-divvy-tripdata.zip
df_202310 -> https://divvy-tripdata.s3.amazonaws.com/202310-divvy-tripdata.zip
df_202311 -> https://divvy-tripdata.s3.amazonaws.com/202311-divvy-tripdata.zip

License Link:
* [Here](https://divvybikes.com/data-license-agreement)

Full Data Link:
* [Here](https://divvy-tripdata.s3.amazonaws.com/index.html)


# Divvy_Stations_2017

This file contains metadata for both Trips and Stations files.

For more information, visit http://DivvyBikes.com/data or email questions to data@DivvyBikes.com. 


Metadata for Trips:

Variables:

trip_id: ID attached to each trip taken
start_time: day and time trip started, in CST
stop_time: day and time trip ended, in CST
bikeid: ID attached to each bike
tripduration: time of trip in seconds 
from_station_name: name of station where trip originated
to_station_name: name of station where trip terminated 
from_station_id: ID of station where trip originated
to_station_id: ID of station where trip terminated
usertype: "Customer" is a rider who purchased a 24-Hour Pass; "Subscriber" is a rider who purchased an Annual Membership
gender: gender of rider 
birthyear: birth year of rider


Notes:

* First row contains column names
* Trips that did not include a start or end date are excluded
* Trips less than 1 minute in duration are excluded
* Trips greater than 24 hours in duration are excluded
* Gender and birthday are only available for Subscribers
* Divvy_Trips_2017_Q3 has 1,608,270 rows
* Divvy_Trips_2017_Q4 has 669,239 rows



Metadata for Stations:

Variables:

id: ID attached to each station
name: station name    
latitude: station latitude
longitude: station longitude
dpcapacity: number of total docks at each station as of 12/31/2017
online_date: date the station was created in the system

Notes:

* Divvy_Stations_2017_Q3Q4 has 586 rows