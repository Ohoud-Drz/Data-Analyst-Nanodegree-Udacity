# CitiBike Data Exploration - Second Quarter 2020/2021
## by Ohoud Draz

Citi Bike is New York City’s bike share system, with 20,000 bikes and over 1,300 stations. Launched in May 2013, and has become an essential part of transportation network. 

## Dataset

> Two datasets for the years 2020 and 2021 have been used. Each dataset contains information about trips made in CitiBike system during the second quarter of the year. They are downloaded from their website https://ride.citibikenyc.com/system-data. 

> CitiBike system creates a file for each month so second quarter files downloaded and compiled into one file for each year. Since the files  have been downloaded for different years, each year has its own data format:
       1. Names of columns were different.
       2. Values of category variable 'user type' are different in the datasets.
For data standardization and reducing distraction, update 2020 dataformat to 2021 dataformat "the new data format".

## Summary of Findings

> 1. In the second quarter of 2020, 56% of CitiBike users were male. And 30% of its users were female.
  2. Docked bike is the preferred bike for CitiBike users in the second quarter of 2021. Electric bike only had been used 6 times over 3 months, maybe because of its price per minute compared to others.
  3. The number of trips in the second quarter of the year 2021 has almost doubled.
  4. Around 70% of the total trips were made by Members in 2021.
  5. CitiBike usage gradually increases during normal working hours in New York City.
  6. Most of the trips were made in June (Spring/Summer Season) according to NYC weather.
  7. The average of trip duration for Casual users is higher than Member users.
  8. In 2020 and 2021, Saturday and Sunday have the highest average trip duration compared to other days of week.
  9. The average of trip duration for member females is higher than the average of trip duration for other members (male and unknown).
  10. The average of trip duration is longer when using Docked bike than using Classic bike for Casual and Member users.


## Key Insights for Presentation

> For the presentation, at first looking at each year's dataset separately by checking Citibike usage by gender in 2020. Then checking the most used bikes in 2021. After that making a comparsion by checking the number of trips in the second quarter of 2021 compared to 2020. Then looking at Citibike usage by user type. Followed by, investigating peak hours of CitiBike usage. Then the trip duration distribution and number of trips from April to June. Finally, looking at the relations between trip duration and other factors (gender, user type, bike type).