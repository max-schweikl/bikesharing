# bikesharing

## Overview

CitiBike is a long-standing program in New York City, but analysts are looking at the possibility of rolling out this program to other cities, specifically Des Moines, IA.  The data shown here in particular is for August 2019 usage, and many trends were presented, specifically the checkout time for users, checkout times by gender, trips by day of week, trips by gender (shown broken down by hour), user trips by gender and day of week for both customers and subscribers, and then finally the most popular starting and ending locations.  Through this data, we look to draw conclusions on how to best implement CitiBike deployment to Des Moines, IA, in addition to some extra recommendations on what to research further.

## Results

### Link to Tableau Dashboard
[NYC CitiBike Challenge](https://public.tableau.com/app/profile/max.schweikl/viz/NYC_CitiBike_Challenge_16486689002250/CheckoutTimesforUsers)

### Checkout Times for Users

In August 2019, there were 146,752 bikes that were registered checked out at the 5 minute duration mark.  This represents the highest usage peak.  Looking more at longevity stats, there were 33 bikes that were checked out for 2 hours, 59 minutes or potentially longer.

![](Resources/Checkout_Times_For_Users.png

### Checkout Times by Gender

When looking at bike usage by gender, males came in much higher than female, at close to 110k male users at the peak usage time, compared to ~34k female users at the peak.  There was also some unkonwn gender data within the CitiBike data.

![](Resources/Checkout_Times_By_Gender.png

### Trips by Weekday

Citibike usage was at the lowest between 12am-5am on all days of the week, while the most popular trip period was around 5pm-6pm on Monday, Tuesday and Thursday.

![](Resources/Trips_By_Weekday.png

### Trips by Gender (Weekday per Hour)

When looking at both female and male, both genders utilize CitiBike the most from 5pm-6om on Monday, Tuesday and Thursday, in addition to 8am on just weekday mornings.

![](Resources/Trips_By_Gender_Weekday.png

### User Trips by Gender by Weekday

For customers, weekends tend to be a bit more popular than weekdays, while for subscribers weekdays tend to be more popular than weekends, with Thursday being the most popular day of the week, predominantly being male subscribers on those days.

![](Resources/Trips_By_Gender_Subscription.png

### Top Starting Locations

The most popular starting locations for CitiBike users were Grand Central Station, Union Square/Union Square Station and Washington Market Park/Rockefeller Park Water Ferry Terminal.  From first glance, it appears the type of destination that a CitiBike user was checking a bike out was a transportation hub.

![](Resources/Top_Starting_Locations.png

### Top Ending Locations

Interestingly enough, CitiBike users destinations were the same as the top starting locations: Grand Central Station, Union Square/Union Square Station and Washington Market Park/Rockefeller Park Water Ferry Terminal.  Again, similar to the above, CitiBike users were taking the bikes to destinations that appear to be a transportation hub.

![](Resources/Top_Ending_Locations.png

## Summary

### High-Level Results

When looking at the August 2019 data for CitiBike, there's a few major conclusions that can be drawn: 1) gender usage data shows us that the majority of users are male over female, 2) weekdays are more popular for usage versus weekends, with Thursday being the most popular day of the week, 3) early morning and early evening are the most popular usage times of day, likely aligning with the commute schedule of many NYC workers, as the trip start/end data reveals that most bikes are originating and ending in the same locations.

### Future Visualization Recommendations

When looking at introducing CitiBike to Des Moines, there's a few factors that should be considered.  The first is the vast population differences between the two cities - what is the ideal bike per capita needed to ensure there's not too few or too many bikes in supply for Des Moines.  We should also look at weather patterns for Des Moines compared to New York City.  This data was looking at the month of August in this analysis, but what is December climate in New York compared to Iowa - can we expect usage rates to be similar if the weather patterns are starkly similar or different?  One last thing to consider is the ease of access for bike-friendly roads or lanes in each city.  Does Des Moines have more or less of what is considered "bike-friendly" access routes than New York?  What about origins and destinations that will be most popular?  Do we expect average ride length to be shorter or longer when looking at how spread out popular attractions or places of work to home are in Des Moines compared to New York City?
