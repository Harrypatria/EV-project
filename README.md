### EV-project
#### EV Charging Station Siting Analysis
#### Introduction to Business Problem:  
- Background: 
This code was written as part of the requirements of the IBM/Coursera Data Science Professional 
Career Track Specialization. Students were asked to choose a problem and utilize skills acquired 
during this specialization to solve the selected problem.
- Business Problem Outline:
Electric Vehicles (EVs) are gaining popularity due to absence of local emissions, and certain 
technical advantages that EVs have over conventional vehicles (faster acceleration, no need for 
periodic service requirements etc.). This is not to say that there are no barriers to the widespread 
acceptance of EVs. One of the primary drawbacks is the lack of access to charging equipment at 
public locations.

- In this project, we look at the city of Raleigh in North Carolina, where I currently reside. The 
objective is to try to come up with a siting analysis for public EV charging station installations -
preferably close to local shops and restaurants so that people can charge their cars while getting 
groceries or sharing a meal with their loved ones. One of the indirect benefits of EV charging 
that is often talked about is contribution to the local economy - i.e. people tend to spend money 
on nearby shops when waiting on charging their EVs.
- To be specific, the area of interest in this case is within a 100 km radius of downtown Raleigh in 
North Carolina. This approximately covers the towns of Durham, Raleigh and Chapel Hill. As of 
2020, the population of the larger Raleigh-Durham-Chapel Hill Combined Statistical Area (CSA) 
is estimated at 2.03 million. Hailed as a technological hub within the state, the mean age of 
residents range between 26 to 35 years. This area may be considered a suitable case study 
location for testing out algorithms ranking retail facilities that could benefit from EV charger 
installations. 
- Note that the approach that I am taking is pretty simplistic - I am aiming to identify retail 
locations (primarily grocery shops, restaurants and some service industries) that have relatively 
few EV chargers in the vicinity. A list of suitable retail locations that could benefit from an EV 
charging installation in its neighborhood is provided as input to a clustering algorithm. This 
algorithm determines locations that could improve access to EV charging in our region of 
interest. 
- Outputs include a map with clusters of retail locations that could benefit from EV charger 
installations and a list of suitable locations for EV charging installations.
