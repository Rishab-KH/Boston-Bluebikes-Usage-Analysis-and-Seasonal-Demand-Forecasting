# Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting_

# Summary
Bike-share programs are cost-effective, environmentally friendly alternate transport offerings that are emerging all over the country. These programs are rental schemes where users can pick up, ride and drop off bicycles at various automated stations across the city. By sharing with others, these public bicycles can be used on an “as-needed” basis, without ownership. The advantages of bike-sharing are numerous, including health benefits, reduced impact to the environment, financial savings for individuals, and much more. 

Despite these advantages, users often report issues with the logistics of bike-sharing schemes, particularly with the flows of usage at different time periods of the day. Focusing specifically on the Boston Bluebikes program, there have been several reports of unavailability of bikes during high periods of passenger traffic during the day, especially at popular dock stations - even with efforts to manually rebalance bicycles from emptier stations multiple times a day [1]. The busiest stations tend to be around academic institutions, where there is a large student footfall. Additionally, the weather impacts the usage of the bikes greatly, regardless of the attempts by Boston Bluebikes management to incentivize rides during the winter months through prizes and challenges [2]. 

In this project, we analyze the usage patterns of the Boston Bluebikes program to help understand the seasonal and time period effect on the utilization of the bicycles. We then focus on describing the bike activity near the Northeastern University campus in order to visualize the demand during school terms. Furthermore, we provide a forecast of the demand of Bluebikes around Northeastern for every academic season, allowing for the ability to plan ahead and have a streamlined organization system in place for busier periods around the campus. 

We made use of the publicly available Boston Bluebikes dataset across the years 2019 - 2022 [3]. The data is in CSV format, consisting of one CSV for each month of the year and 15 columns each. The most significant columns used in our analysis are:

Start Time: Timestamp of when the bike ride began (eg: 1/1/2019  10:09:47 AM)

Trip Duration: Duration of ride in seconds (eg: 371)

User Type: Is the user a regular customer or a subscriber

Start/End Station Latitude and Start/End Station Longitude: Coordinates of the dock stations from where the ride began and ended (eg: 42.358100 and -71.093198)
              
We have used ARIMA and LSTM models for seasonal demand forecasting. LSTM was able to give better predictions of  the total rides used from Northeastern University stations in each season.We observed that the fall season had the highest demand, followed by summer, spring and winter. 




# Usage

Please copy this link -> https://github.com/Rishab-KH/Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting_/blob/main/main.ipynb and copy this url to https://nbviewer.org/ for viewing all the interactive visualizations. 
We can view the interactive plots at github.io ->  https://rishab-kh.github.io//Boston-Bluebikes-Usage-Analysis-and-Seasonal-Demand-Forecasting_//

 

# References
[1]https://www.thecrimson.com/article/2022/12/1/Bluebikes-boston-logistics/

[2]https://www.Bluebikes.com/blog/2022-winter-challenge

[3]https://www.Bluebikes.com/system-data 
