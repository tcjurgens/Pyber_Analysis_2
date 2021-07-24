# PyBer_Analysis
## Project Overview
In this module, we analyzed CSV files and used Matplotlib to show the relationship between the type of city, the number of drivers and riders, and the total ride fares. 

Now, we have been asked to create a summary DataFrame of the ride-sharing data by city type and use Pandas and Matplotlib to create a multiple-line graph that shows the total weekly fares for each city type.

## Results
Below, I have added screenshots from my PyBer_Challenge_final_code.ipynb (this script may be found and viewed in the PyBer_Analysis repository) showing the two deliverables of this challenge: A ride-sharing summary DataFrame by city type, and  A multiple-line chart of total fares for each city type

<img width="629" alt="Screen Shot 2021-07-23 at 5 46 12 PM" src="https://user-images.githubusercontent.com/86446641/126844591-e971b93c-3845-4b0f-8fe5-e3955ec97a61.png">
<img width="990" alt="Screen Shot 2021-07-23 at 5 46 34 PM" src="https://user-images.githubusercontent.com/86446641/126844620-2b3144ba-f070-4c6a-af4e-63acf4974b1f.png">

Some interesting notes from this data is that in both rural and suburban cities- there were more total rides than total drivers (Urban cities had more total drivers than total rides), and similarly in both rural and suburban cities the Avg. Fare per Ride was less than the Avg. Fare per Driver (Urban cities had a higher Avg. Fare per Ride than Driver). It appears that these figures are correlated, and that if driver total and ride total were closer to even, so would be driver and ride fares.

## Summary

To sumarize to the CEO: it is clear that Urban cities bring in more cash flow- and this makes sense- theres more people in a close proximity so it is more likely that PyBer will be used. Also, in urban cities often people dont have their own transportation- so they have to look to ride sharing to get around more often. 

If the CEO were to expand PyBer to more urban cities- they can expect similarly large cashflow via farer. However; it would likely be difficult to match the total drivers count to total ride count- and thus the average fare per driver will continue to be less than the average fare for ride--- but thats ok.

If the CEO wanted to increase the Average Fare per Ride in Urban cities to resemble Suburban or Urban numbers- they would likely have to cap the number of drivers in those cities, supply-demand would mean that the riders would have to pay more to get a ride. However, I am not sure this is a reccomendable strategy.

One particular reccomendation would be to suggest incentivizing new drivers to sign on to rural and suburban areas so that riders could more easily get cars. More data/research would undoubtably be needed to confidently justify this: but, if riders are struggling to find rides in these citys/areas w PyBer, they may choose to use another ride sharing service- causing us to lose business. Further: because the average fare per ride is much higher in comparison (likely because these rides are longer on average than urban rides), profit lost to other ride sharing services in these areas may be a significant chunnk of profit we are not capitalizing on. 


