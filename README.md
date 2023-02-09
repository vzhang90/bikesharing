# Bikesharing Trip Analsis Tableau Story Visualization
[Bikesharing Trip Analysis Tableau Public Story](https://public.tableau.com/app/profile/vincent.zhang3409/viz/BikesharingTripAnalysis/TripAnalysis?publish=yes)

## Overview of Trip Analysis
From Tableau, a set of visualizations were created to present New York City's Citibike in the month of August for bikesharing trip analysis.
- After reading the csv file from the <code>201908-citibike-tripdata.csv.zip</code> of the [Citi Bike System Data Page](https://www.citibikenyc.com/system-data), a dataframe created with Pandas changed the "tripduration" column from an integer to a datetime datatype
   - This DataFrame was exported as a new csv file without the index colum
- Utilizing this new csv file processed from the mentioned code above in the [NYC_CitiBike_Challenge](https://github.com/vzhang90/bikesharing/blob/main/NYC_CitiBike_Challenge.ipynb), a [Bike Trip Analysis story](https://public.tableau.com/app/profile/vincent.zhang3409/viz/BikesharingTripAnalysis/TripAnalysis?publish=yes) was created in [Tableau](https://public.tableau.com/app/profile/vincent.zhang3409/viz/BikesharingTripAnalysis/TripAnalysis?publish=yes) with graphical representations that are presented in an ordered fashion to help discern overall sentiment and marginal benefits based on cohorts with subsequent additional filters to expand upon certain visualizations


## Results
This tableau story conveys 8 visualiations to help demonstrate bike trip analysis for a pitch to convince investors that a bike-sharing program in Des Moines is a solid business proposal.  

  
Respective to the order of captions within this [Tableau story for Bikesharing trip analysis](https://public.tableau.com/app/profile/vincent.zhang3409/viz/BikesharingTripAnalysis/TripAnalysis?publish=yes) in accordance with worksheet visualizations presented in the story:
>*visualizations not displayed in this README.md file because of clutter, please use [Tableau story visualizations](https://public.tableau.com/app/profile/vincent.zhang3409/viz/BikesharingTripAnalysis/TripAnalysis?publish=yes) alongside*

1) **Checkout Time for all Users**
   - Line graph displaying number of bikes checked out by duration for all users
   - Line graph  can be filtered by the hour
2) **Checkout Times by Gender**
   - Line graph additionally displaying the number of bikes that are checked out by duration for each gender by the hour
   - Line graph can be filtered by the hour and gender
3) **Trips by weekday for each Hour**
   - Heatmpap created showing the number of bike trips for each hour of each day of the week
4) **Gender Breakdown**
   - Pie Chart displaying trip analysis by only gender cohorts 
5) **Trips by Gender (Weekday per Hour)
   - Heatmap created additionally showing the number of bike trips by gender for each hour of each day of the week
   - Heatmap can be filtered by gender
6) **Customers
   - Pie Chart displaying trip analysis by only customer cohorts
7) **User Trips by Gender by Weekday
   - Heatmap further generated to show the number of bike trips for each type of user & gender for each day of the week
   - Heatmap can only filter by user & gender
8) **August Peak Hours
    - Horiozontal Bar Chart displaying August Peak Hours of NYC's CitiBike sharing
  
## Summary
The provided visualizations show a direct positive correlation in number of bikes checked-out with male genders who are subscribers averaging 6 minutes trip duration during weekday work-related morning and afternoon rushours (around 7am to 8am as well as 5pm to 6pm peak).

This trip analysis can be further investiaged with tableau visualizations if graphically representing 1) the trip distance and duration filtered based on age as well as gender and 2) displaying additional line graph with the same metrics as above created heatmaps to picture the quantitative relative differences easier.
