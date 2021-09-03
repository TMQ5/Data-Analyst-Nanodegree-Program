# Ford GoBike System Data Exploration

## Dataset
There are 174,952 bike trips in this dataset that happened in February and 1st, March of 2019. The dataset consists of 16 features ('duration_sec', 'start_time', 'end_time', 'start_station_name', 'end_station_name', 'user_type', 'member_birth_year', 'member_gender', 'start_hour', 'day_of_week_start', 'start_date', 'end_hour', 'day_of_week_end', 'end_date', 'age', 'duration_min'). Most variables are numeric, but 6 variables are categorical, which: start_station_name, end_station_name, user_type, member_gender, day_of_week_start and day_of_week_end. 


## Summary of Findings
Out of 174,952 trips, more than 140,000 were subscribers and less than 20,000 were customer this means that the subscribers (approximately 91% of users) was higher than that of customers (approximately 8%). Male users was higher than other gender by more than 120,000 trips (almost 75%). The median of users age was about 34 years and age range was between 20 - 56 years.

Based on day, the number of trips increases more on weekdays than on weekends (Saturday, sunday), and most trips on weekdays are on Thursdays with more than 30000 trips. Median of age is about 34 years in weekdays and about 32 years in weekend. In each day, number of trips for subscriber users is more than customer users and male more than ther gender. The highest number of trips for both user type and all gender type was on Thursday.

Based on trips start hour, most trips times start and end was in weekdays not in weekends from the 8 am to 9 am in the morning and from 4 pm to 6 pm in the evening, while the least times are between midnight and 5 am. The most popular time for the start and end of the trip is 5 pm.The time period for male is between 6 am - 22 pm and the most popular time is 5 pm and 8 am, while for female is between 7 am - 9 am and between 4 pm - 6 pm and the most popular time is also 5 pm and 8 am.

Based on trips duration(min), the median of trip duration was about 8 min. The highest duration in minutes for subscriber users is 5 min and for customer is 9 min while the highest duration for male  and female users is 5. The customer users has median duration higher than subscriber .The highest median for customer was in the weekend while the subscriber has the lowest median in weekend.



## Key Insights for Presentation
For the presentation, I focused on users characteristics like: gender, type, and age. Also look at the most popular time period. In addition to the relationship between interst features trip 'duration in minutes' and supported features 'user type' and 'member gender'. I started by presenting a comparison using bar chart and pie plot between the two types of users (subscribers and customers) and gender types(male,female,and other) who has the most bike trips? 

Then, I uesd histogram and boxplot to show the distribution of bike users age. After that, I showed the most popular time period in each day using heatmap. Then, I showed the user type for each user gender using bar chart. Afterwards, I compared between duration in minutes for each user type and for each gender using clustered bar chart and between median of duration in minutes for each user type for each gender using heatmap.





## Resources: 
https://www.youtube.com/watch?v=3aOtG9ns_Ko

https://www.youtube.com/watch?v=UFuo7EHI8zc

https://www.datasciencemadesimple.com/difference-two-timestamps-seconds-minutes-hours-pandas-python-2/

https://stackoverflow.com/questions/33379439/python-pandas-date-time-conversion-to-date

