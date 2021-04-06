# PyBer_Analysis

Overview:

Analyze ride share data set via Python and pyhon libaries, Pandas and Matplotlib.

Purpose:

The purpose of this project was to analyze PyBer ride sharing data. Analysis was done by Python Pandas library which helped process a large data set. The analsis was then made in to easy to follow visuals by Matplotlib.

There was quite a few data series to work with to make the data frame from. City type was choosen to make the frame off of. So the data could be grouped by 3 main categories, Rural, Suburban and Urban city type. There were 2 sets of data to merge, the first set was for the calender year while the other set tracked data by city type and classified cities by a certain classification. The data frame was made in accordance with that classification in mind.

Analysis:

The city data showed some expected trends based on the classification of city types. Urban areas for instance were 3.5 time represented than rurals ones and when urban was compared to suburban areas urban cities were almost represented 2 to 1. Rural areas had a higher average fare with regards to per driver and driver average. This is expected as rural areas would have less available drivers due less of a demand for ride sharing leading to a higher cost for the rider. Urban and surban areas these avaergaes were lower with Urban being the lowest in fare by driver, this can be expalined by the law of averages and if the same number of rides were given in subarban it is likely one would see a converagness of this trend on the suburban type with a big enough sample size. Urban areas veing more populate this area had more drivers and more number of rides given. This no doubt drove the trend of urban rides being given 2.5 more than a suburban ridge and almost 5 times as many available drivers compared to suburban available drivers. 



Looking to the figure below, fare by city type in 2019 shows that urban areas have a much high revenue compared to rural with subarban being in the middle of the two classes. There is no intersection being any of the trends based on the given data set based on any of the classification such as driver, fare average or total rides given.



Challenges:
The data set itself presented no challenges as the data was fairly cleaning and any null values(Nan) were removed. The only challenege personally faced were more hardward issues as the pathway for python had to be reset in order to load the data. 

Summary:
Based on the anlaysis of this data set a few recommendation can be made to address the imbalance between the types of classes.

1. If the distance for the rides are tracked then the rides with the same distances should be compared along class to determine if the imbalance between classes exists based on the ride and its associated actions or if the imbalance is based on volume of rides. Drill down further on the set will provide a clearer and more object view of the business process.

2. The urban areas should be further analyzed to remove high volume area such as downtown and area with shorter trips to try and normalize rider travel distance and remove outliers from the higha nd low end of the spectrum. This drill down will also impact average cost of fare and average fare per driver as some drivers may only work certain areas like downtown or areas where passengers may constantly be needing a ride like a steet of bars and clubs. 

3. The data should also be intersected with any events going on in the respective areas, conventions, concerts and such will naturally slant towards the urban areas. many rural and suburban areas will not have these events and removing these events form the data series gives a better comparision of apples to apples as opposed to apples and fruits. 
