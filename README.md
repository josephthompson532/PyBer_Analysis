# PyBer_Analysis
An Analysis using Pandas, MatPlotLab, NumPy, and SciPy

## Overview 
I created a summary DataFrame of the ride-sharing data along lines of city type (Urban, Suburban, Rural) and then created visualizations of the data. We imported csv files and manipulated the data through pandas to get the data necessary to find metrics relevant to management. For this project, by giving a representation of the weekly fares for each city type, we can get a better sense of the relation between city types and weekly fares. 

### Project Focus
For this project, management requested that we create a multi-line graph showing the total weekly fares for each city type.  

### Dataframe Creation: Filtering the Data
To do this, we first used the groupby() function to get the total number of rides, total number of drivers, and the total fares for each city type. Then, calculate the average fare per ride and average fare per driver for each city type. Finally, add this data to a new DataFrame, then format the columns.

![Screen Shot 2020-08-15 at 2 56 21 PM](https://user-images.githubusercontent.com/66881241/90322338-e9e3b180-df07-11ea-82ea-7f78ee1c39b5.png)


### Visualizations
Here, we used Pandas pivot() and resample() function to create a multiple-line graph that shows the total fares for each week by city type. The groupby() function was used to create multiple indices. The resample() function was used to put the data in weekly bins. 

![Screen Shot 2020-08-15 at 2 56 58 PM](https://user-images.githubusercontent.com/66881241/90322329-cd477980-df07-11ea-9631-1007c00685b8.png)

![Screen Shot 2020-08-15 at 2 56 41 PM](https://user-images.githubusercontent.com/66881241/90322324-be60c700-df07-11ea-8194-d5fb87519662.png)


![Screen Shot 2020-08-15 at 2 54 47 PM](https://user-images.githubusercontent.com/66881241/90322301-9a9d8100-df07-11ea-851d-42f7394e6f2e.png)


## Results

### Summary Dataframe Insights
The summary Dataframe shows that the total rides, total drivers, and total fares are lowest in Rural city types, then Suburban city types, and finally highest in Urban city types. However, the inverse is true with regards to average fare per ride and drivers fare per driver. This suggests that the less rides there are to go around, higher the cost per ride. Conversely, it could just be a reflection of the fact destinations in cities could on average be closer to each other than in Suburban and then Rural environments. However, the lack of total rides seems to be offset by the extreme shortage of drivers, therefore, they still make more money than those in Urban areas.

### Multiple-line Chart
Urban, Suburban, and Rural fares seem to correlate week to week. While they are consistent in their proportionality as reflected in the summary Dataframe.

## Summary
In conclusion, the data visualizations created in this challenge show that there is a large difference in the amount of total fares by city type collected by PyBer ride-sharing. The cost of rides also likely goes up in rural areas as shown in the summary dataframe as compared to both urban and suburban city environments. In order to address disparities between these 3 city types, I recommend first that the CEO find a way to decrease the costs of rides in rural areas. This could increase the total number of rides. The cost of this can be placed on the drivers, who are already making far more than drivers in Suburban and Urban city types. Similarly, the same could be done to Suburban drivers who also make far more than Urban drivers in fare per driver. By leveraging this cost on the drivers, the cost of rides should go down for customers and the populace in these city types may begin to take more rides with PyBer.




>>>>>>> bf81eacfeffc6c88da287f3f94fd6115495fbfdf
