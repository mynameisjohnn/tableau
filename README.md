## Unit 1 | Assignment - Citi Bike Analytics

## Background

![Citi-Bikes](Images/citi-bike-station-bikes.jpg)

Congratulations on your new job! As the new lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers. 

## Task

**Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs to build a data dashboard, story, or report.  You may work with a timespan of your choosing. If you're really ambitious, you can merge multiple datasets from different periods. Try to provide answers to the following questions:**

* How many trips have been recorded total during the chosen period?
    294,928 trips
    
* By what percentage has total ridership grown? 
    1.90% from January 2017 to December 2017

* How has the proportion of short-term customers and annual subscribers changed?
    The number of customers and subscribers have increased over the year with peak usage in the summer time.

* Today, what are the peak hours in which bikes are used during summer months? 
    The peak hours are 8 AM and 6 PM which coincides with work commute times. 

* Today, what are the peak hours in which bikes are used during winter months?
    The peak hours are 8 AM and 6 PM which coincides with work commute times. 
    
* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
    Newport PATH, Newport Pkway, Sip Ave, Van Vorst Park, Warren St, Newark Ave, Exchange Place, Grove St PATH, Morris Canal, Hamilton Park. These areas are the top locations because they are in the main city area.

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
    Newport PATH, Newport Pkway, Sip Ave, Warren St, Newark Ave, Exchange Place, Grove St PATH, Morris Canal, Hamilton Park, City Hall. These areas are the top locations because they are in the main city area.

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
    Union St, West Side Light Rail, Danforth Light Rail, Journal Square, NJCU, Columbia Park, MLK Light Rail, Bayside Park, Bethune Center, JCBS Depot.

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)
    W 41 St & 8 Ave, W 22 St & 10 Ave, Liberty St & Broadway, W 13 St & 5 Ave, Spruce St & Nassau St, Broadway & Battery Pl, Broadway & W 24 St, W 24 St & 7 Ave, E3 St & 1 Ave, Centre St & Worth St. 
    
* Today, what is the gender breakdown of active participants (Male v. Female)?
    Male = 212,709
    Female = 61,294

* How effective has gender outreach been in increasing female ridership over the course of the past three years?
    The data only represents 2017, but the usage among Females seems to remain steady with the usage trends of the bikes. It does not flucuate as much as Males did during the year

* How does the average trip duration change by age?
    The average distance is dramtically higher for users born in 1998.

* What is the average distance in miles that a bike is ridden?

* Which Bikes (by ID) are most likely due for repair or inspection this year? 
    29242, 29542, 29522, 29646, 26273 as they were riden the most in 2017.

* How variable is the utilization by bike ID?

**Additionally, city officials would like to see the following visualizations:**

* A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

* A dynamic map that shows how each station's popularity changes over time (by month and year) -- with commentary pointing to any interesting events that may be behind these phenomena.

**Lastly, as a chronic over-achiever, you must also:**

* Find at least two unexpected phenomena in the data and provide a visualization and analysis to document their presence. 

## Considerations

Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused, concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes. 

## Assessment

Your final product will be assessed on the following metrics: 

* Completeness of Analysis 

* Analytic Rigor

* Readability

* Visual Attraction

* Professionalism

## Hints

* You may need to get creative in how you combine each of the CSVs. Don't just assume Tableau is the right tool for the job. At this point, you have a wealth of technical skills and research abilities. Dig for an approach that works and just go with it.

* Don't just assume the CSV format hasn't changed since 2013. Subtle changes to the formats in any of your columns can blockade your analysis. Ensure your data is consistent and clean throughout your analysis. (Hint: Start and End Time change at some point in the history logs).

* Consider building your dashboards with small extracts of the data (i.e. single files) before attempting to import the whole thing. What you will find is that importing all 20+ million records of data will create performance issues quickly. Welcome to "Big Data".

* While utilizing all of the data may seem like a nice power play, consider the time-course in making your analysis. Is data from 2013 the most relevant for making bike replacement decisions today? Probably not. Don't let overwhelming data fool you. Ground your analysis in common sense.

* Remember, data alone doesn't "answer" anything. You will need to accompany your data visualizations with clear and directed answers and analysis. 

* As is often the case, your clients are asking for a LOT of answers. Be considerate about their need-to-know and the importance of not "cramming in everything". Of course, answer each question, but do so in a way that is organized and presentable. 

* Since this is a project for the city, spend the appropriate time thinking through decisions on color schemes, fonts, and visual story-telling. The Citi Bike program has a clear visual footprint. As a suggestion, look for ways to have your data visualizations match their aesthetic tones.

* Pay attention to labels. What exactly is "time duration"? What's the value of "age of birth"? You will almost certainly need calculated fields to get what you need.

* Keep a close eye for obvious outliers or false data. Not everyone who signs up for the program is answering honestly.

* In answering the question of "why" a phenomena is happening, consider adding other pieces of information on socioeconomics or other geographic data. Tableau has a map "layer" feature that you may find handy. 

* Don't be afraid to manipulate your data and play with settings in Tableau. Tableau is meant to be explored. We haven't covered all that you need -- so you will need to keep an eye out for new tricks. 

* The final "format" of your deliverable is up to you. It can be an embedded Tableau dashboard, a Tableau Story, a Tableau visualization + PDF -- you name it. The bottom line is: This is your story to tell. Use the medium you deem most effective. (But you should definitely be using Tableau in some way!)

* Treat this as a serious endeavor! This is an opportunity to show future employers that you have what it takes to be a top-notch analyst. 

* Good luck!

## Copyright

Coding Boot Camp (C) 2018. All Rights Reserved.
