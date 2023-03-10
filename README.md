# bikes-analysis-project 

## Problem Statement:
### About the System:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

### Their reasons for approaching us:
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
How have they collected data?
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

#  The Business Problem
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


# Features 
* datetime : date and time 
* season :  There are 4 categories
Spring ,Summer ,Fall, Winter        
* holiday: Weather the day is a holiday.
0 : Not a Holiday
1 : Holiday           
* workingday: If the day is working.
0 : Neither weekend nor holiday
1 : Not a working day        
* weather  The weather on that particular day
1 : Clear, Few clouds, Partly cloudy, Partly cloudy
2 : Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3 : Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4 : Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog           
* temp: Temperature in Celsius              
* humidity : (in Percentage)          
* windspeed : wind speed 
* casual: Count of casual users. Casual users are users who use the service occasionally or don't have a subscription to the service.            
*registered: Count of registered users. Registered users are those who register for an annual or 30-day membership and rent more frequently        
* rented_bikes_count 
* Profit   
