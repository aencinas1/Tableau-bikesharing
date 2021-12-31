# An Analysis of Bike Sharing and its Expansion to Des Moines

## Overview
In this challenge, we dive a bit further into CitiBike data, creating visualization that help us better understand CitiBike usage and how it would translate to a new market. After converting the trip duration of rides to a more digestable minutes format, our visualization told a more compelling story of usage.

## Results
Please click the link below to view the visualization that I'll be explaining.

[Link to Tableau Dashboard](https://public.tableau.com/app/profile/andres.encinas)

After converting out data to datetime format to get minutes, I began further visualization.

![](Images/checkouttimesforusers.png)
First, we took a look at the trip duration of user trips, based off the start time. From this, we can see peak usage is met at the 5 hour mark. We also see that there is a rapid increase in usage from hours 1-4. There is a slow decline in usage from hour 5.


![](Images/checkouttimesbygender.png)
We then further filtered this data to show us usage by gender.We can begin to see that more males use citibike than other genders. The same findings from before apply here as well.


![](Images/tripsbyweekday.png)
Here, we visualize usage per weekday, where yellow is less usage and red is more. We can see peak usage Mon-Wed to be 7am-9am and 5pm-7pm. We also see higher usage on Friday 12pm-8pm and Saturday/Sunday 10am-8pm, possibly due to people participating in activities over weekend hours.


![](Images/tripsbygenderandweekday.png)
This breaks down the last visualization by gender. Again, we can see that each gender follows similar usage trends, but there are significantly more male users.

![](Images/usertripsbygenderandweekday.png)
Finally, we can see a breakdown of usage by weekday, filtered by gender and whether or not the user is a subscriber. We can see, again, a higher male usage. For non subscribers, Unknown gender makes up most usage, while for subscribers, it makes up the least.

## Summary
The most interesting, and useful, find is the realization that the majority of customers are male. This is useful because we can infer that males would continue to be the majority of customers in a new market. Using cencus data, we could easily look to see if Des Moines has more males or females. Depending on how many males are in Des Moines, we would have a good estimate on whether or not CitiBike would be successful there. Not dependent on gender, Des Moines also has workers that commute to work. Having a alternative to driving could be appealing to locals, including younger people such as university students. Another thing to consider is that Iowa has similar weather to New York, meaning that we can expect weather to impact both markets similarly.

To further explore some of these implications, I would suggest the following visualization be put together:
1. I would take a look at usage by weekday, filtered by gender AND age. Age is a critical component to understanding who is utilizing the CitiBike service. If we had a breakdown of usage by age, we could directly compare that demographic to Des Moines.
2. I would also take a look at usage per month. Des Moines is not nearly the size of New York, so investors will need a crystal clear understanding of when bikes are being used. If December-March sees hardly any use, they should be prepared to limit the number of bikes in the city, or to temporarily relocate bikes for those months.


