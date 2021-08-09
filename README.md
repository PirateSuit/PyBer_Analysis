# PyBer_Analysis

## Overview

### The purpose of this analysis was to create a summary of ride information and to output a line graph that compares fares for each city type.

## Results

Taking the ride and city data given, I put them into a dataframe and then organized and cleaned the data until I got a dataframe of fares per week by city type. 

Here it is:
![image](https://github.com/PirateSuit/PyBer_Analysis/blob/main/analysis/resampled_weekly_fare_df.png)

I then took that data and put it into a line plot.

The plot:

![image](https://github.com/PirateSuit/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary

On the surface, what we see is clear: Urban cities bring in more fares than suburban ones, and the rural cities bring in fewer fares than either of those. This isn't surprising. A higher population and density means more people taking rides.

But looking at this summary dataframe that was created during the analysis, we can glean some other information.

![image](https://github.com/PirateSuit/PyBer_Analysis/blob/main/analysis/pyber_summary.png)

The less dense the city type, the higher the fare per ride and fare per driver. We could assume that with less density comes a longer ride, but this dataset did not include the length of the ride and so we can't be sure. Doing a deeper analysis with more information could be useful.

We could also look into the rural city types to see whether or not a higher number of drivers could yield more business. 


