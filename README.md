# # Overview of Analysis

The purpose of the project is to Visualize the bike sharing data based on the below three requirments

- Visualize length of time that bikes are checked out for all riders and genders
- Visualize number of bike trips for all riders and genders for each hour of each day of the week
- Visualize number of bike trips for each type of user and gender for each day of the week

Soures used
1.Pandas with python
2.Tableau
3.Bike Sharing data

## Results

In order to visualize the the bike trip duration of the users the bike sharing data given is converted into Pandas dataframe and then the trip duration column data type is changed to datetime to visualize in Tableau.

In order to fulfill the first requirment of how long bikes are checked out for all riders and genders graph is plotted for  
1.length of trip duration against number of bike users
2.length of trip duration against number of bike users based on Gender (Male, Female, Unknown)

![Chekout Time for Users](Module%20Challenge/Images/Chekout%20Time%20for%20Users.png)

Tableau link: ![https://public.tableau.com/app/profile/ghousiya/viz/CitybikeRide_CheckoutTimeforUsers/CheckoutTimeforusers]

![Chekout Time for Users](Module%20Challenge/Images/Chekout%20Time%20by%20Gender.png)

Tableau link: ![https://public.tableau.com/app/profile/ghousiya/viz/CitybikeRide_CheckoutTimebyGender/CheckoutTimebyGender]

The trip duration against weekday per hour is plotted as follows and below HeatMap is created
![Trips by Weekday per hour](Module%20Challenge/Images/Trips%20by%20Weekday%20per%20hour.png)

Tableau link: ![https://public.tableau.com/app/profile/ghousiya/viz/CitybikeRide_TripsbyWeedayperHour/TripsbyWeekdayperHour]

The trips per Weekday plotted by Gender is plotted as below 
![Trips by Weekday per hour by Gender](Module%20Challenge/Images/Trips%20by%20Weekday%20per%20hour%20by%20Gender.png)

Tableau link: ![https://public.tableau.com/app/profile/ghousiya/viz/CitybikeRide_TripsbyGenderWeekdayperHour/CreatetheTripsbyGenderWeekdayperHour]

The final Heat Map representing the trips based on user type plotted by Weekday per hour is generated as follows
![Trips by Weekday per hour by Gender_user type](Module%20Challenge/Images/Trips%20by%20Weekday%20per%20hour%20by%20Gender_user%20type.png)

Tableau link: ![https://public.tableau.com/app/profile/ghousiya/viz/CitybikeRide_UserTripsbyGenderbyWeekday/UserTripsbyGenderbyWeekday]

## Summary

From the above graphs plotted the following data points can be summarized.

- Maximum trip duration was for 5 minutes and most of the trip duration confined withing an hour
- From the Figure 2 it can be interpreted that Female bike users had 6 minute of maximum trip duration and 
  Male bike users had trip duration of 5 minutes
- The number of Male users are dominant sharing 65% male, 25% female, and 10% other genders approximately.
- From the heatmaps generated it can be interpreted that Bikes users are predominant during weekdays between  7-9 AM in the morning or between 5-8 PM
- Timeframe between 5-7 PM on Thursdays was the busiest of all other timeframes
- During weekends 7-9 AM timeframe was less busy as most users started to use the bike sharing service after 9 AM
- Majority of the bike users are Males
- Maximum number of users are Subscribers rather than Customers. 


Tableau Link
![https://public.tableau.com/app/profile/ghousiya/viz/CityBikeRide_Visualization/CityBikeRide_Visualization]
