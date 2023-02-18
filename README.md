# PyBer_Analysis

## Overview of Analysis
- Creating a multiple-line graph that shows the total weekly fares for each city type
- Explain how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Purpose

We have been give a new assignment by our boss, to create a DataFrame of the ride-sharing data by city type.
Omar and I will be analyzing the data to see how each community differes in ride-sharing. 

## Analysis

Below you will some of the work we did to get to the results we wanted.



<img src="Resources/Total_and_Average_Chart.png" width=600>

Above you can see the chart that we created after scrubbing the data and cleaning. This chart tells us
a few things.
  1. Rural and suburban areas are more expensive than urban
  2. Urban areas seems to be the area you want to be at if you want thrive in this business.
  
  
<img src="Resources/Merged_Charts.png" width=600>

Here, we ended up merging city and ride csv files. We did this so we can use the pivot function to create
a new table and then using this new table to create the next dataframe which involved using the resample
function. The end results is this multi-line graph that you'll see below which shows us a timeline; we'll 
get more into this in the results section of this analysis.

## Results
<img src="Resources/Multi_line_Graph.png" width=600>
