# Bikesharing

## Overview 

Analyze bikeshare data from CitiBike in New York City and show future investors that a bikeshare program in Des Moines Iowa can be a profitable business. Before that we need to look into the data number of short-term customers and annual subscribers to the Citi Bike service. This will help us determine the types of customers we could expect for a bike-sharing company in Des Moines. Specifically, you want to find out how the proportion of short-term customers to annual subscribers has changed. This analysis might help answer a few more key questions:

Who uses bikeshare programs?
How long bikes are checked out for all riders and genders?
How many trips are taken by the hour for each day of the week, for all riders and genders?
How much are the bikes used and by whom?
What days of the week a user might be more likely to check out a bike, by type of user and gender?

Analytic Tools;

- Tableau Platform for data visualization
- Pandas to manipulate data tripduration


[Link to CitiBike Trip Analyisis Tableau Story](https://public.tableau.com/app/profile/ninotshka/viz/CitiBikeTripAnalysis_16683913534820/CitiBikeTripAnalysis)

## Results:

> Graph Line the with length of time that bikes are checked out for all riders. 146,752 users tripduration was 5 minutes and start declining through 60 minutes.

<img src=https://user-images.githubusercontent.com/110786136/202327749-59455676-52ac-42de-b126-f9d30cb42845.png width=50% height=25%>


> Multiple graph Line with the length of time that bikes are checked out for each gender.
<img src=https://user-images.githubusercontent.com/110786136/202327756-a4f1f4b5-122f-4804-869a-6d36940816ed.png width=50% height=25%>


> Heatmap the number of bike trips by weekday for each hour of the day.
<img src=https://user-images.githubusercontent.com/110786136/202327768-66075de3-5ba7-4f51-b14d-62e3e8a9e66f.png width=50% height=25%>


> Heatmap the number of bike trips by gender for each hour of each day of the week.
<img src=https://user-images.githubusercontent.com/110786136/202327779-8734b06a-3680-4acc-b1f7-9298d9aa239c.png width=50% height=25%>

> Heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype.
![image 5](https://user-images.githubusercontent.com/110786136/202327786-3a805d41-6ccb-4e73-b99f-c26e965aaabf.png)



## Summary:
We can conclude that Males tend to be a heavy user . Most of users tripduration is five minutes with a 146,752 trip total. User more active hours during the week is from 5:00pm to 6:00pm.

Below analysis should be included to identify posible bikeshare station location and understand trends between customers and subscribers for the bottom start station. 


> Determine whether or not the 10 bottom start station usertype have a relationship or correlation 
<img src=https://user-images.githubusercontent.com/110786136/202327978-a57d0f73-7f54-4cc0-aeac-cf1668b95236.png width=50% height=25%>


> A customer’s location can help you better understand customer needs and enable us to establish location-specific bikeshare station .This analysis shows the income of the bottom users station and help us to determinate what neighborhood we need to focus base on county Per Capita Income and locations that we may need to avoid. 

<img src=https://user-images.githubusercontent.com/110786136/202327988-72f95ff8-cc3d-4c4f-9fe0-cf8e9bc11d91.png width=50% height=25%>


