# bikesharing


## Overview
### Purpose
- Get familiar with manipulating data with Tableau.
- Present data visualizations in Tableau and appropriate analysis and explanations.
- Review Pandas (Python) knowledge of data cleaning.
- Create a report to convince investors that a bike-sharing program in Des Moines is a solid business proposal.

### Resources
- Languages: Python
- Interface: Tableau Public, Jupyter Notebook
- Environment: Miniconda
- Packages and Software: Pandas
- Data Source: [City Bike Trip Histories](https://ride.citibikenyc.com/system-data), August 2019

## Results

### [Online Tableau Dashboard](https://public.tableau.com/app/profile/emily8604/viz/AugustCitiBikeAnalysis/AugustPeakHours)
### August Peak Hours
![August Peak Hours](https://raw.githubusercontent.com/li-emily/bikesharing/images/august_peak_hours.png)

From this bar graph showing the peak hours of Citi Bike usage, we can see that the most busy times are 7 am to 8 am, and 4 pm to 7 pm.
### Gender Breakdown
![Gender Breakdown](https://raw.githubusercontent.com/li-emily/bikesharing/images/gender_breakdown.png)

The gender demographics of Citi Bike users are overwhelmingly male, with almost 3x the amount as female riders. However, we do not know around 10% of the users' gender.
### Checkout Times for Users
![Checkout Times for Users](https://raw.githubusercontent.com/li-emily/bikesharing/images/checkout_times.png)

The peak on this graph shows that most riders use Citi Bikes for about 5 minutes. The majority also ride for under an hour. 
### Checkout Times by Gender
![Checkout Times by Gender](https://raw.githubusercontent.com/li-emily/bikesharing/images/checkout_time_gender.png)

Gender breakdown is an additional lens to see the peak time duration that each gender uses the bikes for. Male and female riders have similar time usages, while gender unknown riders have a mound instead of a peak. Most still remained under an hour.
### Trips by Weekday for Each Hour
![Trips by Weekday for Each Hour](https://raw.githubusercontent.com/li-emily/bikesharing/images/trips_weekday.png)

Trips peak at rush hours on weekdays and during daylight for weekends, possibly because they may be used more for pleasure. 
### Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](https://raw.githubusercontent.com/li-emily/bikesharing/images/trips_weekday_gender.png)

Peak hours show similar concentrations to previous gender breakdowns and trips by the day of the week graph.
### User Trips by Gender by Weekday
![User Trips by Gender by Weekday](https://raw.githubusercontent.com/li-emily/bikesharing/images/user_trips_weekday_gender.png)

There are two user types at the moment: customers (pay to for each use) and subscribers (pay subscription fee based on time period). We can see that users are much more likely to be subscribers.
## Summary
With all of these data visualizations, we are able to grab a decently accurate picture of Citi Bike demographics and usage times. This helps us determine the user base, which can also become the basis for pricing. Usage times can be taken into account for maintenance. We decide to look a bit further.

### User Trip Duration by Weekday
![User Trip Duration by Weekday](https://raw.githubusercontent.com/li-emily/bikesharing/images/user_trip_duration_weekday.png)

Based on this graph, we can see that subscriber usage peaks mostly on weekdays, while customer usage peaks on weekends.
### User Ending Locations
![User Ending Locations](https://raw.githubusercontent.com/li-emily/bikesharing/images/user_ending_locations.png)

With this map, we can see that overall, most ending locations are dominated by subscribers. However, around the parks and waterfront, customers actually come close to or surpass subscriber usage. Thus, it seems that they are more likely to be tourists looking at attractions in NYC.

