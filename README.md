 [![news](/pics/header.png)](/vids/News_vid.mp4?raw=true)  
 
#### Table of Contents  

[Project Roadmap](#project-roadmap )    
[Project Overview](#project-overview)  
[Resources](#resources)  
[Technology](#technology)  
[Objectives](#objectives)  
[Summary](#summary)  
[Dashboard](#dashboard)  
[Presentation](#presentation)  
[Recommendation](#recommendation)  
[Limitations](#limitations)  
[Sources](#sources)  
[Communication Protocols](#communication-protocols)  

## Project Roadmap  
The project roadmap and description of all the project deliverables can be found in [Deliverables.md](/Deliverables.md)  

## Project Overview    
### Nearly 700,000 people left California last year
#### Despite roughly 500,000 people coming to the Golden State in 2018, census data shows more people left California than moved in.
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

**Reason the topic was selected**  
There are many articles written, like this one, about Califorian's leaving due to the high cost of living. The reason this topic was selected, with our group living in California, it's personal.  

As a broad generalization, most people can afford to purchase a house worth about three times their total (gross) annual income, assuming a 20% down payment and a moderate amount of other long-term debts, such as car or student loan payments. This best practice can be found at [mymoneyblog.com](https://www.mymoneyblog.com/4-different-rules-of-thumb-for-how-much-house-you-can-afford.html). As there are many similar "Best Practices" in home buying, We would like to keep a consistancy throughout the analysis and use this one, three times total annual income. The consistancy will make the analysis meaningful. 

With the best pracice in mind and the median price of homes currently listed in San Bernardino County is $350,000, according to [zillow.com](https://www.zillow.com/san-bernardino-county-ca/home-values/), a single gross income of **$116,666.67** would be needed to purchase a **median price** home in **San Bernardino County**.  

Although, that number is flabbergasting enough, it fails when compared to surrounding California counties.These counties the median home prices are, easily, doubled.  Meaning, the gross annual income would, also, have to double.  
Pricing can be seen on [laalmanac.com](http://www.laalmanac.com/economy/ec37.php)  


**Questions the team hopes to answer with the data**  
We would like to perform analysis on the cost of housing in California that included:  

- Median Home Price
- Median Household Income  
  
With California being the targeted data, we wanted to compare all the other states. Questions the team hopes to answer with the data is:  
- What are the California median household prices in California expected to be in the next five years?  
- What are the California median household prices in California expected to be in the next ten years?  
- Based on the ["Best Practices"](https://www.mymoneyblog.com/4-different-rules-of-thumb-for-how-much-house-you-can-afford.html) in home buying, how much income would be needed to live in a median priced home in California at that time.  
- What are the top 5 states Californians are moving to?  
- How does California housing cost compare to those 5 states?

**After our analysis, we hope to answer:**
- Is it time to leave California? 

## Resources
- **Data Source:** [2010_data](/Resources/data/2010_data.csv) | [2011_data](/Resources/data/2011_data.csv) | [2012_data](/Resources/data/2012_data.csv) | [2013_data](/Resources/data/2013_data.csv) | [2014_data](/Resources/data/2014_data.csv) | [2015_data](/Resources/data/2015_data.csv) | [2016_data](/Resources/data/2016_data.csv) | [2017_data](/Resources/data/2017_data.csv) | [2018_data](/Resources/data/2018_data.csv) | [population_data](/Resources/data/population_data.csv) | [migration_2010](/Resources/data/migration_2010.csv) | [migration_2011](/Resources/data/migration_2011.csv) | [migration_2012](/Resources/data/migration_2012.csv) | [migration_2013](/Resources/data/migration_2013.csv) | [migration_2014](/Resources/data/migration_2014.csv) | [migration_2015](/Resources/data/migration_2015.csv) | [migration_2016](/Resources/data/migration_2016.csv) | [migration_2017](/Resources/data/migration_2017.csv) | [migration_2018](/Resources/data/migration_2018.csv) |  [zillow_data](/Resources/data/zillow_data.csv)  
## Technology
- **Software:** Jupyter Notebook, pgAdmin,   
- **Languages:** Python, JSON, SQL  
- **Dependencies:** Pandas, Matplotlib, SciPy  
- **Algorithms:**  


Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)## Objectives   
- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of our choosing.
- Optimize model training and input data to achieve desired model performance.

## Summary  
- Description of the data exploration phase of the project  
- Machine Learning Model   
- Database Integration  
- Description of the analysis phase of the project  

### Description of the data exploration phase of the project  
**Data Selection**  
Data selection entails making good choices about which data will be used. Consider what data is available, what data is missing, and what data can be removed.  

**Obstructions to progress**  
The first roadblock our team encountered was lack of data for our origional machine learning concept. Our first concept involved extracting data for our individual counties to compare against each other, then choose one county from another state to compare against our indivual results. Although, there is robust amount of data available through the [data.census.gov](https://data.census.gov) website, after filtering what was needed for our analysis, the amount of data remaining was not enough to provide a meaningful analysis. To overcome this obsticle we decided to broaden our analysis from four counties to all states in the U.S.. California is, now, our targeted data to compare against all the other states.  

**What data is available?**  
First, we account for the data we have. We use the columns method and output the columns.  

<img align="right" width="900" src="/pics/columns.png"><br/>
Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)  

Our output of column titles does **not** let us know what data we have. Scrolling back to the dataframe we can see the first row has the column description.  

<img align="left" width="900" src="/pics/df.png"><br/>
Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)

We refered back to the Excel file and expanded the cells to get the full description of the column values.  

<img align="left" width="900" src="/pics/excel.png"><br/>
File can be found in Resources/data/[2010_data.csv](Resources/data/2010_data.csv)

**What type of data is available?**  
Using the dtypes method, we confirm the data type, which also will alert us if anything should be changed in the next step. All the columns we plan to use in our model must contain a numerical data type.  

<img align="left" width="900" src="/pics/dtypes.png">
Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)  

Our data is, almost, all Objects and needed to be converted to numeric.  

**What data is missing?**  
Next, we see if any data is missing. Unsupervised learning models can’t handle missing data. If we try to run a model on a dataset with missing data, we’ll get an error. Pandas has the isnull() method to check for missing values. We loop through each column, check if there are null values, sum them up, and print out a readable total.  

<img align="left" width="250" src="/pics/null_values.png"><br/>
Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)

**What data can be removed?**  
We have begun to explore the data and have taken a look at null values. Next, determine if the data can be removed. Consider: Are there string columns that we can’t use? Are there columns with excessive null data points? Was our decision to handle missing values to just remove them?  

In our dataset, there are string type columns, and we made the decision that only a few rows have null data points, but not enough to remove a whole column’s worth.  

Rows of data with null values were removed with the dropna() method.  

# Drop null rows  
df = df.dropna()  

Duplicates were also be removed using the duplicated().sum() method.  

<img align="left" width="250" src="/pics/duplicate.png"><br/>
Code can be found in [census_2010.ipynb](Notebook/census_2010.ipynb)

To remove columns we used:  

# Remove columns
df.drop(columns=

**Description of data preprocessing**  
Data processing involves organizing the data by formatting, cleaning, and sampling it. For data processing, the focus is on making sure the data is set up for the unsupervised learning model, which requires the following:
- Null values are handled.
- Only numerical data is used.
- Values are scaled. In other words, data has been manipulated to ensure that the variance between the numbers won’t skew results.  

**Is the data in a format that can be passed into an unsupervised learning model?**
We saw that all our data had the incorrect type for each column. We had to use [pandas.to_numeric](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html) to convert our arguments to a numeric type. Also, we know that our model can’t have strings passed into it.  

To make sure we could use our string data, we transformed our strings of Region values in population data to 1, 2, 3, 4. We did this by creating a function that converts Northeast Region to 1, Midwest Region to 2, South Region to 3, West Region to 4, and anything else to 0. The function was then ran on the whole column with the .apply method.  

In our dataset on states housing cost, The scale for Median Income and Median Home Value is much larger than all the other values in the dataset. We adjusted this format by dividing by 1,000 to rescale those data points.  

**Data Transformation**
Data transformation involves thinking about the future. More times than not, there will be new data coming into your data storage (a place where raw data is stored before being touched), with many people working on different types of data analysis. We want to make sure that whoever wants to use the data in the future can do so.  

**Can I quickly hand off this data for others to use?**
The data now needs to be transformed back into a more user-friendly format. We converted the final products into a common data type CSV files. With our data being cleaned and processed, it is ready to be converted to a readable format for future use.  


### Machine Learning Model
**Description of feature engineering and the feature selection, including the team’s decision-making process**

**Description of how data was split into training and testing sets**

**Explanation of model choice, including limitations and benefits**

**Explanation of changes in model choice (if changes occurred between the Segment 2 and Segment 3 deliverables)**

**Description of how the model was trained (or retrained if the team used an existing model)**

**Description and explanation of model’s confusion matrix, including final accuracy score**

**How does the model address the question or problem the team is solving.**  

### Description of the analysis phase of the project

### Database Integration  
**Our final segment includes a fully integrated database, with the following features:**
- Stores static data for use during the project
- Interfaces with the project in some format (e.g., scraping updates the database, or database connects to the model)
- Includes at least two tables (or collections if using MongoDB)
- Includes at least one join using the database language (not including any joins in Pandas)
- Includes at least one connection string (using SQLAlchemy or PyMongo)
- Important If you use a SQL database, you must provide your Entity Relationship Diagram (ERD) with relationships.    

## Recommendation
**Recommendation for future analysis**   

## Limitations  
**Anything the team would have done differently**  

## Dashboard
The dashboard presents a data story that is logical and easy to follow for someone unfamiliar with the topic. It includes all of the following:
- Images from the initial analysis
- Data (images or report) from the machine learning task
- At least one interactive element
- Either the dashboard is published or the submission includes a screen capture video of it in action

## Presentation  
The presentation can be found in [Google Slides](https://docs.google.com/presentation/d/14h7wNLqN1Vh8AVsPMiOpv18YU4jbhMqiKdh0yhPtdns/edit?usp=sharing)  

## Sources  
### Description of the source of data  
**All .csv resources for our analysis were downloaded from [data.census.gov](https://data.census.gov) and [www2.census.gov](https://www2.census.gov)**  

Resources for data:  
- [population_data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/national/totals/nst-est2019-alldata.csv?#)  
- [2010_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2010&tid=ACSST1Y2010.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)  
- [2011_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2011&tid=ACSST1Y2011.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2012_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2012&tid=ACSST1Y2012.S2506&=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2013_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2013&tid=ACSST1Y2013.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2014_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2014&tid=ACSST1Y2014.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2015_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2015&tid=ACSST1Y2015.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2016_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2016&tid=ACSST1Y2016.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2017_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2017&tid=ACSST1Y2017.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)

- [2018_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2018&tid=ACSST1Y2018.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)  

- [migration_2010](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2010/state-to-state-migration/state_to_state_migrations_table_2010.xls)  
- [migration_2011](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2012/state-to-state-migration/state_to_state_migrations_table_2012.xls)  
- [migration_2012](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2012/state-to-state-migration/state_to_state_migrations_table_2012.xls)
- [migration_2013](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2013/state-to-state-migration/state_to_state_migrations_table_2013.xls)
- [migration_2014](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2014/state-to-state-migration/State_to_State_Migrations_Table_2014.xls)
- [migration_2015](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2015/state-to-state-migration/State_to_State_Migrations_Table_2015.xls)
- [migration_2016](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2016/state-to-state-migration/State_to_State_Migrations_Table_2016.xls)
- [migration_2017](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2017/state-to-state-migration/State_to_State_Migrations_Table_2017.xls)
- [migration_2018](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2018/state-to-state-migration/State_to_State_Migrations_Table_2018.xls)  

DBD created at :
- [quickdatabasediagrams.com](https://www.quickdatabasediagrams.com/)


### Description of visual sources:
**README.md video** was created with clips from: 
- [California faces housing 'crisis' amid extremely high rents](https://www.youtube.com/watch?v=kJH4wSW_X5A)
- [California housing crisis reaches boiling point](https://www.youtube.com/watch?v=Q4Zq5NmoWoM)
- [Can Big Tech Curb A Housing Crisis It Helped Cause](https://www.youtube.com/watch?v=e-cT0gQQsiw)
- [Goodbye, California! Longtime residents fleeing rising housing cost](https://www.youtube.com/watch?v=Q4t7GlCs2IY)  

**README.md header picture** was found at:
- [zerohedge.com](https://www.zerohedge.com/political/conservative-californians-leaving-droves-america-first-law-and-order-red-states)  

**Code pictures** were screenshots of:  
- Line x of [.ipynb]()  
- Line x of [.ipynb]()  
- Line x of [.ipynb]()

## Communication Protocols  
It is important to establish a communication protocol. We created direct messages for only team members in Slack at [final-project-jas](https://ucbdatasept19.slack.com/archives/CTXNA5K5G) and exchanged cell phone numbers where we created a group-text.  

- Instant commumnication will be done via text  
- Ideas and links will be done via Slack  
- Meetups will be held via Zoom  

In an emergency we will inform our group through our group-text and reach out to the staff by direct conversation in Slack.
