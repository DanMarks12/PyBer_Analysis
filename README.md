# PyBer_Analysis

## Overview of the analysis: Explain the purpose of the new analysis.
The purpose of our analysis was to explore ride sharing data of our ride service based on the type of city (Urban, Suburban, Rural). Upon merging our 2 dataframe we are able to take differnt views of each city type be it average fare, number of drivers, and eventually daily and weekly views. By creating these analysis (shown below) we are able to make important business desicions which could affect marketing to consumers as well as marketing projects to recruit new drivers in cities where we see opportunity in. Our final piece of analysis provided us with a view of total fare by city over a duration of time so we are able to measure the profitability we have experienced in the given city types. 


## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
We ran all kinds of analysis through our DataFrame to give different views on our business models in these cities. We started off with a scatter plot with all 3 city types represented to give a better comparison of each.

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig1.png)

As we can see above, the majority of our rides are coming out of urban areas. Not only this, we can also see our average fares are higher in Rural and Suburban areas, city types that have less rides on average.

This is further supported in our box and whiskers where we look at fare prices on average. Charts like these can show us opprotunities where we may have missed opportunities to capture more revenue. 

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig3.png)

Although this is true, an obvious reason behind this would be supply and demand. One could assume that because less people live in Rural areas they will use our ride app less frequently, but this may not tell the whole story. From the chart below, we can see a low supply of drivers in rural and suburban areas. We can theorize that because we have hired less drivers in these areas, the price is higher and may be a deterent for people to take more rides.

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig4.png)

We can quickly go over a distribution of %Total Fares and %Total rides in these areas. We use a pie chart to provide a very simple yet engaging view of the distribution. It makes sense that the city type that has the largest total rides also provides us with our largest share of Fare (revenue)

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig5.png)    ![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig6.png)

But if we look deeper, we can see more info on the point I made above. The distribution of drivers in these cities are much different. Although it still follows the order from max to min of Urban, Suburban, Rural, we can note that the % distribution is much different than above. 

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/Fig7.png)

Our final piece of analysis involved taking all of our data we have been playing around with and providing a better look of our data over a time period. Through this data we can see the same info as above, that Urban provides the most fares while Rural the least, but we can also see some important patterns. We see a sike in fares between Feb and March, as well as similar spikes beginning in April. If we line these dates up with marketing initiatives we have in place we can see the impact certain marketing campaigns have had on revenue and plan accordingly throughout the new year. 

![](https://github.com/DanMarks12/PyBer_Analysis/blob/main/analysis/fig8.png)

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

1) We need to hire more drivers in suburban and rural areas. Not only would this provide more opportunties for our customers to hire rides, it will also bring the price down which could increase demand in these untapped markets.

2) We could change how we charge in Urban areas. Since these areas are our hot spots and main money makers, we need to leverage the volume of rides we have. Maybe by charging more on a per mile basis than we do in Rural areas we would be able leverage opportunity in our hottest market and make more fares per ride.

3) By looking at our final graph we can see dips and spikes throughout the year. My first recomendation would be to look at the data over a whole year or longer if possible, and then create incentives for drivers to drive during the busiest periods (which we now know ahead of time) and additional provide incentives to hire new drivers in Rural and Suburban areas. 
