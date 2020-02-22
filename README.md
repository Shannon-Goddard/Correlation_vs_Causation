**Resources** [https://www.census.gov](https://www.census.gov/quickfacts/fact/table/sanbernardinocountycalifornia,yolocountycalifornia,contracostacountycalifornia/PST045219)

## Nearly 700,000 people left California last year
### Despite roughly 500,000 people coming to the Golden State in 2018, census data shows more people left California than moved in.
CALIFORNIA, USA — In 2018, nearly 700,000 people decided to pack their bags and leave the California life behind.

**By contrast, there were only 501,000 people who decided to follow the California dream and set up camp in the state. With 691,000 people leaving the Golden State for another state, California was in the negative as far as net population change.**

The exodus from California also led among other states. Only the numbers for Texas, Florida, and New York came close.

**Texas lost 462,000; New York lost 458,000; and Florida lost 470,000.**

According to [the Census data](https://www.census.gov/data/tables/time-series/demo/geographic-mobility/state-to-state-migration.html), most Californians found themselves heading to Texas, Arizona, Washington, Nevada, and Oregon.  
- Texas - 86,000
- Arizona - 68,000
- Washington - 55,000
- Nevada - 50,000
- Oregon - 43,000  

While California led in people leaving the state in 2018, it came in third for the number of people who moved in. The state was behind Florida, who had 587,000, and Texas, who saw 563,000 move in.

**Census data also showed that the number of people leaving California has steadily increased since 2011.**  
- 2018 - 691,000
- 2017 - 661,000
- 2016 - 657,000
- 2015 - 643,000
- 2014 - 593,000
- 2013 - 581,000
- 2012 - 566,000
- 2011 - 562,000  

A [2018 study by the California Legislative Analyst's Office](https://lao.ca.gov/laoecontax/article/detail/265) revealed that more than a million people left California - spread out over a decade - as opposed to those who moved here from other states.  

The study said high taxes, cost of living, and affordable housing were among the main reasons why people were leaving.  

A [recent study by UC Berkeley](https://escholarship.org/uc/item/96j2704t) made similar findings with voters. According to the poll, roughly half of the state's voters have considered leaving California.  

The main reason was the high cost of housing, but high taxes and political culture were also big reasons voters considered leaving.  

Author: **Eric Escalante**  
Published: **5:30 PM PST November 5, 2019**  
Updated: **12:38 PM PST November 11, 2019**  
Full article can be found at [abc10.com](https://www.abc10.com/article/news/local/california/691000-leave-california/103-e02662aa-dfae-46b2-b94a-f20158053e60)  

There are many articles written, like this one, about Califorian's leaving due to the high cost of living. I would like to perform analysis on the cost of living that included:  

- Cost of Goods
- Minimum Wage  
- Maximum Wage
- Median Household Income  
- Median Home Price  

Although, Califoria would be the targeted data, it can be broken down by county and easily comparable to other California counties or counties in other states. With our diverse group living in different counties, each person can load the data from their county. As long as we all followed the same analysis steps, the test we perform would be meaningful.

Through various charts of the matplotlib library we would be able to visualize a strong correlation between the cost of goods and minimum wage. We could use Supervised Learning models to determine if the rise in minimum wage is the causation of the rise in the cost of goods. 

One of the challenges in this particular analysis would be finding a consensus on defining "cost of goods". I would recommend using The [Big Mac Index](https://www.economist.com/news/2020/01/15/the-big-mac-index) as a guide. The **Big Mac Index** is published by The Economist as an informal way of measuring the purchasing power parity (PPP) between two currencies and provides a test of the extent to which market exchange rates result in goods costing the same in different countries. However, we would be utilizing it as a measurment of the US dollar between years, rather than countries. The constant variable could be column titles from the census data, rather than the Big Mac. The analysis would reveal the value of the US dollar's fluxuation within each county of the same country.  

We would be able to find the Minimum Wage, Maximum Wage, Median Household Income, Median Home Price throughout the years on Census data. However, I would like to dive deeper in our analyisis and use a specific company as a model for purpose of our analysis. <br/>  

Kroger is the fifth-largest retailer in the world and the fourth largest American-owned private employer in the United States. Kroger is ranked #20 on the Fortune 500 rankings of the largest United States corporations by total revenue. As of 9 November 2019, Kroger operates, either directly or through its subsidiaries, 2,758 supermarkets and multi-department stores. More information can be found at [wikipedia.org](https://en.wikipedia.org/wiki/Kroger)  

Kroger's grocery stores are what the company is most known for. With Kroger owning nearly 2,800 grocery stores in 35 states. These stores comprise more than 24 chains, including Kroger, Ralphs, Dillons, Smith's, King Soopers, City Market, Fry's, QFC, and Harris Teeter. With the company having such a strong presence throughout the country, it seems fair to use one of their California subsidiaries as the model, Food 4 Less.  

Food 4 Less is a national grocery store grocery chain, currently owned by Kroger. It is a no-frills grocery store where the customers bag their own groceries at the checkout. Kroger operates Food 4 Less stores in California, Illinois, Indiana, and Ohio.

The rates of pay can be found on local union contracts. For our model, we will use [Food-4-Less Local 1167](https://www.ufcw1167.org/pdf's/17F4L_WEB.pdf) for 2017-2020. Here I could determine the Minimum Wage is $13.20 through the "Service Clerk" title and Maximum Wage is $20.11 through "Grandfather Warehouse Clerk" title, currently, for San Bernardino County.  

Using the the "Grandfather Warehouse Clerk" title's Maximum Wage of $20.11 and multipling it with 40 hours a week and, then, multipling it by 52 weeks ((20.11 * 40) * 52), we can see their annual income is $41,828.80.     

As a broad generalization, most people can afford to purchase a house worth about three times their total (gross) annual income, assuming a 20% down payment and a moderate amount of other long-term debts, such as car or student loan payments. This best practice can be found at [mymoneyblog.com](https://www.mymoneyblog.com/4-different-rules-of-thumb-for-how-much-house-you-can-afford.html). As there are many similar "Best Practices" in home buying, I would like to keep a consistancy throughout the analysis and use this one, three times total annual income.  

With the best pracice in mind and the median price of homes currently listed in San Bernardino County is $350,000, according to [zillow.com](https://www.zillow.com/san-bernardino-county-ca/home-values/), a single gross income of **$116,666.67** would be needed to purchase a **median price** home in **San Bernardino County**.  

Although, that number is flabbergasting enough, it fails when compared to surrounding southern California counties, such as:  
- Los Angeles  
- Orange  
- Ventura  
- San Diego  

These counties the median home prices are, easily, doubled.  Meaning, the gross annual income would, also, have to double.  
Pricing can be seen on [laalmanac.com](http://www.laalmanac.com/economy/ec37.php)  

Going back to the "Grandfather Warehouse Clerk making a maximum wage of $20.11, their gross annual income would be calculated by **hourly rate X 40 hours a week X 52 weeks a year = $41,828.80**. A Kroger employee working for 20-30 years to make maximum wage would only be able to afford a home valued at $125,486.40, when using the best practice of three times your annual income. It would take 2.79, almost 3 incomes, to live in a median valued home in the cheapest county of southern California when at maximum wage job in the top 20 fortune 500 company. However, Food 4 Less doesn't just opporate in San Bernardno county. It opporates throughout the state.  

There are many articles written about Califorian's leaving due to the high cost of living. However, they fail to mention the stagnant rise of Maximum Wage. It would be intresting to see what an in deapth analysis could reveal about the Minimum and Maximum wage gap with the census data, the correlation of the Minimum Wage and Cost of goods rising 100% over the past two decades, and the housing cost and value of the US dollar fluctuating in each county.  
