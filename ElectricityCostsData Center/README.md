# Project info
It is provided by DataCamp [link](https://github.com/datacamp/careerhub-data/tree/master/Electricity%20Prices)
I've made some visualizations, calculated hypothesis testing and created a model to predict prices.
- Conclusions:
  - 16:00 - 21:00 electricity tends to be most expensive
  - Sundays and Mondays are more expensive then other days.
  - In the hypothesis testing section I concluded that a hypothesized 50-cabinets data center can cost around 82.37 $ per day more in holidays. 
  - Also 107.71 $ per day more on Sundays or Mondays.
  - And over 200$ more between 16:00 and 21:00 then the rest of the day.
  - The model was able to predict the days where the price would have been inflated (top 25% most expensive energy), with 100% accuracy thus helping make decisions on a day-to-day basis.
  - From research I founded that the price of a Data Center depends on 4 main factors space, energy to run servers and to cool them, Network connections and technitians.
  - Although price tends to be lower on the summer months (when more energy is needed to cool the data center) the weekly and daily cycles are still present. 
  - Therefor if there were to be increase in price I would recomend creating two different fees : a higher one between 16:00 and 21:00 and a normal fee for the rest of the day.  
  - Also an extra fee for Sundays and Mondays.


## This is the information I had. (and the .csv file) 

## Project Brief

You are working at a data center. One of the biggest costs for the center is the electricity required to run all of the servers. To ensure that they will continue to charge customers appropriately for their services, it’s important for them to be able to estimate the price they will have to pay for running the center - in particular the electricity price. 

As well as knowing whether it is possible to get a reasonable estimate of the price, they would like to know if there are factors that cause the price to increase, so they can charge customers more for those situations.
## **Data**

Dataset containing the price of electricity for a data center in addition to factors that might affect the price.

- DateTime: String, defines date and time of sample
- Holiday: String, gives name of holiday if day is a bank holiday
- HolidayFlag: integer, 1 if day is a bank holiday, zero otherwise
- DayOfWeek: integer (0-6), 0 monday, day of week
- WeekOfYear: integer, running week within year of this date
- Day integer: day of the date
- Month integer: month of the date
- Year integer: year of the date
- PeriodOfDay integer: denotes half hour period of day (0-47)
- ORKTemperature: the actual temperature measured at Cork airport
- ORKWindspeed: the actual windspeed measured at Cork airport
- CO2Intensity: the actual CO2 intensity in (g/kWh) for the electricity produced
- ActualWindProduction: the actual wind energy production for this period
- SystemLoadEP2: the actual national system load for this period
- SMPEP2: the actual price of electricity of this time period, the value to be forecasted

