# (Ford GoBike System DataSet Exploration)
## by (Salvation Peter)


## Dataset

This dataset has 183,412 records with 16 columns. The columns include 'duration_sec','start_time','end_time','start_station_id','start_station_name','start_station_latitude','start_station_longitude','end_station_id','end_station_name','end_station_latitude', 'end_station_longitude','bike_id','user_type','member_birth_year', 'member_gender','bike_share_for_all_trip'. 
Some of these columns were read in with the wrong data type which were changed before the exploration. Also a new column was added pointing to the particular day in the week for each start_time.



## Summary of Findings

The findings from the data exploration includes:
1. Females took longer time in their rides than males although the "other" group took the longest time. This could mean females either rode loger distances or rode with less speed. Due to lack of data this can not be really understood.
2. Though there was no actual relationship between the duration_sec and age except that on average those whose birth year between 1960 and 2000 have lower mean duration_sec
3. Subcribers have lower mean duration_sec as well as those who have the "yes" option for the bike share column.
4. The day with the highest mean duration is the 28th of february.
5. Thursday is the day name with the highest count of bike rides.
6. I also observed that more men rode bikes than any other gender class each day.
7. Males have the highest number of rides and also the lowest mean duration.
8. This was strengthened by the mean duration (sec) per day per member gender where the males had the least mean duration of rides.


## Key Insights for Presentation

For the presentation, the main threads to be displayed are summarized below. They are answers the questions below:

1. When are most trips taken in terms of time of day, day of the week, or month of the year?
2. How long does the average trip take? and
3. Does the above depend on if a user is a subscriber or customer?


Most rides were taken on the 28th of february, 2019. Cummulatively, Thursday ranks the day with the highest number of rides. On average, a ride could take about 726secs or being more generalistic, between 650s and 1400s and this could be influenced by the user type as subscribers have lesser mean duration than customers.
