# Investigate-Business-Hotel-using-Data-Visualization
Mini Project  

Data Preprocessing

The steps taken are

Importing libraries and importing datasets
Check data with the df.info() command to find out the types of data and the number of rows and columns
Check the statistics of the overall data with the command df.describe()

Handling Missing Value

Bring up the columns that have missing values ​​with the command df.isna().sum() then print based on the most data that has missing values
Performs handling missing values ​​with commands

Correcting Unsuitable Value

Perform Correcting Unsuitable Value for the meal column with the command

Correcting Data Types

Make changes to the data type in the necessary columns

Drop Unnecessary Data

Drops less useful data like columns

Save / save the data that has been preprocessed
New data name = data_clean.copy()

Visualization

![image](https://user-images.githubusercontent.com/116936082/218110294-db1fb690-0951-4e21-ba10-8a4fc9041888.png)

Based on the graph, the highest hotel bookings are in July and June. This can be seen from the percentage and number of hotel bookings. In the July period, city hotels had the highest percentage at 11.18%, while for June resort hotels had the highest percentage at 9.82%. Then at the end of the year it was 10.32% for city hotels and 9.61% for resort hotels, this was due to the Christmas and New Year holiday periods

In addition, the insights obtained in the domestic context from the graph above are that the periods of June and July are periods of school holidays or long lecture holidays, this causes a relatively high frequency of hotel bookings. Meanwhile, the year-end period is the Christmas and New Year holidays

![image](https://user-images.githubusercontent.com/116936082/218110911-73246273-a539-4161-a8b6-82a3baa36ab5.png)

The duration of the consumer's stay / length of stay has an effect on the high percentage of hotel order cancellations. On the other hand, if the duration is not too long, the percentage of hotel cancellations will be low/decreased
The most canceled hotel bookings for this type of city hotel are the duration of stay / length of stay 4 weeks with a percentage of 87.23%.
The most canceled hotel bookings for this type of resort hotel are the duration of stay / length of stay 3 weeks with a percentage of 46.75%.

![image](https://user-images.githubusercontent.com/116936082/218111279-71f05c3a-7136-4675-a3e6-b766702d2985.png)

Based on the graph above, the insight is obtained that:
Both types of hotels have the lowest cancellation rates for a 1-month order interval, namely 22.47% for city hotels and 13.11% for resort hotels.
Both types of hotels have the highest cancellation rates for booking intervals of 11-12 months, namely 77.41% for city hotels and 43.5% for resort hotels.
The cancellation rate has a tendency to increase for the order interval from 2-4 months  5-7 months  8-10 months. This can be seen from the trend chart.
