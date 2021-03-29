# Introduction
[Bey Wheels](https://en.wikipedia.org/wiki/Bay_Wheels) is a regional public bicycle sharing system in California's San Francisco Bay Area. It is operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. The system was initially launched as Bay Area Bike Share in August 2013. At launch, it became the first regional bicycle sharing system deployed on the West Coast of the United States and also the first regional system in the U.S. that services more than just a single city or adjacent cities.
In June 2017, the system was officially relaunched as Ford GoBike in a partnership with [Ford Motor Company](https://en.wikipedia.org/wiki/Ford_Motor_Company).

# fordgobike-system-data
Ford GoBike system Data Analysis and Exploration
This was one of the projects I worked at as part of Udacity Data Analyst Nanodegree Course. I have used Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships.

# Summary of Findings
1. Average trip times
2. Monthly bike ride trend and average trip times
3. Average trip times by gender.


I started my analysis by looking at the structure of the dataset.The main area of interest was what are the factors influencing the trip duration.

This dataset is from the Ford GoBike System data (a bike rental company), with 5054 bikes in this dataset with 1,863,721 rows and 12 features.

Data wrangling for this dataset consisted of converting the data files, combining the 12 months worth of datasets into 1 annual dataset and dropping several of the unnecessary columns that would not be used in the data analysis.

In the exploration, I found there was a trend between number of trips and average trip duration coming to just under 10 minutes, with some trips going up to 300 minutes and more! I found there was a surprisingly consistent minimum of bike trips throughout the year, never dropping under 200 minutes. June and July had the longest trips during those months, and January and December had fewer trips that lasted as long, however the shorted trips were consisted year long. When adding the gender variable we found female users had shorted bike trips than men consistently year long, but in June July and August, the female users bike times did increase. Male users bike times were consistently longer than women throughout the year, averaging above 400 minutes.
