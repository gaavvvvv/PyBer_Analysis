# PyBer_Analysis
## Overview
- The purpose of this analysis is to show the weekly total fares by city type and and to make recommendations on where Pyber can improve. 
- For deliverable 1 we merged the city data and the ride data data frames, making the pyber data frame. We then use the pyber data frame to pull totals such as rides by type, drivers by type, total fares and more, and we also create other data frames from this "mother" data frame. Once we pulled our totals, we create a new and formmated data frame, "Pyber_summary_df". 
- For deliverable 2 we merge our newly created "Pyber_summary_df" with the city data and ride data data frames into another new data frame - one centered around the dates of the rides. We eventually want to get fares by week, so we format the data frame making the index the dates (by week, )the columns are types (rural, urban, suburban) and the values are the fare amounts (USD$). Once the new data frame is cleaned, we plot and visualize the data.
## Results
- Unsurprisingly, the total rural fares and total rides are the lowest of the three (rural areas have less rides and drivers), followed by suburban and then the most is of course urban. The totals follow a similar pattern, though. Looking at the chart, at the end of February fares in all three city types hit their respective peaks. 
- Total rural fares per week pretty much never crossed the 500$ mark
- Total suburban fares stay pretty consistantly above 1000$, although there were some weeks where it dipped below
- Total urban fares are for the most part above the 2000$ mark
## Summary
- Recommendations for decision makers at Pyber
  - focus on urban and suburban riders and drivers, that's where your money is at
  - figure out what is happening at the end of February and see if you can replicate whatever is happening then since that's when total fares across the three city types is at its peak
  - figure out whats causing the rise and fall that occurs in urban cities so there is more consistant ridership and fares
