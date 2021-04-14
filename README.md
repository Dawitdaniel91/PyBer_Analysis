# PyBer_Analysis

# Overview of the analysis:

The purpose of this anaylysi is to prepare the dataframe that shows ride sharng data of Rural, Urban and suburban cities.The source of data is city_data.csv & ride_data.csv. Based on the sources, i am going to creat the line graphs that total summery of fare by cities.i pulled the data by using the group() funciton with count and sum to get total number of driver, total number of rides and total number of fare by city type. Finaly , I used the pivot() function and resample function to creat line grapth.

 # Results:
 
 Tabble 1.
 
 ![PyBer summary DataFrame](https://user-images.githubusercontent.com/80365882/114764962-6c33a800-9d19-11eb-9afa-fc241723cf4f.png)

### The above tables shows that:
     . Rural city has the least amount of driver, rides and total fares when commering to the rural and subrural cities.But the urban city has the most amount of driver, rides and total fares than others.
     
Table 2.

![convert the DataFrame](https://user-images.githubusercontent.com/80365882/114764372-b8cab380-9d18-11eb-8c5e-2005669c485f.png)

The above table shows that total fare for date and time.

Table 3.

![resampled DataFrame](https://user-images.githubusercontent.com/80365882/114765066-8ec5c100-9d19-11eb-8b51-ca274f16c511.png)

The above table shows us resampled DataFrame

# Total fare by city Chart

![PyBer_fare_summary](https://user-images.githubusercontent.com/80365882/114765222-c03e8c80-9d19-11eb-9f6b-a963a3285c92.png)

# Summery

  The results shows that what kind of fares recomend based on the which cities the passenger catching ride in. 
  
    1. assign the driver on which cities busy and more work in.
    2. charge more fare in urban cities
    3. make some fare madification at rural area for more atract more drivers'


