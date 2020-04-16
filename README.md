# Tableau Homework - Citi Bike Analytics



As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, I downloaded Jun through Dec 2019 data to provide some insights on CitiBike usage, ridership, and my recommendations. 
Data Source: [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

Used pandas/jupyter notebook to merge the individual files (one for each month) and relabeled gender (to unknown, male, and female instead of 0,1, and 2). Have the following fields in Tableau. 

* Trip Duration (seconds)
* Start Time and Date
* Stop Time and Date
* Start Station Name
* End Station Name
* Station ID
* Station Lat/Long
* Bike ID
* User Type (Customer = 24-hour pass or 3-day pass user; Subscriber = Annual Member)
* Gender (Zero=unknown; 1=male; 2=female)
* Year of Birth
* Age (Calculated in Tableau based on Birth Year)
* Age Groups (Created groups of 5 years in Tableau)
* Sum of trips at Each Station (divided into 3 buckets for >66,666, 66,666-33,333, <33,333)


## Tasks and Takeaways

* How many trips have been recorded total during the chosen period (Jun-Dec 2019)? 13,621,906 trips

* By what percentage has total ridership grown?Grown in the summer months by about 2-7% every month and then decreased duing the winter months by about 14-35%.

* How has the proportion of short-term customers and annual subscribers changed? Short-term visitors are a very small percentage of subscribers (about 18%) and it reduces a lot in Winter.

* What are the peak hours in which bikes are used during summer months? Commute hours (8am and then 5-6pm) have peak activity. Summer has more activity than Winter but trends are the same by hour of day. 

* What are the peak hours in which bikes are used during winter months? Commute hours (8am and then 5-6pm) have peak activity. 

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?) Indicated in top 10 stations but basically the ones in the center of NY and ones on the periphery that go to New Jersey, etc.

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?) Similar to the top 10 starting stations

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

* Today, what is the gender breakdown of active participants (Male v. Female)? about 70% males and 23% females 

* How effective has gender outreach been in increasing female ridership over the timespan? Not very effective as females did not increase over teh timespan.

* How does the average trip duration change by age? People in teh age group of 25-35 and 5-55 have peak activity both in trip duration and number of trips.

* Which bikes (by ID) are most likely due for repair or inspection in the timespan?
Assuming longer trip duration bikes will need repair the top 3 (based on trip duration) are: 16498, 32225, 39570

* How variable is the utilization by bike ID? Very variable anywhere from over 5,000,000 seconds (trip duration) to a few hundred.

* A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.- shown in Tableau

## BIG TAKEAWAYS





### Copyright

Data Boot Camp (C) 2019. All Rights Reserved.
