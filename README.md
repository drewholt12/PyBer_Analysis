# PyBer_Analysis
Ride-Share analysis using python, pandas, matplotlib
# Overview
PyBer, a ride sharing application company, has requested an analysis of ride sharing data by city type.  Using Pandas and Matplotlib, we have created a multiline graph displaying the results of the analysis.  The visualization of the immense amount of data used in this project is necessary to quickly ascertain comparisons between the number of rides, drivers, and fares collected in each city type.  


## Software Used
- Jupyter Notebook
- Python 3.6
- Pandas
- Matplotlib
## Source Data
- city_data.csv
- ride_data.csv
    
    
# Results
The distribution of the number of drivers and the number of rides is consistent with the expected populations of each city type.  Urban areas have higher populations than rural areas and have higher rates of drivers and rides.  The average fare per ride, however, is highest in rural areas and lowest in urban areas.  The average fare per driver has similar results where rural fares per driver were much higher, over 3.5 times higher, than urban areas.  Suburban areas were in between urban and rural areas in all categories.  A summary was created from the source data illustrating these results.


    
    
# Summary
Business Recommendations
1.	 The number of urban drivers is significantly higher than the number of rides.  This results in lower average fares per driver.   With the excess drivers, many may not continue to be available if they are not able to earn income from rides.  Turnover would increase, and overall driver availability would decrease as word spread of the limited income earnings potential.  The result may lead to reduced use of the app in these areas.   More data would be required to identify what part of these cities are seeing higher numbers of rides, what factors could be influencing additional drivers to be working, time of day drivers are available, and duration of a drivers usage of the app. 
2.	The data showing average fare per ride and average fare per driver is skewed.  Due to the limited number of drivers in suburban and rural areas, the average fare per driver is higher than that in urban areas.  A more accurate determination of average fare price is to view the fare price per ride.  Another column could be created if a driver ID is added to the data set to indicate which drivers are working more, or successfully earning more fares than others.  
3.	The number of rides per city type visualization shows some consistency in weekly fares for each city type.  Rural cities tend to be the most consistent each month than urban or suburban.  However, the plot also shows fluctuations between weeks and months.  It could benefit users of the app to have notifications for when additional drivers are necessary based on days, or hours of the day, versus historical rides being taken.  


