# sqlalchemy-Challenge

Congratulations! 
You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii! To help with your trip planning, you need to do some climate analysis on the area.

First, you decided to analyze the last 12 months of data. August, did you say? Not a great period to go to Hawaii. Precipitations are possible and more relevant compared to other months, also the STD in 2016 tells that there is a lot of variability in that period.  
Althought we have to say that the data is complete for August 2016, not so much exhaustive for 2017 to make a truthful comparison.

![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Precipitations%20over%2012-month%20period.png)

![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Precipitations%20over%2012%20months%20period_Summary%20Statistics.png)

Analyzing the temperature of Hawaii, plotting a boxplot allows to have an understanding of the distribution of the datapoints of all weather stations and determine if there are any potential outliers visually.
There are multiple potential outliers in the temperature datapoints that could skew data analysis and further investigations should be done.

Hawaii is reputed to enjoy mild weather all year. Is there a meaningful difference between the temperature in, for example, June and December?
I decide to run a statistical un-paired test between June and December data. If the pvalue is smaller 0.05, like here, we can reject the null hypothesis and say there is a statistical meaninful high difference between these groups. 

Other specific plots are below:

- A plot comprising the min, avg, and max temperature from first days of August as a bar chart.
![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Temperatures%20over%20a%2012-month%20period.png)


![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Temperature%20over%2012-month%20period%2C%20station%20USC00519281.png)



![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Trip%20Average%20Temp.png)


![Summary Statistics](https://github.com/AliceSartori/sqlalchemy/blob/main/Predicted%20Temperatures%20for%20Historical%20Temperature%20-%20Hawaii.png)

