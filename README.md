


create table uber(
Trip_count Integer,
fare_amount float,
pickup_longitude float,
pickup_latitude float,
dropoff_longitude float,
dropoff_latitude float,
PICKUP_COUNTRY text,
DROPOFF_COUNTRY text,
passenger_count integer,
travel_mode text,
year integer,
Month integer,
Day integer,
weeks integer,
Hours integer,
Minute integer,
Second integer,
Time time,
Date date,
Weekdays text,
Distance_in_km float,
Time_of_Day text,
DateTime Date)

select * from uber;

copy public. "uber" from 'C:\Users\Pavit\Downloads\uber_csv.csv' delimiter ',' csv header;

select * from uber;
