We have chosen road accidents in the UK as the topic for our data visualization project. We have found extensive data on this topic published by the UK Department of Transport on the government’s data website: 

https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data

There are three important datasets related to road accidents:

•	the first dataset provides information about all accidents that occurred in the UK. All rows in this dataset correspond to one accident, which is uniquely identified by an accident_id. Columns in this table include information on location (latitude, longitude, district, road), time (date, day of week, time, year), severity, number of vehicles and casualties, type of road, conditions (weather, light, road surface) and many other accident specific attributes.
•	the second dataset provides information about all vehicles involved in the accidents from the first dataset, each row corresponding to one vehicle. Columns in this table include information on vehicle type and other vehicle specific attributes (left vs right hand drive, age, engine capacity), vehicle-accident specific attributes (vehicle manoeuvre, first point of impact), and driver characteristics (age, sex, journey purpose)
•	the third dataset provides information about all casualties involved in the accidents from the first dataset, each row corresponding to a casualty. Columns in this table include information on casualty demographic characteristics, casualty class (driver vs passenger vs pedestrian), severity of injury, etc. 

There are numerous issues and questions that we can address using this dataset. 
Here we provide a non-exhaustive list of issues that we might expand upon after further consideration:

1.	Where car accidents tend to happen more often than not — based on latitude and longitude, road number, district etc.
2.	When accidents tend to happen more often than not — based on date, time, day of week etc.
3.	What factors increase the likelihood and severity of car accidents — based on road type, speed limit, road surface conditions, light and weather conditions, junction or pedestrian crossing proximity, other special conditions at the accident site, driver and vehicle characteristics, number of passengers, etc. 
4.	What trends there are for different types of road users in terms of number of accidents and casualties
5.	Whether road safety campaigns and policies/laws are effective in reducing the frequency or severity of accidents

Apart from exploratory data analysis, the statistical techniques we will most likely use to answer these questions are linear regression. For example, we could use a linear regression model where the number of casualties or the severity of accident is the dependent variable in order to see which are the factors most strongly determine these variables.
