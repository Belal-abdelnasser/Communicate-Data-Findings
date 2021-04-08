# (Dataset Exploration Title)
## by (your name here)


## Dataset
> > This Dataset is for Ford Bikes and contain information about trips in Feb 2019. The structure of data is as follows:
> - duration_sec
> - start_time                |   183412 non-null  object
> - end_time                  |   183412 non-null  object 
> - start_station_id          |   183215 non-null  float64
> - start_station_name        |   183215 non-null  object 
> - start_station_latitude    |   183412 non-null  float64
> - start_station_longitude   |   183412 non-null  float64
> - end_station_id            |   183215 non-null  float64
> - end_station_name          |   183215 non-null  object  
> - end_station_latitude      |   183412 non-null  float64
> - end_station_longitude     |   183412 non-null  float64
> - bike_id                   |   183412 non-null  int64  
> - user_type                 |   183412 non-null  object 
> - member_birth_year         |   175147 non-null  float64
> - member_gender             |   175147 non-null  object 
> - bike_share_for_all_trip   |   183412 non-null  object 
> dtypes: float64(7), int64(2), object(7)
and This the key questions we need answers for:-

>- How long does the average trip take?
>- Does the above depend on if a user is a subscriber or customer?
>- What is Bike Sharing segemnt out of all users?
>- Subscribers to Customers ratio?
>- When are most trips duration in terms of time of day and day of the week?
>- Does the trips duration depend on if a user is a subscriber or customer?

## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
### Univariant Insights Summary
>- 90.5% subscribers and 9.5% customers.
>- We can see that males is more than females so far. Make 74.6%  and female 23.3%.
>- Thursday have te most taken trips.
>- 90.1% Sharing - 9.9 % Non-sharing
>- 5:00 AM is the most starting hour of trips.
>- Age distribution shows that there is outliers. This the only unusual point in all valriables of interest.
>- Duration distribution also have many extreme values but I can't decide it is outliers or not becuase I don't have domain knowledge.
>- Create month, weekday, hour and trip columns from start_time column To find out When are most trips taken in terms of time of day, day of the week.
>- Create (Age) new feature from birth data column
### Bivariate Insights Summary
> - We find from the plots that trips duration slightly change through different weekdays. The mean duration(sec) of trips is very close through weekdays.
> - We find that the mean Duration of trips is very close to each other during hours of the day. But the largest mean of duration of trips versus hours of the day is at 8:00 AM and 5:00 PM.
> - We find that most of users is subscribers regardless of gender. 
> - The rush hour of trips is before or after work hours which is pretty relevant becuase distribution of age of users shows that most of users is at work age (20:50 years old)
> - Almsot All od users are subscribers. 
## Multivariate Insights Summary
> - Daily trips duration change slightly for subscribers.
> - For customers there are clear change in weekdays trips duration and the the most increase happened in weekends.
> - For subscribers there are little change in Trips duration for each hour during the whole day. But for customers there significant change during day hours. As we can see at 3:00 AM is the biggest rise in Trips duration then comes 2:00 AM.
> - In Weekly basis the largest Trips duration for customers is in weekends
> - In Weekly basis Customers make larger average Trips durations than subscribers.
> - In Weekly basis Subscribers make small regular trips duration (everyday)-there is no peek- but I think for long term plan(months).
> - In Hourly basis Customers .
> - In Hourly basis Subscribers make small regular trips duration but I think for long term plan. 
## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
### Univariant Insights Summary
>- 90.5% subscribers and 9.5% customers.
>- Thursday have te most taken trips.
>- 5:00 AM is the most starting hour of trips.
>- Duration distribution also have many extreme values but I can't decide it is outliers or not becuase I don't have domain knowledge.
### Bivariate Insights Summary
> - We find from the plots that trips duration slightly change through different weekdays. The mean duration(sec) of trips is very close through weekdays.
> - We find that the mean Duration of trips is very close to each other during hours of the day. But the largest mean of duration of trips versus hours of the day is at 8:00 AM and 5:00 PM.
> - We find that most of users is subscribers regardless of gender. 
> - The rush hour of trips is before or after work hours which is pretty relevant becuase distribution of age of users shows that most of users is at work age (20:50 years old)
> - Almsot All od users are subscribers. 
## Multivariate Insights Summary
> - Daily trips duration change slightly for subscribers.
> - For customers there are clear change in weekdays trips duration and the the most increase happened in weekends.
> - For subscribers there are little change in Trips duration for each hour during the whole day. But for customers there significant change during day hours. As we can see at 3:00 AM is the biggest rise in Trips duration then comes 2:00 AM.
> - In Weekly basis the largest Trips duration for customers is in weekends
> - In Weekly basis Customers make larger average Trips durations than subscribers.
> - In Weekly basis Subscribers make small regular trips duration (everyday)-there is no peek- but I think for long term plan(months).
> - In Hourly basis Customers .
> - In Hourly basis Subscribers make small regular trips duration but I think for long term plan. 