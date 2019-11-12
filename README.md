According to the The U.S. Census Bureau, the term foreign-born refers to "anyone who is not a U.S. citizen at birth. This includes naturalized U.S. citizens, lawful permanent residents (immigrants), temporary migrants (such as foreign students), humanitarian migrants (such as refugees and asylees), and unauthorized migrants." 

As a naturalized U.S. citizen, I'm interested to analyze and visualize how the region-of-origin composition of foreign born populations in the United States compare state by state. The data sets I used were pulled using the tidycensus R package that allows users to interface with the US Census Bureau’s decennial Census and five-year American Community APIs to return tidyverse-ready data frames. 

# About the data

The data used is from the 5-year American Consumer Survey (2013-2017) estimate. Although the 1-year survey contains the most current estimates, it wasn't used because that survey only includes estimates for areas with populations of 65,000+ so the population size is small, making it less reliable than the 5-year survey estimates. The 5-year estimates were collected from all areas in the United States, between January 1, 2013 and December 31, 2017 making it the most reliable and least current estimates available. The 5-year estimates allows you to examine tracts and other smaller geographies while the 1-year doesn't. Here is a [link](https://www.census.gov/programs-surveys/acs/guidance/estimates.html) that goes over when to use the 1-year and 5-year estimates.

The "ACS2018_Table_Shells.csv" file is a variable mapping table that has information about census tables.
