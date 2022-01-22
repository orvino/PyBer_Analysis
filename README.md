# PyBer_Analysis_Challenge

## Challenge Overview
After completing an exploratory analysis for PyBer, a ride-sharing business, a deeper dive into reviewing the data by city type was requested by the CEO. The scope of work includes using Python, Pandas, and Matplotlb to create a summary DataFrame and a multi-line graph of the total weekly fares for each city type: Rural, Suburban, and Urban.

## Resources
- Data Sources: city_data.csv, ride_data.csv
- Software: Python 3.8.8, Visual Studio Code 1.63.2, Jupyter Notebook 6.3.0, Pandas 1.3.3, Matplotlib 3.3.4, Pandas 1.2.4, Numpy 1.20.1

## Results

### Differences between the different city types
total rides, total dirvers, total fare, avg far per ride and dirver and total bare by thype

<img width="828" alt="Screen Shot 2022-01-22 at 10 11 45 AM" src="https://user-images.githubusercontent.com/91889241/150646631-d0b4f47b-9419-42a0-b3d6-f3b8240f7823.png">

  1. The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver. The Urban drivers had the lowest average fare per ride and earned significantly less than the Rural drivers.

  2. The Rural city type had the least number of total drivers giving way to having the highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type.

### Total Fare by City Type
From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks to show the total fares by city type.

<img width="826" alt="Screen Shot 2022-01-22 at 10 14 22 AM" src="https://user-images.githubusercontent.com/91889241/150646669-4b089120-7369-4ac2-bd4a-169c2eeb0219.png">

  1. All three city types start to rise to a peak at the end for February. For the Urban city type, that oscillating peak lasts through April, while the other city types wane in the month of March.

  2. The Rural city type increases again leading into the month of April. The Suburban city type starts to peak again at the end of April, while the Rural city type drops off.

## Summary and Recommendations:
The results of the summary DataFrame could be due to Urban city types being more compact, which collects a lower average fare per ride, while Rural city types are more spread out, which would collect a higher average fare per ride. To test this theory, PyBer should work to include mileage distance data as part of the data collection process and analysis.

Because there are more total drivers than total rides in the Urban city types, the Urban drivers may not have enough work to support themselves. PyBer may want to consider investing advertising dollars in the Urban city types to increase the total rides or risk losing Urban drivers.

If PyBer were to invest into advertising dollars in the Urban city type, the next question is when would ads be the most effective? After reviewing the Total Fare by City Tpye graph, the end of February kicks off the increase in total fares and would be a good time to launch an advertising campaign, which would also strategically help the other two city types.

