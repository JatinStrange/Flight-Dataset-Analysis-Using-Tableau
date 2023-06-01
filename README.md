# Flight-Dataset-Analysis-Using-Tableau
DATASET
Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

FEATURES
The various features of the cleaned dataset are explained below:
1) Airline: The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.
2) Flight: Flight stores information regarding the plane's flight code. It is a categorical feature.
3) Source City: City from which the flight takes off. It is a categorical feature having 6 unique cities.
4) Departure Time: This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and have 6 unique time labels.
5) Stops: A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.
6) Arrival Time: This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.
7) Destination City: City where the flight will land. It is a categorical feature having 6 unique cities.
8) Class: A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.
9) Duration: A continuous feature that displays the overall amount of time it takes to travel between cities in hours.
10)Days Left: This is a derived characteristic that is calculated by subtracting the trip date by the booking date.
11) Price: Target variable stores information of the ticket price

The aim of our study is to answer the below research questions:
1). Availability of tickets
2). Maximum and Minimum price of different airlines ?
3). Price variation wrt days left to travel
4).Which date must be chosen based on the ticket fare?
5). Total flights travelling in a given time of day( for example morning-->evening)
6). Number of flights based on the number of stops
7). Minimum Price Variation of each airline(with forecast of min price in future)
8). Variation in the average ticket  price in the Economy and Business class?
9). Checking Flights across with different stops and timings under different airlines
10). Ticket Pricing System
