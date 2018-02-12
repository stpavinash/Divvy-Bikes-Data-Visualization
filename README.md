# Divvy-Bikes-Data-Visualization

I've used the Divvy Challenge dataset from the Divvy bikes in Chicago to produce a single visualization with the dataset. 
Below are some guidelines given as part of the contest. 
"Explore the data to see how Chicago gets around by bike by visualizing over 3.2 million Divvy trips in an insightful, beautiful, 
or creative way."

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

Metadata for Stations:

Variables:

id: ID attached to each station
name: station name    
latitude: station latitude
longitude: station longitude
dpcapacity: number of total docks at each station as of 6/30/2017
online_date: date the station was created in the system
