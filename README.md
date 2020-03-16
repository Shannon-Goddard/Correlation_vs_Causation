[![news](/pics/header.png)](/vids/News_video.mp4?raw=true)  
 
#### Table of Contents  

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)  
[Recommendation](#recommendation)  
[Limitations](#limitations)  
[Sources](#sources)  
[Communication Protocols](#communication-protocols)  
[Project Roadmap](#project-roadmap )  

## Project Overview  
### **Reason the topic was selected**  
**There are many articles written about Californian’s  leaving due to the high cost of living. There are many news clips, like the ones we chose for our video embedded in our header. The reason this topic was selected, with our group living in California, it's personal. We live throughout the state, Southern California to Northern California, with a wide range of interests, backgrounds, experiences. We find commonality in the abiding weight in questioning, "Is it time to leave California?"**   

As a broad generalization, most people can afford to purchase a house worth about **3X** their **total (gross) annual income**, assuming a **20% down** payment and a moderate amount of other long-term debts, such as car or student loan payments. This best practice can be found at [mymoneyblog.com](https://www.mymoneyblog.com/4-different-rules-of-thumb-for-how-much-house-you-can-afford.html). As there are many similar "Best Practices" in home buying, We would like to keep a consistency throughout the analysis and use this one, three times total annual income. The consistency will make the analysis meaningful. 

With the best practice in mind and the median price of homes currently, as of 02/13/20, listed in San Bernardino County is **$350,000**, according to [zillow.com](https://www.zillow.com/san-bernardino-county-ca/home-values/), a single gross income of **$116,666.67** would be needed to purchase a **median price** home in **San Bernardino County**.  

Although, that number is flabbergasting enough, it fails when compared to surrounding California counties. These counties the median home prices are, easily, **doubled**.  Meaning, the gross annual income would, also, have to **double**.  
Pricing can be seen on [laalmanac.com](http://www.laalmanac.com/economy/ec37.php)  

**We performed analysis on the cost of housing in California that included**:  
- Median Home Price
- Median Household Income  

**Questions the team answers with the data**  
- What are the California median household prices in California expected to be in the next five years?  
- What are the California median household prices in California expected to be in the next ten years?  
- Based on the ["Best Practices"](https://www.mymoneyblog.com/4-different-rules-of-thumb-for-how-much-house-you-can-afford.html) in home buying, how much income would be needed to live in a median priced home in California at that time?  
- What are the top 5 states Californians are moving to?  
- How does California housing cost compare to those 5 states?  

**After our analysis, we answer:**
- Is it time to leave California?  

With the vast amount of data we used for our analysis, we devoloped a "user friendly" dashboard to diplay all the information. The dashboard presents a data story that is logical and easy to follow for someone unfamiliar with the topic. It includes a Leaflet.js Application Programming Interface (API) to populate a geographical map with migration data from [www2.census.gov](https://www2.census.gov). Each states migration flow is visually represented by a circle, where a higher migration population has a larger diameter. In addition, each state has a popup marker that, when clicked, shows the population and migration for that state. We, also, have an interactive HTML map. A drop down table allows the user to select a year. The map is then updated with the year selected information, each state, when hovered on, shows the median housing cost for that state.  

<img align="left" width="250" src="/pics/migflow2_map2018.png"><br/>
<img align="left" width="250" src="/pics/migflow2_map2018.png"><br/>
<img align="left" width="250" src="/pics/cost_map.png"><br/>
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>

## Resources  
- **Software:** Jupyter Notebook, PostGreSQL,   
- **Languages:** Python, JSON, SQL  
- **Dependencies:** Pandas, Matplotlib, SciPy, NumPy, Scikit-learn, hvplot, Plotly express  
- **Algorithms:** K-means, Random Forest Classifier, LinReg 
- **Data Source:** csv resources for our analysis were downloaded from [data.census.gov](https://data.census.gov), [www2.census.gov](https://www2.census.gov), and [zillow.com](https://www.zillow.com/)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2010_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2010&tid=ACSST1Y2010.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2010](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2010/state-to-state-migration/state_to_state_migrations_table_2010.xls)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[population_data](https://www2.census.gov/programs-surveys/popest/datasets/2010-2019/national/totals/nst-est2019-alldata.csv?#)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2011_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2011&tid=ACSST1Y2011.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2011](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2012/state-to-state-migration/state_to_state_migrations_table_2012.xls)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[zillow_data](https://www.zillow.com/research/data/)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2012_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2012&tid=ACSST1Y2012.S2506&=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2012](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2012/state-to-state-migration/state_to_state_migrations_table_2012.xls)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2013_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2013&tid=ACSST1Y2013.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2013](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2013/state-to-state-migration/state_to_state_migrations_table_2013.xls)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2014_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2014&tid=ACSST1Y2014.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2014](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2014/state-to-state-migration/State_to_State_Migrations_Table_2014.xls)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2015_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2015&tid=ACSST1Y2015.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2015](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2015/state-to-state-migration/State_to_State_Migrations_Table_2015.xls)

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2016_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2016&tid=ACSST1Y2016.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2016](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2016/state-to-state-migration/State_to_State_Migrations_Table_2016.xls)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2017_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2017&tid=ACSST1Y2017.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2017](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2017/state-to-state-migration/State_to_State_Migrations_Table_2017.xls)  

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[2018_data](https://data.census.gov/cedsci/table?g=0100000US.04000.001&y=2018&tid=ACSST1Y2018.S2506&t=Financial%20Characteristics%3AHousing%3AHousing%20Value%20and%20Purchase%20Price%3AIncome%20%28Households,%20Families,%20Individuals%29%3AIncome%20and%20Earnings%3AIncome%20and%20Poverty%3AMortgage%20Costs&vintage=2018&hidePreview=true&moe=false)&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[migration_2018](https://www2.census.gov/programs-surveys/demo/tables/geographic-mobility/2018/state-to-state-migration/State_to_State_Migrations_Table_2018.xls)  

## Objectives  
- Import, analyze, clean, and preprocess a “real-world” classification dataset  
- Select, design, and train a binary classification model for Deep Learning  
- Optimization methodology to increase model performance  

## Summary  
### [Machine Learning Model](/Machine%20Learning.md)  
[Data Preprocessing](#data-preprocessing)  
[Feature Engineering](#feature-engineering)  
[Training and Testing Sets](#training-and-testing-sets)  
[Model Choice](#model-choice)  
[Model Limitations](#model-limitations)  
[Model Benefits](#model-benefits)  
[Changes In Model's Choice](#changes-in-model-choice)  
[How the Model Was Trained](#how-the-model-was-trained)  
[Model’s Confusion Matrix](#model’s-confusion-matrix)  

## [Analysis](/Analysis.md)  
### Description of the analysis phase of the project  

### [Database Integration](/Database%20Integration.md)
**Our final segment includes a fully integrated database, with the following features:**  
[Stores Static Data](#stores-static-data)  
[Interfaces](#interfaces)  
[Tables](#tables)  
[Joins](#joins)  
[Connection string](#connection-string)  
[Entity Relationship Diagram (ERD)](#entity-relationship-diagram-(ERD))  
[Back to top](#table-of-contents)  
[Next Section](#recommendation)  

## Stores Static Data  
Once a clean data was obtained, parsed and sorted, it made it clear what types of tables could be useful for the project. Tables were then built in PostgreSQL to store static data. An ERD with a schema was first constructed and helped shape how and what questions we wanted the database to answer or insights to generate. Eventually, multiple tables were built to store static data.  

## Interfaces  
The database interfaces with our python notebook file where all the data loading and cleaning occurred. This was achieved by importing create_engine form sqlaclchemy; the information that sqlaclchemy needs to create a database engine.  

## Tables  
Multiple tables were generated to store static data as the project evolved. Tables include combined_ca_data, ca_analysis, housing_and_income, analysis_info, just to mention a few. For example, the ca_analysis table stores static data of all CA who moved to selected states between a given period, ordered by ascending order. Similarly, the analysis_info table stores median housing cost(monthly) data for all states.  

## Joins  
A left join using the database is performed on selected states from 2017 and 2018, left joining on the States which is a column found in both data sets.  

## Connection string  
A connection string using SQLAlchemy connects our python to our PostgreSQL.  

## Entity Relationship Diagram (ERD)  
<img align="center" width="400" src="/Data/Migration_FlowDB(2).png"><br/>
<br/>
<br/>
<br/>
<br/>  

## Dashboard
The dashboard presents a data story that is logical and easy to follow for someone unfamiliar with the topic. It includes all of the following:
- Images from the initial analysis
- Data (images and report) from the machine learning task
- Interactive elements
- Our dashboard is published on GitPages [Leaving California Dashboard]()  

## Presentation  
The presentation can be found at [Google Slides](https://docs.google.com/presentation/d/14h7wNLqN1Vh8AVsPMiOpv18YU4jbhMqiKdh0yhPtdns/edit?usp=sharing)  

## Recommendation
**Recommendation for future analysis**

A linear regression was performed using the census data for 2010-2018 as well as the Zillow monthly data from April 1996 to January 2020. These regression equations were very different from each other, mainly due to the amount of information that was available in each dataset. Future analysis could include comparing the home values in the upcoming months to see if either model was close to reality. Another venue for future analysis would be to perform similar linear regressions for the other 49 US states to see if any of those models are an accurate representation of the home values in the near future. Even more interesting would be to see how the inclusion of market fluctuations in the Zillow data will hold up when predicting home values in 2030 and beyond.

As for the RandomForest Classifier, it would be interesting to see if the model could accurately predict good and bad housing costs with data from the 2020 census.

**Anything the team would have done differently**

Our original plan was to gather data from 1980 through now, to be able to show the fluctuations in home value. We had also hoped to show that the cost of housing and annual income has increased, but not at the same rates and not at sustainable rates. However, the datasets that were available on the census.gov website only went as far back as 2010. If given more time, it might have been possible to get access to previous years and convert it into datasets that were similar to the 2010-2018 data.

## Limitations  
The creating of the migration flow map requires registration for a [Mapbox](https://www.mapbox.com/) account to generate an API key to allow rendering of maps on the browser. Mapbox does provide a free tier on their [pricing]( https://www.mapbox.com/pricing/), however a credit card is required for the sign up.  

## Sources  
**DBD created at : [quickdatabasediagrams.com](https://www.quickdatabasediagrams.com/)**  

**README.md video** was created with clips from: 
- [California faces housing 'crisis' amid extremely high rents](https://www.youtube.com/watch?v=kJH4wSW_X5A)
- [California housing crisis reaches boiling point](https://www.youtube.com/watch?v=Q4Zq5NmoWoM)
- [Can Big Tech Curb A Housing Crisis It Helped Cause](https://www.youtube.com/watch?v=e-cT0gQQsiw)
- [Goodbye, California! Longtime residents fleeing rising housing cost](https://www.youtube.com/watch?v=Q4t7GlCs2IY)  

**README.md header picture** was found at:
- [zerohedge.com](https://www.zerohedge.com/political/conservative-californians-leaving-droves-america-first-law-and-order-red-states)  

**Interactive map created with** [websitebeaver.com](https://websitebeaver.com/how-to-make-an-interactive-and-responsive-svg-map-of-us-states-capitals) **| Permissible** [License](https://github.com/WebsiteBeaver/interactive-and-responsive-svg-map-of-us-states-capitals/blob/master/LICENSE)  

**Code pictures** were screenshots of:  
- [.ipynb]()  
- [.ipynb]()  
- [.ipynb]()  

## Communication Protocols  
It is important to establish a communication protocol. We created direct messages for only team members in Slack at [final-project-jas](https://ucbdatasept19.slack.com/archives/CTXNA5K5G) and exchanged cell phone numbers where we created a group-text.  

- Instant communication will be done via text  
- Ideas and links will be done via Slack  
- Meetups will be held via Zoom  

In an emergency we will inform our group through our group-text and reach out to the staff by direct conversation in Slack.  

## Project Roadmap  
The project roadmap and description of all the project deliverables can be found in [Deliverables.md](/Deliverables.md)  

[Back to top](#table-of-contents)
