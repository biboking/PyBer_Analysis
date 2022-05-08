# PyBer_Analysis


## The purpose of this Project

As a new data analyst of Pyber, a python-based ride-sharing app company, my first task was to read, clean, and process extensive data from CSV files to generate an in-depth report. I was using matplotlib, panda library, jupyter notebook, and the related tools to create a variety of charts to showcase the relationship between the type of city and the number of riders and drivers, as well as the percentage of the total fares, riders and drivers by type of city. Pyber would use my visualizations and analysis to improve its access to ride-sharing services and access the affordability for underserved neighborhoods.


## Results
- After cleaning the raw data with data sets merge and groupby() functions, I created a summary report with five elements for three city types, based on the CSV data provided. The city types were rural, suburban, and urban. The five elements for these three types were total riders, total drivers, total fares, average fare per ride, and average fare per driver. We focused on the first 17 weeks of 2019, from January 1st to April 28th.

![results](analysis/Deliverable_1_result)
- From this summary, we found out that Rural cities had the least total rides while the urban area had the most rides. This meant that the ride-sharing happened more where the population density was higher.
- Accordingly, a higher need for rides led to a higher number of total drivers and fares. Thus, the urban city had the highest total drivers and fares as well, the suburban the next, and the rural cities the least.
- On the contrary, rural areas had the highest cost, as the "average fare per ride" and "Average Fare per Driver" ranked highest among the three.

![charts](analysis/PyBer_fare_summary.png)
- All three city types' total shared riding fares reached their peaks by the end of February 2019. But the urban cities had a primarily steady increasing trend before March, while suburban and rural cities had some up and downs before they reached their ride peak.
- All three types of cities had a decrease in March. The rural cities had a steady and growing trend. The total fares in suburban areas plummeted, and it grew back enough within March. The urban cities had a very steep curve in fares in March.

## Summary
1. Although the urban cities had more ride requests and lower average fare per driver, there were more drivers available than needed. More investment is needed for user awareness of using ride-sharing apps in urban cities.
2. Likewise, more ads and benefits are needed to recruit enough drivers to meet the ride-sharing demand in rural and Suburban cities. This will also help to reduce the average cost per ride and per driver.
3. Campaign at the right time is also very important. Pyber should see why some of the months have lower rides. Is it all about seasonality? Any other reasons included? Pyber can do an AB test to see if they should invest more in quieter seasons to increase the rides, or campaign at good seasons to push the peak even higher; whichever provides a higher ROI (return of investment) should be more effective.
4. Customers would want a lower fee per ride, but drivers would like to earn more. How to balance this and provide the customer with affordable services while let drivers earn more will determine the market share of Pyber.
