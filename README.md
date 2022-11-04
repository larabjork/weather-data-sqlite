# Weather Data Analysis
Data Bootcamp week 9 - SQLite and SQLAlchemy

## Overview of Analysis
This exercise involved a fictious scenario in which an investor is considering supporting a surf shop/ice cream parlor in Hawaii. The investor requested an analysis of weather on the island of "Awahoo". 

The guided homework portion of the exercise involved using SQLALchemy to query an SQLIte database (which was provided). The homework also included an introduction to the Flask framework, specifically creating routes to display information from the SQLite database on a local host.

The independent challenge portion of the exercise involved querying the SQLite database for temperature data in the months of June and December and summarizing it in a Pandas DataFrame.

## Results
As shown in the tables below, Awahoo's temperatures (all given in degrees Fahrenheit) in June and December differ in the following ways:

* The minimum temperature recorded in December is lower than the minimum recorded in June (56 versus 64).
* In June, 75% of the time the temperature is at or above 73 degrees, while in December, the temperature is at or above 74 degrees F only 25% of the time.
* The range in temperatures is greater for December (minimum of 56 and maximum of 83) than for June (minimum of 64 and maximum of 85).

![table with summary statistics for June temperatures](https://github.com/larabjork/weather-data-sqlite/blob/main/Resources/june_temps.png)

![table with summary statistics for December temperatures](https://github.com/larabjork/weather-data-sqlite/blob/main/Resources/dec_temps.png)

## Summary 
### Review of Temperature Data
Not surprisingly, this analysis of temperature data shows that Awahoo's temperatures in June are generally higher than in December. This is especially concerning for potential ice cream sales, although further research into ice cream consumption patterns relative to temperature fluctuations would help refine that statement. As far as the surf shop side of the business, an examination of the water temperatures relative to air temperatures would also be helpful, as well as of surfer behavior relative to these two factors; perhaps it is the water temperature that is more predictive of people's willingness to surf. 

### Additional Considerations
* The available data also includes another important weather condition for both sides of the potential business: precipitation.

