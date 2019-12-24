# (Forgobike Dataset)
## by (Youssef Shabana)


## Dataset

This dataset contains users bike rides records including their user type, gender, age, trip duration, stations, trip date. 
Below wrangling has been done before exploring the data:
Quality Issues
1) Some Columns have null values have been dropped.

2) End_time and Start_time columns are object not date, type changed to be date.

3) Some rows have null values have been dropped.

Tidiness Issues
1) Dates are all in one column (hour, day, month & year), separated in separate columns

2) Birthyear column is provided. However, age column will be much better and easier in analysis and communication, age column has been added.

3) Trip Duration in seconds is provided but it will be much better if it is in Hours, Duration_hour column has been added.


## Summary of Findings

1) Most of the bikers are between 20 and 60 years old, the rest are outliers and will be removed
2) Subscribers are using the service way more than customers
3) Majority of the bikers are Males
4) As we found before most of the customers are subscribers and here it looks like they are using the service daily in normal working days Mondays to Fridays. On the other hand, Customers trend is almost the same daily.
5) October is the highest month in traffic, Also the lowest in traffic is December. Maybe it has something to do with the weather, as it starts to increase from December to October.
6) As expected from the gender graph earlier, there is a big difference between the number of male subscribers and female subscribers. Howevere, the difference bwteen female and male customers is not that much which may suggest that most of the customers are couples trying the service together maybe for fun or exploration.
7) Most of the users (customers & Subscribers) use the service for about 5 hours, except for users in their 30s they use for longer time around 10 hours
	


## Key Insights for Presentation

The main thread used in the presentation is the user type with their count and activity during the week & year and their behavior.