# NYC CitiBike Analysis

## Overview:

Des Moines has requested data be presented for a business proposal. NYC CitiBike data collected from Aungust 2019 is used to review geographical data and data separated by user types, user genders, and recorded trip duration and usage times. This is compiles and analyzed to help Des Moines determine a good business proposal and investment. 

## Purpose:

*	Import data into Tableau.

*	Create and stylize worksheets, dashboards, and stories in Tableau.

## Tableau Story

[NYC CitiBike Analysis Tableau Story](link)

## Cleaning the Data:

The original CSV file containing the data had the trip duration saved as an integer. This was changed using Jupyter Notebook to make trip duration to a datetime field.

* Intial Datatypes

![initial_datatypes](https://user-images.githubusercontent.com/103263248/184982695-5999184e-01e0-4fb0-9c50-3317d0ffb51c.png)

* New Datatypes

![new_datatypes](https://user-images.githubusercontent.com/103263248/184982778-78a1abd0-8c13-440e-955a-6ed9db8439a5.png)

## Results:

### [Checkout Times for All Users.](link). 

The usage of CitiBikes reaches a peak of approx. 3,000 minutes per user.

![checkout_times](https://user-images.githubusercontent.com/103263248/184982952-fc3f7756-c8c3-4b8e-b215-fe36db9cf928.png)


### [Checkout Times by Gender.](link). 

Looking at checkout times by gender, males are significantly higher users of CitiBike than other listed genders.

![checkout_times_gender](https://user-images.githubusercontent.com/103263248/184982911-3e8c27a3-a5fb-40a2-8e9a-81b025fbd19b.png)


### [Trips by Weekday per Hour.](link)

 Between the hours of 06:00 - 10:00 AM and 05:00 - 08:00 are peak usage hours.
 
![trips_by_weekday_hours](https://user-images.githubusercontent.com/103263248/184983035-45cef880-9eb8-4c62-8678-fc9b7089ef48.png)

### [Trips by Gender (Weekday per Hour).](link)

Based on gender males are the make a high number of users during the peak hours.

![trips_by_gender_weekhours](https://user-images.githubusercontent.com/103263248/184983060-9108a4d4-a4e3-4609-ac82-b72b699a33d3.png)

### [Trips by Gender and User Type (by Weekday).](link)

There is a greater number of male subscribers using the CitiBikes compared to other types of users.

![user_trips_gender_weekday](https://user-images.githubusercontent.com/103263248/184983092-0dfd5df8-ad93-4d21-b99a-7a6a766ed005.png)

### [Starting and Ending Locations.](link)

Looking at the trip starting locations and ending locations there are a higher count of trips starting and ending in lower Manhattan than outer parts of the city.

![starting_ending_locations](https://user-images.githubusercontent.com/103263248/184983138-72f5e61c-14a1-467a-b70c-86598c4608e2.png)

### [Bike Repairs.](link)

Around the hours of 01:00 - 05:00 AM have the least bikes in use, making this the best time to repair the bikes. A third of the Citi Bikes have a high amount of use in them.

![bike_repairs](https://user-images.githubusercontent.com/103263248/184983586-de02fd1a-b5af-47a8-a40a-1c3afba7e4cf.png)

## Summary:

Based on the analysis of the data to keep the NYC CitiBikes operational and well maintained the best time for maintence is between the hours of 01:00 AM to 05:00 AM. This is also a good time to rotate the bikes so that the bike IDs with lower usage can be moved to higher usage areas. This should help the one third of bikes that are being used more often be rotated out for maintence and lower use areas.

Male subscribers are the main users of the NYC CitiBikes and trip duration follows the trends of high use to and from work. This means a large market of the audience is males needing transportation to and from work, and weekend usage. This information can be used to push for additional males subscribing to the services. Consideration of how to market to other demographics and target audiences, for example females, can be applied to create a larger more diverse audience of subscribers and users.

## Additional Analysis:

### * [Customer and Subscriber Locations](link)

Subscribers and Customers are shown as users throughout the city. More customers seem appearing in tourist areas around Central Park and Lower Manhattan, and more subscribers than customers towards the Brooklyn area. Future analysis to include more geographical data to show more trips outside of the main city to see could give more insight into why subscribers are more likely to travel further.

![Customer_subscriber_map](https://user-images.githubusercontent.com/103263248/184983647-67ff04a7-2a1b-4de7-bc1b-ba20f98f86af.png)

### * [Starting and Ending Locations by Gender.](link)

Males are more likes to start and end trips further away from the city than females or unknown genders are. Future analysis to include more geographical data to show how far of trips males are taking outside the city, as well as if there are more areas outside of NYC that females or unknown genders are using.

![location_based_on_gender](https://user-images.githubusercontent.com/103263248/184983966-8d60232d-4191-4e68-8911-1cffad2c0a85.png)
