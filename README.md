# PyBer-Analysis
## Project Overview
PyBer has hired us to analyze their rideshare data; they've provided a ride.csv containing headers (city name, date, ride cost, id) and the city.csv with (city name, driver count, city type). From these files, we want to determine the total number of rides, drivers, fare count, and the average fare per city type. After we will plot the date's time series data vs. the sum of total fares, grouped by city type.

### Purpose
Using Pandas, we’ll create a summary DataFrame of the data by city type. Then using Matplotlib we’ll create a multiple-line graph, showing the first trimester of 2019's total fares by city type. Finally, we'll analyze these results.

---
## Analysis
Before this analysis, we must assume that Urban cities' population > Suburban > Rural, and further Urban cities' population density > Suburban > Rural.

### Summary Data Frame
<img width="629" alt="Screen Shot 2022-04-23 at 7 52 51 AM" src="https://user-images.githubusercontent.com/79609464/164915633-c6291a5d-b877-4d4d-b7b2-220f9c614b2c.png">

From our table, the more populous a city the more transactions and drivers it has. This trend is inversely proportional to the average fare price per city type; the less dense a population, the higher the average fare cost. Similarly, the Average Fare per Driver column confirms this; Denser populations will on average have cheaper fares than more spread out cities. 
<br />

### Sum of Daily Fares over Time
<img width="1097" alt="Screen Shot 2022-04-23 at 7 53 05 AM" src="https://user-images.githubusercontent.com/79609464/164915636-8926c0bf-5d55-4b56-8188-2b4efa181127.png">

This graph has a few important features. First, the volume of rides in Suburban and Rural cities has remained relatively stagnate. Urban cities remained stagnate after January, but had a significant (near $500 a day difference) uptick towards the end; one explanation is that fewer people are working during the beginning of January, hence there is less demand for PyBer. The last feature is across all city types, but February has a significant uptick around the middle/end of the month; the most obvious explanation is that people have the day off for Presidents day and needed to utilize rideshare services.
<br />

### Challenges and Difficulties
The biggest challenge I came across during this analysis was that the data set was extremely limited in terms of size (~2500 data points), and shape (Only covered the first trimester of 2019). To do a more thorough analysis of PyBer, I would need at least 1-3 years of data to adequately determine if the graph features are trends or mere flukes. With 1 year's worth of data, we could start to track the seasonal demands for PyBer's services; For all we know, April is the peak of our demand and our customers will choose to bike since the weather is better. 

---
## Results
- More populous cities have more drivers/customers and hence more transactions.
- Denser populations have things closer together and thus rides are shorter/transactions are cheaper.
- Demand in Suburban and Rural cities is less than in Urban cities and does not follow any trend; this implies PyBer is used as needed as opposed to regularly if the city isn't Urban. 
- Demand for PyBer in Urban Cities is lower during the beginning of January because people are still on vacation/don't need regular services. 
- February has a significant uptick in volume around the middle/end of the month because of the national holiday, Presidents Day.

---
## Summary
Urban cities have a greater demand for PyBer's services, but these transactions will- on average- be cheaper than less dense cities. If a city is less dense, things are more spread out, and- on average- our transaction will cost more, but there is not a regular demand. Finally, if there is a holiday all city types will have more transactions on that day.

---
