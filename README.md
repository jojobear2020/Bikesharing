# Bikesharing


## PROJECT OVERVIEW

Using sample size from August 2019, we analyzed user profiles and some of the key bike rider’s trends. This information is especially helpful as it may help convince investors that a bike-sharing program in Des Moines is a solid business proposal. For easier understanding, we created a story in Tableau that any investor can go and check, if they wish.

[CITI BIKE DASHBOARD - STORY (August 2019)](https://public.tableau.com/profile/larysa.oddo#!/vizhome/NYCCitibike_16038393812120/CitiBike?publish=yes))


## RESULTS

1. For this analysis, first we used Pandas to change the "tripduration" column from an integer to a datetime datatype. 

2.	Then, using the converted datatype, we created in Tableau a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders

To show correlation between converted travel time and numbers of bikes, we plotted this chart that demonstrates number of bikes/bike rides depending on trip duration in hours and minutes. Top of the chart is at 5 hours meaning that this trip duration was the most common


![](https://github.com/jojobear2020/Bikesharing/blob/main/Images/checkout_times_for_users.PNG)


We then added filter by genders to see the same trend but if factor in rider’s gender. From this chart we see that males tend to use Citi bikes more often than female. We also have the unknown gender category, which is skewing this results a bit.

![]( https://github.com/jojobear2020/Bikesharing/blob/main/Images/checkout_times_by_gender.PNG)


* Show the number of bike trips for all riders and genders for each hour of each day of the week

This chart confirms our findings about Male/Female/Unknow gender proportion when it comes to Citi bikes use. We modified our chart a bit and added weekday and hour criteria. We see that the most density in Males section of the cart on Mondays, Tuesday and Thursdays between 17-18pm. Surprisingly Wednesday night is quite “light”. These results potentially signify that even though we do not have that in our data, many Citi bikes users use it to commute from work to home.

![]( https://github.com/jojobear2020/Bikesharing/blob/main/Images/trips_by_gender_weekdays_hour.PNG)


* Show the number of bike trips for each type of user and gender for each day of the week.


We also looked at the type of users – subscriber or customer who only occasionally use Citi bikes. Based on our chart below, Male Subscribers are the ones that use services more frequently.

![]( https://github.com/jojobear2020/Bikesharing/blob/main/Images/user_trips_by_gender_weekday_hour.PNG)




3.	Finally, we added these new visualizations to the two we created in this module for your final presentation and analysis to pitch to investors.


Citi bike start and end points maps. This helps understand where the bikers actually start and go to. As per graph below, we see that it is all as spread throughout the city area with Manhattan and Brooklyn leading in bike riders’ start and destination points. We can view this information as a the closer to the downtown area, the more people use it.

![]( https://github.com/jojobear2020/Bikesharing/blob/main/Images/map_start_end_points.PNG)


This graph is just for informational purposes to see what stations are the most used as a starting point.

![](https://github.com/jojobear2020/Bikesharing/blob/main/Images/top_start_stations_by_gender.PNG)



## SUMMARY

For this analysis we utilized two main tools in this analysis – Python (for cleaning the data) and Tableau (visualization).
Using one-month data sample, we found out the most popular weekdays and times for bike rides, including how it correlates with the gender and user profile. Since Des Moines is also a quite large city, we can assume that we can expect similar trends there too. This is essential in developing the right marketing strategy and targeting the right customer base. 

