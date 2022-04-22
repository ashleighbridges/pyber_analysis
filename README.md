# pyber_analysis

## Overview
This analysis was initially conducted for PyBer to find any trends or relationships between city types, fare amounts, ride counts, and driver counts. I created DataFrames and charts out of raw city and ride data provided by the company, which I then put together into a presentation for the CEO, V. Isualize. After the presentation, V. asked for further analysis and a chart to see the trends for weekly fares by city type for a four-month period.

## Results
The following DataFrame was created from our previous analysis to see the disparities between the city types:

![PyBer_fare_summary_df](https://user-images.githubusercontent.com/100883212/164583053-4213f306-dc04-41e9-9c71-a6d27153d202.png)

My first observation was that unsurprisingly, the Urban cities held the largest numbers for Total Rides, Total Drivers, and Total Fares. This is logical due to the higher populations in urban environments. People are also less likely to own a car in an Urban city, since they are usually more accessible by walking or public transit. I also was not surprised to see that the Average Fare per Ride was highest for the Rural communities. These environments are usually far more spread out and have little to no public transit options, therfore the vast majority of residents own vehicles. I was somewhat surprised to see that the Average Fare per Driver was almost $40 higher in Rural communities than it was in Urban cities. However, this makes sense given there are 2,327 more drivers in the Urban environments than the Rural ones.

I also created a line chart comparing the total weekly fares by city type over the span of almost four months. While the Rural communities have higher Average Fares per Ride and Driver, the Urban cities far exceeded them in Total Weekly Fares, with the Suburban towns falling almost directly in the middle.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100883212/164582573-a86d68b3-b897-484d-a04c-edfce1e3df66.png)

## Summary
After a thorough analysis of the PyBer city and ride data, I have a few recommendations for addressing disparities among the city types:
- I would recommend collecting mileage data to add to the current metrics. The higher fares in Rural communities is likely due to longer rides taken there than in the Suburban and Urban communities. Having mileage data would allow for us to see if there are ways we could possibly increase the distance of rides across all city types, such as offering airport transfer services to outlying communities.
- Since Urban communities have the highest number of drivers and rides by far and create the majority of PyBer's revenue, we should continue investing the current Urban cities we service, as well as looking into other Urban cities to expand to.
- We should also consider redirecting a portion of the marketing budget dedicated to recruiting new drivers in Urban cities to instead attempt to increase ridership. Because the Average Fare per Driver is low in the Urban cities, we are at risk of high turnover rates for drivers there.
