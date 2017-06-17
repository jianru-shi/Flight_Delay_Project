### Data Source
 
The original data airline_delay_causes.csv is downloaded \
from [RITA](https://www.transtats.bts.gov/ot_delay/ot_delaycause1.asp?type=21&pn=1).

The time period is from April, 2012 to April, 2017. 

### Data Description 

The complete original dataset has 70695 records and 16 variables: 


Name	Description
1	Year	2012-2017
2	Month	January-December
3   Carrier 	Carrier Code
4 	CarrierName 	Carrier Name
5	Airport 	Airport Code
6	AirportName		Airport Name
7 	ArrFlights		Number of arrival flights
8	ArrDel15		Number of arrival flights delay more than 15min 
9	ArrCancled 		Number of canceled arrival flights
10  ArrDerived 		Number of derived arrival flights
11	ArrDelay	arrival delay, in minutes
12	CarrierDelay	in minutes
13	WeatherDelay	in minutes
14	NASDelay	in minutes
15	SecurityDelay	in minutes
16	LateAircraftDelay	in minutes

### New Variables Created from Original Dataset

Name 	Description 
1 	avg_delay 	 ArrDelay/ArrFlights
2	avg_CarrierDelay	CarrierDelay/ArrFlights, in minutes
3	avg_WeatherDelay	WeatherDelay/ArrFlights, in minutes
4	avg_NASDelay	avg_NASDelay/ArrFlights, in minutes
5	avg_SecurityDelay	avg_SecurityDelay/ArrFlights, in minutes
6	avg_LateAircraftDelay	avg_LateAircraftDelay/ArrFlights, in minutes

### Groups Created in Tableau

Name 	Description
1 MajorAirport 	Grouped 18 major airports in the US
