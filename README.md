# Project Name: HOTEL BOOKINGS ANALYSIS

-------
# Problem Definition
Optimizing Hotel Bookings for International Travelers

------
# Objective
To analyze the provided dataset of hotel bookings and extract insights to optimize the company’s services for international travelers.

--------
# Data Sourcing
The data analyzed is an open access data downloaded from the repository of the DatAfrik community. It consists of 66,541 hotel bookings between January 1st 2010 and December 31st 2019 from a company who helps international travellers around the world secure hotels in destination countries.


---------
# Data Transformation
In excel, five (5) duplicate entries were found and removed. Also, a wrong data entry having age at -5 was discovered and deleted reducing the total bookings to 66,535. 

Using Power query, a conditional column was added to segment the travellers into categories: Individual, Couple, and Group which is dependent on the No. of People column.


--------
# Findings and Recommendations
Insights:
1. The company has its customers spread across 7 south east Asian countries with her highest travellers alternating between Thailand and Malaysia across the 10-year period. 
2. In 2019, the company recorded over a double of the total bookings in 2010 which was at 4,797.
3. Bookings trendline across the years is sinusoidal indicating a periodic increase and decrease in bookings.
4. A positive correlation is observed between bookings and revenue. However, in 2014, bookings increased by 400 compared to the previous year but revenue decreased from 1.15M to 0.93M. This invariably means that hotels with low booking price were booked more in 2014.
5. 66,535 bookings recorded in 10 years with 73% spread almost evenly in Malaysia, Thailand, Singapore and Indonesia. 
6. All countries except Cambodia showed an upward trend in bookings between November and December.
7. All years except 2010 have their peak booking period in the last quarter of the year. Booking declined in 2010.
8. No. of people to no of rooms ratio is approximately 2:1.
9. Over 70% of bookings were from group travelers.
10. Great number of bookings happen in the afternoon hours of Sunday.

-----
# Dashboard
