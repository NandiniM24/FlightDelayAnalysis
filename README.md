**Problem Statement**
The aviation industry in the USA faces a pressing challenge with the persistently high rate of flight delays over the past decade. These delays not only inconvenience passengers but also incur substantial financial costs for airlines. According to recent statistics, flight delays cost the industry billions of dollars annually, with an estimated loss of over $25 billion in revenue each year. These delays result in increased operational expenses, such as fuel consumption, crew wages, and maintenance costs, while simultaneously leading to revenue loss due to missed connections, cancellations, and reduced customer satisfaction. Moreover, airlines risk facing regulatory fines and penalties for prolonged delays, further exacerbating their financial burden. Additionally, frequent flight delays tarnish airlines' reputations and erode customer loyalty, posing long-term challenges in maintaining competitiveness in the market.

Therefore, it is imperative for the aviation industry to address this issue effectively to minimize financial losses, enhance operational efficiency, and improve customer satisfaction to secure long-term profitability and business growth.

**Objective**
The primary objective of this project is to develop a predictive model to accurately predict flight delays by building a robust regression model to predict flight delays based on various factors such as carrier issues, weather conditions, national air system problems etc.

**Dataset Description**
Source - https://www.bts.gov/browse-statistical-products-and-data

The dataset comprises information pertaining to delay in flights because of various reasons. Below is a concise overview of the dataset's variables:

date: Year and month, in the format YYYY-M (e.g., 2018-1) 
carrier: The two character designator for the carrier/airline. 
carrier_name: The full name of the carrier/airline. 
airport: The three character designator for the arrival airport. 
airport_name: The full name of the arrival airport. 
arr_flights: The total number of arriving flights for the carrier-airport 
pair: for the month specified. 
arr_del15: The number of arriving flights that were delayed. Delayed is when a flight arrives more than 15 minutes later than the scheduled arrival time. 
carrier_ct: The number of arriving flights delayed due to a carrier issue. 
weather_ct: The number of arriving flights delayed due to a weather issue. 
nas_ct: The number of arriving flights delayed due to a national air system issue. 
security_ct: The number of arriving flights delayed due to a security issue. 
late_aircraft_ct: The number of arriving flights delayed due to an earlier late arrival of an aircraft. 
arr_cancelled: The number of cancelled flights. 
arr_diverted: The number of diverted flights. 
arr_delay: The total number of delayed minutes due to delays. 
carrier_delay: The total number of delayed minutes due to carrier issues. 
weather_delay: The total number of delayed minutes due to weather issues. 
nas_delay: The total number of delayed minutes due to national air system issues. 
security_delay: The total number of delayed minutes due to security issues. 
late_aircraft_delay: The total number of delayed minutes due to earlier later arrival of aircraft.
