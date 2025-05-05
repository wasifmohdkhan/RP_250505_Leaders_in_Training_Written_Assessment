# RP_250505_Leaders_in_Training_Written_Assessment

RP_250505_Leaders_in_Training_Written_Assessment

Steps:

1.  Create a new directory "Data" to download the data using web address

    1.  The HTTP address did not work, so downloaded the data manually

2.  Download tidyverse

3.  To answer Question 1, I used a heatmap for selected entries between permits and inspections
    
    Conclusion:
    1. The frequency of issued permit was higher than ohter types of permits
    2. Among the issued permits, highest were either approved, inspection scheduled, or got partial approval after inspection

4.  To answer Question 2.1,
    1.  First, I combined the two datasets to get the information on city, permits and inspections
    2.  I used a table and a bar plot to show the number of inspections per city (geographic area)
    3.  I used a table and a bar plot to show the number of inspections per zone (considered as geographic area)
    
    Conclusion:
    1. The highest number of inspections happened in the Los Angeles city followed by San pedro.
    2 There was a very high frequency of inspections resulted in Unknown status.
    3. The results were not very meaningful when used the zone codes to make the same table and the plot.
    
5.  To answer Question 2.2,
    1.  I used a table and a bar plot to show the number of inspections per city (geographic area)
    2.  I used a table and a bar plot to show the number of inspections per zone (considered as geographic area)
    
    Conclusion:
    1.  Most of the inspections were Approved in the Los Angeles city, with partial approval and scheduled inspection flollowing that.
    2. Since the number varies a lot between the cities, I realize that a better approach to see this graph would be to use the rate of different types of inspections per city or zone rather than actual values. 
    
6 To answer Question 3,
    1. Converted contractors to a factor based on city or outside the city of Los Angeles
    2. The the success of the inspection was based on the the outcome was determined and converted to a factor 0 and 1
    3. A chi square test was applied to check if there is a significant difference between the outcome of the contractors based on the city or outside the city of Los Angeles
    
    Conclusion:
    1. The chi square test showed that there is a significant difference (p-value < 2.2e-16) between the outcome of the contractors based on the city or outside the city of Los Angeles. which means that the success rate of inspections of contractors in the city of Los Angeles is significantly hihger from those outside the city. However, to firmly conclude this we need to have a second look at the data conversion to define what consitutes a success and what does not.
    

What addional analysis could be done if more time was available?
    I could have mapped the number of inspections on to the map using latitude and longitude