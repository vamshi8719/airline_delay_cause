# Airline Delay Cause
This is a Udacity nano degree project to analyze airline delay cause data. The goal of the project is to show the major causes of flight delay and also explore any relation between the reasons.

# Dataset Overview
The dataset is maitained by U.S. Department of Transportation with data reported by airlines. The delay reasons reported are carrier, late aircraft, nas (air traffic), weather, and security. There is one record for every airline and airport per month. The other details provided are total flights arriving into airport, cancellations, and divertions. Below columns are available in the dataset: 

year = year of flight  
month = month of flight  
carrier = carrier code  
carrier_name = airline name  
airport = airport code  
airport_name = name of airport  
arr_flights = number of flights arrived  
arr_del15 = number of flights that got delayed for more than 15 minutes  
carrier_ct = number of flights that got delayed due to carrier  
weather_ct = number of flights that got delayed due to weather  
nas_ct = number of flights that got delayed due to heavy traffic  
security_ct = number of flights that got delayed due to security  
late_aircraft_ct = number of flights that got delayed due to previous flight on same plane  
arr_cancelled = number of flights cancelled  
arr_diverted = number of flights diverted  
carrier_delay = delay in minutes due to carrier  
nas_delay = delay in minutes due to heavy traffic  
security_delay = delay in minutes due to security  
weather_delay = delay in minutes due to weather  
late_aircraft_delay = delay in minutes due to previous flight on same plane  

# Software and Packages
Jupyter Notebook  
Numpy  
Pandas  
Matplotlib  
Seaborn  
Warnings  

# What I did

Data Wrangling  
Features of interest were identified
Univariate Exploration  
Bivariate Exploration  
Multivariate Exploration  

# Findings

<img width="413" alt="image" src="https://github.com/vamshi8719/airline_delay_cause/assets/56979563/492b0f02-9862-46fa-a407-d90022670ce0">


<img width="672" alt="image" src="https://github.com/vamshi8719/airline_delay_cause/assets/56979563/35b77a11-ada5-46e6-a5ed-da6aa07a1745">  


# Conclusions  

The flight delays can be caused due to multiple reasons. We normally assume weather to be one of bigges reason for flight delays. It was quite suprising to see that delays due to carrier and air traffic (nas) are primary reasons. There were several outliers in the dataset, which made analysis quite difficult. The outliers were overcome by limiting the plot xlim. The dataset for the year 2023 is not complete.  

