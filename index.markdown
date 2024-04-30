---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h1>Shattered Nights: Unveiling San Francisco's Driving Under the Influence Epidemic</h1>

Authors: Manos Loukaidis and Nico Sherpa

Almost every day, we can read about local crimes in the newspaper, and get so overwhelmed with the load of incidents, that it can be very hard to get the big picture of what is actually going on. On this page, we want to investigate and visualize incidents, where people were recorded driving under the influence (DUI) in San Francisco, by looking at the [San Francisco Crime Dataset](https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data), that contains data from between January 2003 and May 2018, that has been narrowed down to the data until the end of 2017, to have consistent month-aggregated values.

![Golden Gate Bridge](assets/golden_gate.jpg)

The dataset contains data to crimes, like e.g. Robbery, Prostitution, Vandalism, or, as we have chosen for the following section, DUI. Besides interesting variables, such as the date and time of the crime or a more detailled crime description, we can also obtain the exact location, where the crime has been reported, giving us the chance to have interesting visualizations of the crime incidents.

In 2022, the amount of people in the United States that died from drug overdoses has increased 797 % since 1999, according to the [National Safety Council](https://injuryfacts.nsc.org/home-and-community/safety-topics/drugoverdoses/data-details/#:~:text=Preliminary%202022%2C%20estimates%20indicate%20that,%2C%20homicide%2C%20and%20undetermined%20intents.). Eventhough this does not mean that there is a direct correlation to the DUI incidence rate in San Francisco, it still tells us that there is a big and increasing problem with drug relatd incidents, under which the DUI incidents also fall.

There have been implementations of various initiatives aimed at reducing DUI incidents and improving road safety in San Francisco during the selected period. For instance in 2006, San Francisco initiated a program called "[Avoid the 25](https://www.eastbaytimes.com/2011/05/26/contra-costa-countys-avoid-the-25-anti-dui-campaign-beefs-up-for-memorial-day-weekend/)" which involved law enforcement agencies across 25 cities and counties in the San Francisco bay area working together to fight DUI's during holidays and special events. This program included increased DUI checkpoints, saturation patrols, and public awareness campaigns to discourage people from driving under the influence.

Furthermore, San Francisco's Police Department received [a grant from the California Office of Traffic Safety](https://www.sanfranciscopolice.org/news/sfpd-receives-grant-special-traffic-enforcement-and-crash) to enhance DUI enforcement efforts, which included funding for additional officers dedicated to DUI patrols and checkpoints. So we can see a proactive approach by the city towards combating DUI incidents and promoting road safety. It thus might be interesting to additionally look at the given data from a quantitative standpoint, to see specific characteristics and patterns in the occurrence of those incidents.

<h2>Prevalence of incidence is dependent on the time</h2>

There are several factors that might have a significant influence on the occurrence of intoxicated driving incidents in San Francisco. One of them is time. Considering the dataset until the end of 2017 (to give a consistent view on all the months) and plotting the aggregated time series, we can observe that incidents occur more often around the night, at weekends, and a bit lesser in the summer months. When observing the plot with our cursor, we see that during between 10 and 11 o'clock, the total incidents are 26 over all the years, while opposed to it between 0 and 1 o'clock the total incident amount is 705, which is more than 27 times more often than during former mentioned time interval.

<iframe src="/assets/combined_crime_plots_newnew" width="100%" height="920px"></iframe>

<h2>There are intoxicated-driving-hotspots</h2>

Below a map is presented with DUI incidents that occured on Sundays in the San Fransisco area. We can clearly observe that the majority of “Driving under the influence” incidents occur within the greater area of San Francisco where locations are situated, that have a potential influence on the incident rate, like numerous nightclubs. Additionally, the map highlights that many violations are concentrated along the highways, indicating a heightened likelihood of police presence and alcohol checkpoints targeting drivers departing from these nightclubs. This area likely serves as a hotspot for various illegal activities due to the significant presence of nightclubs.

<iframe src="/assets/map.html" width="100%" height="600px"></iframe>

Check out the [Nightclubs in San Francisco on Google Maps](https://www.google.com/maps/search/nightclubs+in+San+Francisco/@37.7550043,-122.4926137,12.53z/data=!4m2!2m1!6e1?entry=ttu), its quite interesting to see the overlap with our map from above.

<h2>What the hell is happening in Richmond?</h2>

To not overload the next graphic, we included incidents of driving under the influence only from 2015, and plotted them on the hour of the day. Interestingly, we can confirm the insights from the two previous plots, that during night the incident occurrence increases, and that we can spot the focus area around the night clubs in San Francisco.

<iframe src="/assets/Heatmap_with_time.html" width="100%" height="600px"></iframe>

When starting the animation, we can see a relatively spread out distribution of cases, while we can still recognize a higher density in the central area, eventually related to a higher population density and other factors like previously mentioned nightclubs, that are located there. At around 5 o'clock we can observe a steep decrease of the incidence occurrence. This will be around the time where most of the people having been around in night establishments before are already at home and bars and nightclubs are closing their doors. The incidence prevalence increases again in the late afternoon and early evening, while reaching its peak between 11 p.m. and 4 a.m. (as we can see in the first plot from above). 

However, what we couldn't see in the first plot is, that the relation between the amount of incidents in the main San Francisco area (around the upper right area of the map) and the Richmond area (around the upper left area of the map) show some unusual patterns. Pause the autoplay on the interactive map and look at the hours 13, 16, and 19. What do you observe? We can see not just a few, but no incidents at all in the Richmond area, while the overall trend in the main area is increasing. It might be interesting for law enforcers to investigate, why that is the case. Is it due to a lack in the area specific patrolling and controlling. Or do external factors like establishments have an influence here? Certainly, further research into why certain patterns occur is required to shed light into why they occur or on how to prevent them. One way to do it is to qualitatively analyse police operations in certain areas, or to dive into the more detailled crime descriptions that are given in the dataset.

<h2>What can we learn from the data?</h2>

Having data visualized in an interactive manner can show us quite intuitively where specific patterns occur, that are not yet discovered when only plotting time series bar charts or similar. We could learn, that there are certain times and places, where DUI incidents accumulate stronger (weekends, nights, main city area). With differing time and location variables, the incident rates are changing. However, we also learned about the limitations of visualizing the San Francisco crime data, as we can not exactly explain, why certain patterns occur (like the low Richmond 13, 16 and 19 o'clock incident prevalence). But pointing them out is the first step of finding solutions to systematic problems in patrolling or when trying to find the optimal preventive measures for the future.

<iframe src="network_graph_of_movie_genres.html" width="100%" height="600px"></iframe>


The contribution split for this assignment can be found on the [About](https://nicosrp.github.io/dtu-socialdataproject-movies/about/) page.