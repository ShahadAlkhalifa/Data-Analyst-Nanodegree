# Ford Gobike Data Exploration
## by Shahad Al-Khalifa


## Dataset

Ford GoBike is a regional public bicycle sharing system in the San Francisco Bay Area, California. The Ford GoBike system, which began operations as Bay Area Bike Share in August 2013, now includes approximately 2,600 bicycles in 262 stations around San Francisco, the East Bay, and San Jose. In a collaboration with Ford Motor Company, the system was formally introduced as Ford GoBike on June 28, 2017.

Ford GoBike, like other bike sharing systems, is made up of a fleet of carefully constructed, strong, and durable bikes that are docked at a network of docking stations located around the city. The bikes may be unlocked at any station in the system and returned to any other station, making them perfect for one-way excursions. The bikes are accessible for use 24 hours a day, seven days a week, 365 days a year, and riders who become members or purchase passes have access to all bikes in the network

The dataset has 183412 bike rides that happened in the San Francisco Bay Area. The dataset has 16 features, some of them are:
- `duration_sec`: The duration of the trip in seconds.
- `start_time` and `end_time` for the bike rides.
- `start_station_name` and `end_station_name`, as well as latitude and longitude.
- `user_type` of either a subscriber or a customer.
- Some information of the members such as their gender and birth year.

After my modifications the dataset has 174880 bike rides and 21 features. The added features are the `age`, `start_date`, `end_date`, `start_day`, and `end_day`, since I want to investigate them further.

## Summary of Findings

> After exploring many factors, we conclude the following:
- The average of trip durations is around 600 seconds i.e. 10 minutes.
- Even though the majority of users are subscribers, customers have longer trip durations that subscribers.
- Most users are aged between 20 and 40 with the average being 33 years old.
- While male users are the majority of users in the system, female users and others have longer trip durations than male users.
- Most users aged between 20 and 40 have trip duartions below 2000 seconds i.e. 33 minutes.
- The highest day of the week for bike rides is Thursday, and the lowest is the weekend (Saturday and Sunday).
- There is a strong relation between the location of the start and end stations.
- There is no clear relation between the trip duration and the location of stations.
- The majority of subscribers and customers take around 5.56 hours of trip durations or less on all weekdays. 
- The most popular day for bike rides for subscribers is Thursday and customers have longer trip durations on Saturday.


## Key Insights for Presentation

For the presentation, We will focus on the duration of trips and how it changes with respect to the user type, age, and gender. Thus, three factor will be investigated the user type (Customer or Subscriber), gender (male, female, or other), and age.