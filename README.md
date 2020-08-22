# Cycling-during-Covid-19
### Introduction
Covid-19 is changing the ways we travel around the cities. Governments are advising against the use of crowded transportation except for essential travels. Those who need to go out are using more personal forms of transportation, such as bicycles, scooters and their own feet. Cycling has become one of the safest ways to travel outside as riding solo reduces the risk of catching the virus and keeps others safe. The objective of this project is to compare CitiBike 2019 and 2020 data to identify if the Covid-19 outbreak had an impact on the ridership.



### Defining the problem to solve:
Did CitiBike suffer a drastic ridership reduction?
Have people been travelling less and following the Stay-at-home orders?

Did the top Location that the riders visited changed?

What is the busiest bike in 2020? How many times was it used?


### CitiBike Hire key information
CitiBike bikes are available for hire at the docking- station terminal with a bank card or contactless  payment card.

Getting started is easy : simply hire a bike , ride it where you like, then return it to any of the hundreds of docking stations across NYC's city.

It costs $12 to access the bikes for 24hr , and the first 30 min of the journey is free. Longer journeys cost $4 for each additional 15 minutes.


### Collecting CitiBike Data
To download the data, I went to the official CitiBike webpage and clicked "Download" to all the 2019 files available System Data. 
The CitiBike System provides monthly CSV files that include:

Trip Duration (seconds)

Start Time and Date

Stop Time and Date

Start Station Name

End Station Name

Station ID

Station Lat/Long

Bike ID

User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)

Gender (Zero=unknown; 1=male; 2=female)

Year of Birth

The files have been processed to remove trips taken by staff, and any trips below 60 seconds in length (potentially false starts or users trying to re-dock a bike to ensure it’s secure).
