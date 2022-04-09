# Surfs_UP

## Overview
To add to the analysis prepared for determining the year-round sustainability of a surf and ice cream shop business in Oahu, a comparison of temperature data for the months of June and December have ben requested. Using Python, Pandas, and SQLAlchemy, the date column of the Measurments table was filtered to retrieve the temperatures for those months. The temperatures were then converted to a list, then a dataframe to generate summary statistics.

## Analysis
![June_Temps](https://user-images.githubusercontent.com/97318406/162591688-346bba8d-9f52-4538-9d42-4626832a8f38.png)
![Dec_Temps](https://user-images.githubusercontent.com/97318406/162591670-9bf03f0d-4e87-433f-9514-b598e559172e.png)

  - June mean temp is higher than Dec mean temp
    - 75 degress vs 71 degrees
  - June min temp is higher than Dec min temp
    - 64 degress vs 56 degrees
  - June max temp is higher than Dec max temp
    - 85 degrees vs 83 degrees
    
## Summary
Despite June having higher temperatures, Dec temperature statistics are only a few degrees lower. With temperatures still reaching 83 degrees in December, a surf and ice cream shop will be attractive to both local customers and travelers. To further validate the results of the data, an analysis to determine how many days in each month a certain reached a mean temp or max temp could be performed to compare the number of expected "busy" days in each month. The additional analysis could also be filtered by days that over a certain temperature, for example, how many days in each month were over 70 degrees as warmer days will generate more interest. 

![June_line](https://user-images.githubusercontent.com/97318406/162592495-190c2591-e6a4-4d16-a9d4-7e808d9e7984.png)
![Dec_line](https://user-images.githubusercontent.com/97318406/162592505-950cad85-279c-4b8d-88a6-d2627820f96b.png)

Precipitation is another factor that will impact the sustainability of the surf and ice cream shop. An analysis could be prepared to compare the two months to determine the more rainy season. Number of days in each month that precipitation was observed could also be calculated and the temperature and precipitation analysis combined for a more informative representation of the weather each day. 

![precipitation](https://user-images.githubusercontent.com/97318406/162592800-021db0ca-1e88-4ed1-a4ad-282fe8581e9d.jpg)

A final step to the analysis could include combining the temperature and precipitation analysis with the station data to represent these results by location. This would help with selection of the optimal location for our surf and ice cream shop. The temperature statistics support the year-round sustainability of this endeavor but adding precipitation and location to our analyis will help to further validate our results.
