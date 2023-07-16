# Citibike

This analysis of Citi Bike will show the reach and success of the Citi Bike program. 
I will also suggest a number of actions that could be  taken to increase the usage and popularity.

I analysed the Citibike data for the year preceding March 2023 using Tableau. The Tableau Public VIZ can be found [here](https://public.tableau.com/views/Challenge_16807800846940/TheCitiBikeStory?:language=en-US&:display_count=n&:origin=viz_share_link). Please noote that on the site visuals are interactive and show moving timelines.

In that period  32 million trips were made to and from over 1700 stations across NYC.
The total distance covered was 59 million km which is the equivalent of aproximately 11.000 tons of CO2  if travelled by car or if looking at another dimension cycling around the world 1500 times.
The top 10% of  stations averaged over 67.000 trips each or 35% of the total

This analysis will look at the effects of weather, for which I used an openweather.com API, and time of year/week on number of trips and popularity of stations.

In addition the large fluctuation in trips day by day are analysed and a possible measure to counter these imbalances is introduced.

This map shows a heatmap of the bike stations overlayed on a map of both the subway and NYC burroughs.

<img width="678" alt="Screenshot 2023-07-16 at 2 09 05 pm" src="https://github.com/Reinierandrew/Citibike/assets/112833174/dc8d8db6-182e-4fc7-8335-9fa019e9db7a">

New Yorkers use Citi Bike at all times of the day and night especially aty the end of a work day. The average distance travelled is very consistant at just under 2 km a trip.
During weekends popular times are more evenly distributed from morning to evening.
Note the difference in distribution beween W21 & 6 where the mornings are less popular. The 'live' public VIZ shows a 
<img width="1246" alt="Screenshot 2023-07-16 at 2 08 03 pm" src="https://github.com/Reinierandrew/Citibike/assets/112833174/12db3a7a-5a63-4573-b8b3-1857ebc1ed90">

In the below I ook at the stations from a number of different angles and combinations.
* 	 Date in september 2022
* 	 Minimum trips per day
* 	 Weekend or workday
When zooning in more points of iterest are shown in the background such as museums and buildings.
<img width="1246" alt="Screenshot 2023-07-16 at 2 07 46 pm" src="https://github.com/Reinierandrew/Citibike/assets/112833174/3dbef5d6-357c-4091-a8b2-bfbaa397ed02">

The following shows the effect of temerature and wet/dry days on the number of trips. When there is an unseasonal drop in temerature the bike trips go down.
<img width="1258" alt="Screenshot 2023-07-16 at 1 48 21 pm" src="https://github.com/Reinierandrew/Citibike/assets/112833174/1429b24c-c55b-4cde-8d00-4454b34f235a">

When looking at the  trip start and ends by station and by date there are large fluctuations. These fluctuations are obviously influenced by weather and time of the year or week but those factors do not explain the consistency of the fluctuations.

A major factor for the fluction is the fact that if there are more starts from a station than ends the "stock" of bikes will diminish until there are no bikes and people have to find an alternative to the Citi Bike. A solution could be to move bikes where there is a (forecast) surplus to a station where there is a (forecast) deficit. The logistics costs of such an opersation will be large.

An alternative solution could be to incentivise  users to end their ride at a 'deficit station'  with for example a credit on theirn account.
<img width="1258" alt="Screenshot 2023-07-16 at 2 03 45 pm" src="https://github.com/Reinierandrew/Citibike/assets/112833174/cd99c360-3740-4b7d-b0a7-923f417afff9">


