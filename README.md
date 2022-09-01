# (Dataset Exploration Title)
## by (Adedoyingit)


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area called '201902-fordgobike-tripdata'.

>The data has 183412 individual rides in the dataset with 16 features (duration_sec, start_time, end_time, start_station_id, start_station_name, start_station_latitude, start_station_longitude, end_station_id, end_station_name, end_station_latitude, end_station_longitude, bike_id, user_type, member_birth_year, member_gender, bike_share_for_all_trip). Nine columns are numeric in nature while the variable columns include; start_station_name, end_station_name, member_gender, user_type, bike_share_for_all_trip which are nominal variables.
> Wrangling Steps
I changed the datatype of the start_time and end_time to datetime datatype inorder to extract the month, day and time bike trips were taken using the Define,Code and Test steps. 
After extracting the day and time, I categorized time into periods of the day (Early Morning, Morning, Evening, Late Night, Noon and Night).
I added


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
>Univariant part of the visualization tells more of the categorical and numerical varaibles using histogram and barchart.

>Bivariant visualizations where I compared two categorical variables and two numerical variables.

> Multivariant visualizations compared three variables together. 

>Some interesting findings are: 

>There are more male bike trips than Female trips(univariant)

>Most bike trips were less than 5,000 duration_sec.(univariant)

>Customer user_type had less trips, but had more duration_sec trips than subscriber(bivariant)

>Evening trips are more than other trips and more duration_sec was spent during the evening trips(bivariant)

>Customer user_type trips had higher duration_sec throughout the weekdays compared to Subcriber(multivariant)

>These findings are interesting one to put in the explanatory presentation. 

## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

>The most trips lies below 5,000 duration_sec while higher duration_sec are few.

>Customer user_type are fewer than subsriber use_type

>Evening trips are the highest trips taken

>Customer user_type trips had higher duration_sec throughout the weekdays compared to Subcriber

>Evening trips had highest duration_sec compared to the trips taken in other periods

>Evening trips are more on weekdays compare to Saturday and Sunday

>Early morning trips has the highest duration_sec on Sunday. On weekdays except Saturday and Sunday, early morning trips have the least duration_sec.

>On Sunday, customer user_type have the highest duration_sec followed by Saturday.

>Customer have more duration_sec compared to subscriber across the weekday, noting that duration_sec for most trips are less than 5,000duration_sec

>Early morning trips are more on Saturday and Sunday

>I expect to have more subscriber duration_sec across the weekdays and periods, but visualization helped to tell that even if subscribers were more than customer user_type. Customer user_type take longer bike trips.
