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

![table with summary statistics for June temperatures]

## Summary 
* HIGH LEVEL SUMMARY OF RESULTS
* TWO ADDITIONAL QUERIES TO GATHER MORE WEATHER DATA FOR JUNE AND DECEMBER