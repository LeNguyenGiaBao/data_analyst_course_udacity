# Ford GoBike System Data
## by Nguyen Gia Bao Le

## Dataset
Ford GoBike System Data includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in February 2019.

Data source: 
- [https://www.bikeshare.com/data/](https://www.bikeshare.com/data/)
- [**Github** Bike-Share-Data-Systems](https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems)
- [**Udacity** 201902-fordgobike-tripdata.csv](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)

Data Structure: 

The dataset have 183412 records, 16 columns. 

| column | num records | datatype | description |
| - | - | - | - | 
| duration_sec            | 183412 | int | Trip duration (second) |
| start_time              | 183412 | text | The start time of ride |
| end_time                | 183412 | text | The end time of ride |
| start_station_id        | 183215 | float | The id of the station that start the ride |
| start_station_name      | 183215 | text | The name of the station that start the ride |
| start_station_latitude  | 183412 | float | The latitude of the station that start the ride |
| start_station_longitude | 183412 | float | The longitude of the station that start the ride |
| end_station_id          | 183215 | float | The id of the station that end the ride |
| end_station_name        | 183215 | text | The name of the station that end the ride |
| end_station_latitude    | 183412 | float | The latitude of the station that end the ride |
| end_station_longitude   | 183412 | float | The longitude of the station that end the ride |
| bike_id                 | 183412 | int | The id of the bike |
| user_type               | 183412 | text | The type of user: 'Customer' and'Subscriber' |
| member_birth_year       | 175147 | float | Year of birth of the user |
| member_gender           | 175147 | text | Gender of the user |
| bike_share_for_all_trip | 183412 | text | The user uses bike share system for all his trip | 


## Summary of Findings

Summary about user: 
- User age in range from 20 to 60, and the range from 30 to 40 is the most population age range
- Majority of user is man, greater than 3 times of woman
- Almost users are Subscriber User (pay for the system), is 89.19%
- Male user pay for system more than female user
- Female user take more time than male user

Summary about time of the trip:
- Almost the trip is in the same day, and less than 20 minutes
- The weekdays have more booked than the weekends
- In weekdays, the most booked time are 8 AM and 5 PM
- In weekends, the most booked time is 1 PM.

Summary about the location of stations and the routes:
- The stations are in 3 groups, like 3 cities
- Almost the trips are in the same city
- The route between 2 cities in the south is the greater than to city on the north

## Key Insight for Presentation
User of this system could be office staff, especially the Subscriber Users, because:
- They use the system in the before and the after of working hour
- They are in working age
- They use the system in the working day more than the weekend day
- They use the system for the short trip, in the same city and less than 20 minutes
