# Des-Moines-Bike-Sharing Analysis

**Overview:**

A group of investors are interested in expanding their bike sharing business within the city of Des-Moines, Iowa. After glimpsing our earlier visuals we constructed through Tableau, and using provided data, the have asked us to conduct several more infographics to present to them as the final part of an overall analysis as to whether said expansion should occur. In order to complete this part of our analysis, we first modified our dataset using Pandas before reuploading our data back into Tableau where we ultimately constructed said infographics. 

**Results:**

![image](https://user-images.githubusercontent.com/91284661/148690164-7abb46cc-6b80-4ded-832f-a9748724cf26.png)

One of the first results we pulled saw while consolidating our data comes from the heatmap above. In essence, it should be noticed that a more populated and urban environment seemed to impact the number of shared rides. This is evidenced by the size of the circles in the image above, as a larger circle represents a bike sharing station with more activity. Our results can be inferred by viewing these relative sizes of these concentrations in lower Manhattan compared to the rest of the map.

![image](https://user-images.githubusercontent.com/91284661/148690169-11eec865-a828-4987-a48d-1a8733e95603.png)

Another trend we saw early on in our analysis came from observing who is using this bike rental service. From the image above, we see that for the roughly 2.3 million rides we had data on, near 80% of our rides were conducted by subscribers to the service as opposed to customers.

![image](https://user-images.githubusercontent.com/91284661/148690175-f9b24b99-e9d0-448b-b37e-e2624acad438.png)

It was at this point in our work where we needed to update our data in order to provide further analysis for this project. As illustrated in part in this example, we effectively took our existing CSV file containing our data and pulled it into a jupytr Notebook file. From here, and with the help of the Pandas function, we converted our “tripduration” variable column from integer data to a datetime datatype. With this we could now measure the tripduration variable in hours, minutes, etc. Following this conversion, the data was exported back as an updated CSV file which we pulled back into the Tableau program for the final part of gathering our results.

![image](https://user-images.githubusercontent.com/91284661/148690184-068b36d6-0971-4814-bfb6-d7271dc305b8.png)

One of the items we wished to gather more info was the duration of trips amongst our users who subscribed to the bike sharing service. One of the reasons for finding this info was to get a sense for how much effective “wear-and-tear” would thus be happening to the bike products, which would be useful in relative questions of maintenance. After gathering this info, further detail was inquired: just because we had an idea of how long these trip durations were, doesn’t mean we had a sense for whether certain groups were more likely to have higher durations than others. We thus found that men had the highest relative trip durations within our data pool.

![image](https://user-images.githubusercontent.com/91284661/148690194-8c228a0f-39df-4502-b7b4-d29615d811f5.png)

Following this idea of relative usage time-wise for the bike-service, we also wanted to know what times of day specifically the bikes were getting the most usage. We took our trip counts and spread them out on table for each day of the week, highlighting with darker colors when the product was getting the most use. From the info above, it look as though the highest concentrations are found in the early morning, 7-9am during the work week as well as in the evening those same days, 5-7pm.

![image](https://user-images.githubusercontent.com/91284661/148690204-a5e5214e-57f4-44fc-8a26-9a4021750ea5.png)

![image](https://user-images.githubusercontent.com/91284661/148690211-1f6c14f1-1e5f-422d-ba9b-606678760272.png)

Tying our last points together, these same trends are found between both males and females. Still, the trend is more easily noticed and pronounced within males simply because of their more numerous usage of the service.

**Summary:**

In conclusions, there are several trends that appear to be at play within our data. The first seems notable trend observed is that both men and women use this service consistently during the Monday-through-Friday work week at similar time spans in the morning and evenings. Because of this, it can be inferred with relative safety that the product is being used as a reliable transportation option to get to-and-from work. This claim as a work-related transport service would also likely explain why so many of our users are regular subscribers as opposed to customers: if work is a consistent 9-5 schedule, it’s more likely that if you’re interested in biking that you’d subscribed to a biking service for a cheaper and convenient long-term-service.

Because of this revelation there are several things to put into the minds of the investors as they weigh their decision. The first is that there is a market for adults looking to bike to-and-from work according to this data. For this reason alone, careful consideration should be made when looking to expand this service into the Des-Moine market. Manhattan is a highly urbanized and populated location, and expansion should be made for this industry into other highly urbanized, populated centers within the country. Further analysis into the relative demographics and landscape of Des-Moine would need to be made in order to determine whether an expansion would therefore be a good idea.

The other recommendation made would be one of marketing and scale. Because we have a population of workers looking to bike to-and-from work instead of drive, marketing should be made to reflect how this bike-sharing company can help be apart of this new work-culture. Though the service presents itself as a fun way to tour the city on bike, and the data does present evidence that both customers and subscribers use them frequently and often enough to reinforce this business model, a change in marketing to reflect this work-related niche in our data might prove for a more profitable business model in the long term.
