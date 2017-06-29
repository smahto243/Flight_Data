# Flight_Data
Analyze NYC-Flight data

This dataset contains information about all flights that departed from NYC 
(e.g. EWR, JFK and LGA) in 2013: 336,776 flights in total. 

Exploration ideas:
---------------------------------------------------------------------------
	Departure delays.
	Best airports in terms of time departure %. 
	Aircraft speed analysis. 
	On time arrival % analysis. 
	Maximum number of flights headed to some particular destination.
	

	
Name			Description
------------	---------------------------------------------------------------
year			2013
month			1-12
day				Day of the month (1-31)
dep_time		Departure times, local timezone (HHMM)
sched_dep_time	Scheduled departure time (HHMM)
dep_delay		Departure delay, in minutes, Negative times represent early departures
arr_time		Arrival times, local timezone (HHMM)
sched_arr_time 	Scheduled departure time (HHMM)
arr_delay		Arrival delay, in minutes, Negative times represent early arrivals
carrier			Two letter carrier abbreviation
flight			Flight number
tailnum			Plane tail number
origin, dest	Airport codes for origin and destination
air_time		Amount of time spent in the air, in minutes.
distance		Distance flown, in miles.
hour, minute	Scheduled Time of departure broken in to hour and mins.
time_hour		Timestamp (Scheduled Departure Slot: Date & Hour)
