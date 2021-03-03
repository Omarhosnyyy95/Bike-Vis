# Ford GoBike System Data
## by: Omar Hosny

- ## Dataset: 
    The dataset in hand is for Ford Go Bike System data which contains information about bike trips for customers and subscribers, after dropping missing values the dataset is now 174,952 rows with 16 variables. 9 of which are numerical, 2 datetime variables and 5 other categorical variables. I'm interested in studying the trip duration and how it relates to member's age, member's gender and member's type. I'm also interested in studying the trip's start time distribution through the weekdays and weekends.

- ## Summary of Findings
    - The maximum ratio of missing values are in 'member_birth_year' and 'member_gender' and it **doesn't exceed 5%** of the data. 
    - Our service is more used (**almost double**) during **weekdays** compared to **weekends**.
    - An average **trip duration** will vary from **200** to **1000** secs.
    - The huge number of our users are between **25** and **40** years.
    - Around **75%** of our users are **males**.
    - More than **90%** of the users in this dataset are **subscribers**.
    - for **weekdays**(from Monday to Friday), rush hours for using our service are between **7 am-9 am** and between **4 pm-6 pm**. However for **weekeneds**, the distribution is random  with most of the data falls between **12 pm and 6 pm**. This suggests that our service is widely used by our users to go from and to their jobs during weekdays.
    - Though males use our services more than women as shown in the Univariate data exploration(around 75% of the dataset are males). By comparing the **trip duration** between **males** and **females**, seems that there is **no much difference** between them.
    - Our **customers** tend to take the bikes for **longer durations** per trip than our subscribers.
    - We can see that the **age** of our **subscribers** tend to be **slight older** than the age of our **customers**.

- ## Key Insights For Presentation
    First I want to show through the Univariate Analysis the number of trips along weekdays and weekends, distribution of trip duration, age of users in the dataset, gender distribution in our data and user types. Moving to the bivariate analysis, we can discover if there's any relation between the start hour of using the service and the weekday, trip duarion and age, trip duration and gender, trip duration and user type. At the end we will have a look on the trip duration vs age in each user type category(customer or subscriber)

