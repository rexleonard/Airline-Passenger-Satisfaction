# (Airline Passenger Satisfaction Exploration)
## by (Ugwu Michael Ifeanyi)


## Dataset

The data set is an airline satisfaction scores for 129,880 passengers, were each record represents one passenger. The records contain details about passenger demographics, flight distance, delays, travel class, purpose, ratings for factors such as cleanliness, comfort, service, and as well as overall satisfaction with the airline. The dataset can be found at https://www.mavenanalytics.io/data-playground

**Summary of data wrangling** 
1. Rows with null column
2. Erroneous datatype('Arrival Delay' column datatype is float instead of int datatype)
3. Erroneous datatype('Departure and Arrival Time Convenience' column datatype is int instead of object datatype)
4. Erroneous datatype('Ease of Online Booking' column datatype is int instead of object datatype)
5. Erroneous datatype('Check-in Service' column datatype is int instead of object datatype)
6. Erroneous datatype('Online Boarding' column datatype is int instead of object datatype)
7. Erroneous datatype('Seat Comfort' column datatype is int instead of object datatype)
8. Erroneous datatype('Leg Room Service' column datatype is int instead of object datatype)
9. Erroneous datatype('Cleanliness' column datatype is int instead of object datatype)
10. Erroneous datatype('Food and Drink' column datatype is int instead of object datatype)
11. Erroneous datatype('In-flight Service' column datatype is int instead of object datatype)
12. Erroneous datatype('In-flight Wifi Service' column datatype is int instead of object datatype)
13. Erroneous datatype('In-flight Entertainment' column datatype is int instead of object datatype)
14. Erroneous datatype('Baggage Handling' column datatype is int instead of object datatype)
15. Erroneous datatype('Gate Location' column datatype is int instead of object datatype)
16. Erroneous datatype('On-board Service' column datatype is int instead of object datatype)



**Data Dictionary**

1. ID - Unique passenger identifier
2. Gender - Gender of the passenger (Female/Male)
3. Age - Age of the passenger
4. Customer Type - Type of airline customer (First-time/Returning)
5. Type of Travel - Purpose of the flight (Business/Personal)
6. Class - Travel class in the airplane for the passenger seat
7. Flight Distance - Flight distance in miles
8. Departure Delay - Flight departure delay in minutes
9. Arrival Delay - Flight arrival delay in minutes
10. Departure and Arrival Time Convenience - Satisfaction level with the convenience of the flight departure and arrival times from 1 (lowest) to 5 (highest) - 0 means "not applicable"
11. Ease of Online Booking - Satisfaction level with the online booking experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
12. Check-in Service - Satisfaction level with the check-in service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
13. Online Boarding - Satisfaction level with the online boarding experience from 1 (lowest) to 5 (highest) - 0 means "not applicable"
14. Gate Location - Satisfaction level with the gate location in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
15. On-board Service - Satisfaction level with the on-boarding service in the airport from 1 (lowest) to 5 (highest) - 0 means "not applicable"
16. Seat Comfort - Satisfaction level with the comfort of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
17. Leg Room Service - Satisfaction level with the leg room of the airplane seat from 1 (lowest) to 5 (highest) - 0 means "not applicable"
18. Cleanliness - Satisfaction level with the cleanliness of the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
19. Food and Drink - Satisfaction level with the food and drinks on the airplane from 1 (lowest) to 5 (highest) - 0 means "not applicable"
20. In-flight Service - Satisfaction level with the in-flight service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
21. In-flight Wifi Service - Satisfaction level with the in-flight Wifi service from 1 (lowest) to 5 (highest) - 0 means "not applicable"
22. In-flight Entertainment - Satisfaction level with the in-flight entertainment from 1 (lowest) to 5 (highest) - 0 means "not applicable"
23. Baggage Handling - Satisfaction level with the baggage handling from the airline from 1 (lowest) to 5 (highest) - 0 means "not applicable"
24. Satisfaction - Overall satisfaction level with the airline (Satisfied/Neutral or unsatisfied)


## Summary of Findings

In the exploration, I found that there was a strong relationship between the departure delay and arrival delay. The relationship is approximately linear between departure delay and arrival delay. I also found a somewhat surprising finding, majority of the airline users are returning customer and majority type of travel was business.




## Key Insights for Presentation

For the presentation, I focus on just the distribution of the passengers overall satisfaction, distribution of passengers class and the plot of departure delay vs arrival delay.

Majority of the airline passengers were dissatisfied or neutral with the services provided by the airline. Also, most of the airline passengers chose business or economy travel class, while the least travel class is the economy plus.

From the presentation, it was also observed that there is a strong correlation between departure delay and arrival delay.

