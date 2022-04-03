# PyBer_Analysis
## Overview
This project is an analysis of Pyber ride data. Pyber, a personal transportation company similar to Uber, is interested in a breakdown and visualization of their ride data. Pyber is interested in seeing their fares and driver data broken down by city population types rural, suburban and urban. The purpose of this project is to generate such analysis and data visualization with matplotlib's pyplot in a jupyter notebook.  
## Results
![](Analysis/summary_df.png)
* In the figure above we find that total the most total rides in urban areas and the least in rural areas
* We find the most drivers in urban areas and the least drivers in rural areas
* We find the greatest total fares in urban areas and the least in rural areas
* Conversely, we find the greatest average fare per ride in rural areas and the least in urban areas
* We find the greatest average fare per driver in rural areas and the least in urban areas
![](Analysis/fares_by_city.png)
* In the figure above, we take note of similar trends in fares by living areas from 01-01-2019 through 04-28-2019.
  * More notably, we find similar trends between suburban and rural living areas
* The vertical displacement of each line depicts the greater total fares in urban than suburban than rural living areas noted above
## Summary
Both suburban and rural areas have more total rides called than drivers available, while urban areas have greater drivers than total rides called- this could be the cause of the disparity in lower average fare per driver in urban areas. In order to increase the average fare per driver in urban areas so Pyber drivers earn more, Pyber could advertise more in these areas or offer occasional reduced costs for urban Pyber users in an attempt to increase the number of rides called in urban areas. 
Alternatively, the average fare per ride is $10 less in urban areas than rural areas. Increasing costs of rides during particular traffic hours and holidays could help reduce that disparity, and provide incentive for Pyber drivers to be active during such hours, with the opportunity for greater average fare per driver.
Significant drops and peaks occur from January through April in the number of rides called by Pyber users. In order to reduce drops to better maintain more consistent rides called by Pyber users for Pyber drivers, Pyber could provide incentives to Pyber users to call rides during drops in Pyber rides called.
