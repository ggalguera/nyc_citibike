# CitiBike Analysis

## Overview
This analysis aims to provide insights into the usage of CitiBike bicycle rental service in August 2019. The data used in this analysis contains information on trip duration, start and end times, start and end station locations, bike ID, user type, birth year, and gender. The data has been cleaned and prepared using Pandas, and visualizations were created using Tableau. Our end result is a Story with 7 different visualizations that will be used to show bussines results to stakeholders. 

## Results

### Dashboard

[link to dashboard](link to dashboard"](https://public.tableau.com/app/profile/guillermo.walter.galguera/viz/201908-citibike-dashboard/Story?publish=yes)

### Checkout Times for Users.
This visualization shows the distribution of checkout times throughout the day. We can see that subscribers are more likely to use the bicycles less than one hours, the most common trip time is 5 minutes.

![timesforusers](https://github.com/ggalguera/nyc_citibike/blob/main/Check%20out%20Times%20for%20Users.png)

### Checkout Times by Gender.
This visualization shows the distribution of checkout times throughout the day, separated by gender. It can be seen that male users are more likely use the bikes, while female users use them less.

![timesbygender](https://github.com/ggalguera/nyc_citibike/blob/main/Check%20out%20Times%20by%20Gender.png)

### Trips by Weekday for Each Hour.
This visualization shows the number of trips taken per hour, separated by weekday. It can be seen that the number of trips taken on weekdays is generally higher than on weekends, and that the majority of trips are taken during non-peak hours.

![tripsbyweekday](https://github.com/ggalguera/nyc_citibike/blob/main/Trips%20by%20Weekday%20per%20Hour.png)

### Trips by Gender (Weekday per Hour).
This visualization shows the number of trips taken per hour, separated by gender and weekday. It can be seen that male users are more likely to take trips during peak hours on weekdays, while both Genders are more likely to take trips during non-peak hours on weekends.

![tripsbygender](https://github.com/ggalguera/nyc_citibike/blob/main/Trips%20by%20Gender.png)

### Trips by Gender by Weekday.
This visualization shows the number of trips taken per weekday, grouped by gender. It can be seen that male users take more trips than female users on weekdays and that most of them are subscribers.

![tripsbygenderbyweek](https://github.com/ggalguera/nyc_citibike/blob/main/User%20Trips%20by%20Gender%20by%20Weekday.png)

### Start Locations Map.
This visualization shows the locations of all trip start stations on a map. The size of the circles represents the number of trips starting from that location.

![startlocationmap](https://github.com/ggalguera/nyc_citibike/blob/main/Start%20Location.png)

### End Locations Map.
This visualization shows the locations of all trip end stations on a map. The size of the circles represents the number of trips ending at that location.

![endlocationmap](https://github.com/ggalguera/nyc_citibike/blob/main/End%20Location.png)

## Summary
Overall, the analysis shows that subscriber usage is higher during peak hours on weekdays, while customer usage is higher during non-peak hours. Male users are more likely to take trips during peak hours on weekdays, while female and male users are more likely to take trips during non-peak hours on weekends. The majority of trips start and end in Manhattan, with a few clusters in Brooklyn and Queens. The data suggests that the CitiBike service is most popular among male subscribers who use the service to commute to work during the week.

### Aditional Analysis
One aditional Analysis can be to show the usage by age, we can use the birth year to make this calculation.
A second Analysis can be to measure the bicycle utilization to predict maintenance requirements.
