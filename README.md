# PyBer-Analysis
## Project Overview
PyBer has hired us to analyse their ride and city csv's; they contain (city name, date, ride cost, id) and (city name, driver count, city type) respectively. From these files we want to determine the total number of rides, drivers, fare count and the average fare per city type. After we will plot the date time series data grouped as city type vs. the total fares from that day.

### Purpose
Using Pandas, we’ll create a summary DataFrame of ride-sharing data by city type. Then using Matplotlib we’ll create a multiple-line graph, showing the first trimester of 2019's total fares by city type. Finally we'll analyse these results.

---
## Analysis
### Summary Data Frame
<img width="629" alt="Screen Shot 2022-04-23 at 7 52 51 AM" src="https://user-images.githubusercontent.com/79609464/164915633-c6291a5d-b877-4d4d-b7b2-220f9c614b2c.png">

From our table, the more populous a city (Urban > Suburban > Rural) the more rides and drivers it has. This trend is inversly proportional to the average fare per city type; the average fare price in Urban cities is lower than Suburban and Rural because things are closer together. Additionally, the Average Fare per Driver's column can confirms this; the more populous a city the shorter the average ride. 
<br />

### Fares over Time
<img width="1097" alt="Screen Shot 2022-04-23 at 7 53 05 AM" src="https://user-images.githubusercontent.com/79609464/164915636-8926c0bf-5d55-4b56-8188-2b4efa181127.png">

This graph has a few important features. First, the volume of rides in Suburban and Rural cities has remained relatively stagnate. Urban cities remain stagnate after January, but have a significant (near $500 a day) differnce during; one way to explain this is that less people are working during the begining of January, hence there is less demand. The last feature is across all city types, but Febuary has a significant uptick around the middle end of the month; the most obvious explanation is that people have the day off for Presidents day and decided to go out.
<br />

### Challenges and Difficulties
One challenge I came across was making accurate deductions as the data was very limited (<2000 data points)

---

## Results
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type. (7 pt)

---

## Summary
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)

---
