# Lede-Projects
--------
--------
## Project 1
#### Title:
Bus Zo-mentum
#### Goal Description:
I wanted to see if there was any relationship between bus speed and first-round voter preference in the 2025 NYC Democratic Mayoral Primary
#### Findings:
I found that there did exist a relationship between bus speed and support for Mamdani, but that it was limited to electoral districts along a specific borough's slowest line and mediated through the percentage of car ownership in that borough. 
#### Data collection summary:
I began by obtaining a shape file for NYC's election districts. Then, using the Board of Election's data, I created a table of election districts by the percentage of the vote that Mamdani won in the first round, before merging the two files using GeoPandas.<br/><br/> I then downloaded MTA bus speed data from OpenNYC and identified the slowest and fastest regularly scheduled line in each of the five boroughs. I manually collected the coordinates for each stop on each line, reformatted them, and coded them in GeoJSON.io. I downloaded the result in a shapefile and uploaded everything to MapBox. <br/><br/> Finally, I manually identified the election percentage of the district containing each stop and used Google Sheets to make scatterplots. I compared the R-value of the trendlines on each chart to determine how strong a relationship existed between the variables I tested.   
#### Data used for analysis:
#### Overview of the data analysis process
The data analysis for this project was relatively straightforward, relying mostly on scatterplots. In contrast, the data collection process was very time-intensive and cumbersome. 
#### A section about what new skills, approaches, etc you used, or where you grew the most during the project
This project ended up being way more than I could do as a first project. Although I began it first, I ended up completing it second. I learned a lot about QGIS, MapBox, shapefiles, GeoPandas, and integrating reactive maps into an HTML page. 
#### A section about things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)

--------
--------
## Project 2
#### Title:
How Have Jets Changed?
#### Goal Description:
I wanted to analyze the specifications of commercial jetliners from 1952 to the present day to attempt to identify design trends. 
#### Findings:
I found that while jets have changed in a number of ways since the start of the Jet Age, these changes are most apparent and widespread when it comes to fuel efficiency. For most other factors — wingspan, length, power, speed — design trends were more varied and depended on the role of the jet within a commercial fleet.
#### Data collection summary:
For each entry on Wikipedia's [list of purpose built commercial jet airliners](https://en.wikipedia.org/wiki/List_of_commercial_jet_airliners), I collected a jet's: *Country of origin, *year of airline service entry, *range (km), *wingspan (m),	*height (m),	*length (m),	*empty weight (kg),	*cruising speed (km/h),	*max take off weight (kg),	*max passengers,	*maximum fuel (l),	and *base price ($Million).<br/><br/>
Where possible, I sourced the data from each jet's Wikipedia entry, but when a specific data point was not available there, I consulted several other airplane databases such as [Aerocorner.com](https://aerocorner.com/). For data about a jet's base cost I used [Aerocorner.com](https://aerocorner.com/), while for the yearly average cost of a plane ticket and inflation adjustments I used data from [USInflationCalculator.com](https://www.usinflationcalculator.com/inflation/airfare-inflation/) and the CPI calculator from the [Bureau of Labor Statistics.](https://www.bls.gov/data/inflation_calculator.htm)
#### Data used for analysis:
All my data can be found [here.](https://docs.google.com/spreadsheets/d/1MlAUMLf1cMMMhZtKqxqs9LO-RRNZkLjxi4mG1rSFUuI/edit?usp=sharing)
#### Overview of the data analysis process:
After I collected my base data, I calculated new variables to compare each jet accurately. These were the *difference between a jet's empty weight and maximum take off weight, *liter/km,	*liter/100km/seat,	*the number of flights needed to recoup base costs at the average cost of a flight ticket,	and *cost per Km per passenger. For variables that involved a monetary figure, I made sure to adjust them to 2025 dollars. <br/><br/>
I then grouped each jet into one of three categories based on the maximum number of passengers it could hold. These were planes with more than 300 seats, planes with between 100 and 299 seats, and planes with fewer than 100 seats. The idea behind this was to use the number of seats as a proxy for whether a plane was intended for long-hauls, medium-hauls, or regional flights. <br/><br/> 
Where I was comparing only one variable or looking at industry trends as a whole, I created DataWrapper charts. Where I compared two or more variables or when I broke down a variable by the type of jet, I created scatterplot charts (and one combination line/bar chart) in Google Sheets.  
#### A section about what new skills, approaches, etc you used, or where you grew the most during the project
This was my first time using DataWrapper, which proved to be a steeper learning curve than I expected. I now feel more confident in my ability to make complex DataWrapper charts. In addition to that, I flexed and built new skills in Adobe Illustrator (where I designed models of various jets using schematics I found online), CSS, and HTML. Specifically in CSS, I learned how to make a small animation and how to format different types of content into grids. 
#### A section about things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)
I would have liked to done more statistical analysis of the data I collected and see if the trends I identified were actually statistically significant. I would have also liked to dive deeper into the factors behind the trends I identified, such as what seems to be pushing aerospace companies to invest in higher fuel efficiency vs increasing passenger capacity.

--------
--------
## Project 3
#### Title:
Funding a Governor
#### Goal Description:
#### Findings:
#### Data collection summary:
#### Data used for analysis:
#### Overview of the data analysis process
#### A section about what new skills, approaches, etc you used, or where you grew the most during the project
#### A section about things you tried to do or wanted to do but did not have the skills/time (but if you have more time you might do)
