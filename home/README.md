# Ford GoBike System Data Exploration and Explanation
## by (Tijani Ibraheem)


## Dataset

This data set includes information about individual rides made in a bike-sharing system 
covering the greater San Francisco Bay area. The dataset has 16 original columns that 
contain some important columns relevant for our analysis and a few that are out of our 
question scopes. The data can be found [here](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1660749069764219&usg=AOvVaw3RMR1aglyvpDsJqlIz0tfk).


## Summary of Findings



In the exploratory phase of my analysis, a number of insights where drawn from my data. 
There is a left skewness on the trip durations. This is a clear indication that, customers 
don't take long trips and since a reasonable assumption was that, workers are the most 
customers, it makes sense to admit that their work places isn't far from their homes. 
This is because, the data clearly shows how busy weekdays are compared to weekends where 
users might want to take a rest at home, leading to a drop in customer over the weekends. 
Further more in our univariate analysis, I discored at a glance how dominant male customers 
are to the female and other genders. There was also a 91% of Subscribers as opposed to just 
9% of Customers. This is an indication that, Subscribers have a long term relationship with 
the company because it seems like they will need it on a daily basis, especially on weekdays. 
Most users are youth, concentrated between the age of 20 and 40 years old with trips averaging 
10 mins. Statistically, Customers types have a better performance across all genders compared 
to Subscribers. This is most probably associated with the fact that, the Subscribers rent bikes 
for official reasons or to reach their workplaces while Customers rent bikes most likely for 
sporting and recreation purposes. This is responsible for why the customers tend to display a 
higher average duration ride but significantly lower total duration in comparison with the 
Subscriber users.


## Key Insights for Presentation


- The Ford GoBike System has a number of insights to derive from it. I set out to answer a few 
questions such as; 
 - What time of the days do we normally have high rentals of bikes. 
 - Are bikes rented mostly by customers or subscribers 
 - Are men the ones that rents more bikes or women.
 - What are our top and least performing stations
 
 Fist of all, our users are largely dominated by male subscribers and male customers between 
 the age of 20 and 40 who don't seem to ride more than 10 mins per day on the average. Weekends 
 appear to be less busy as opposed to every other day. Another insight that was drawn was the the 
 duration performance of our users based on gender and user types. Across the whole data, males 
 rent bikes way for than women. Males consist of 75% of the total as compared to 21% of female 
 riders. However, females have a longer average duration ride than men. This could be due to the 
 fact that, women rider slower and could be a good explanation for why they spend longer than men.
 According to the analysis, there are 2 moments of the day when rides peak. These are 8am and 5pm.
 At 8am, workers are on their way to work, this tells why there is a peak in bike rentals, consequently,
 at 5pm, they are leaving their work to go home. For bike sharing, almost 90% of the Subscriber riders 
 don't share bikes. Because the majority of Subscriber bikers ride for a short period, and also because
 they don't mostly share bikes, it's safe to admit that, their work and homes are not too far apart.
 This above reason is why they are mostly subscriber which mean they most likely have a service plan 
 that they are subscribed too for daily short commuting.