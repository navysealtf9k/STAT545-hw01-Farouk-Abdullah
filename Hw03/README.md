README
================
Abdullah Farouk
2017-10-03

I highlight the various tasks I carried out, along with my thoughts on what was easy and difficult for me to achieve. Please refer to [here](https://github.com/navysealtf9k/STAT545-hw-Farouk-Abdullah/blob/master/Hw03/hwo03.md) if you want to see what my analysis looks like.

Progress Report
===============

This format was thought of after peer reviewing the following [assignment](https://github.com/Jenncscampbell/STAT545-hw-Campbell-Jennifer/tree/master/hw02)

Get the maximum and minimum of GDP per capita for all continents.
-----------------------------------------------------------------

-   This was fairly straightforward to compute.
-   I make use of pandoc tables to output my results and experiment with different fill colours in my graph.

Look at the spread of GDP per capita within the continents.
-----------------------------------------------------------

-   I created a spaghetti plot to get an inital feel of the spread across the different continents.
-   Didnt understand clearly what spread meant and therefore interpreted it as the difference between the highest values of gdp for a given continent over time.
-   Tried to plot my table of spread values but my code did not work. Ran into a lot of issues on that front. I commented it out as I was not sure how to fix it.

Compute a trimmed mean of life expectancy for different years. Or a weighted mean, weighting by population. Just try something other than the plain vanilla mean.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------

-   Computed a weighted measure of average life expectancy. I weighted each country's life exp by it's gdp per cap for the year.
-   Did so to try and see if increases in gdp led translated into increases in life expectancy (through the improvement of healthcare afforded to induviduals)
-   Used log of gdp per capita to control the effects of its large size on my caluclations.

How is life expectancy changing over time on different continents?
------------------------------------------------------------------

-   Fairly straightforward computations.
-   Begin my analysis by plotting variations through time, across continents and then tabulating my findings.

Report the absolute and/or relative abundance of countries with low life expectancy over time by continent: Compute some measure of worldwide life expectancy – you decide – a mean or median or some other quantile or perhaps your current age. Then determine how many countries on each continent have a life expectancy less than this benchmark, for each year.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

-   Task took me the longest time and prooved to be quite challenging.
-   Followed a prior example shown in class to segment the population by the benchmark value I calculated.
-   Created a table to keep count of the number of countries in each continent that were above/below the benchmark on a yearly basis.
-   Had difficulties plotting a graph of my results. The stacked bar graph was displaying the splits incorrectly. Fixed it after consultation with TA Katy, who recommended I feed in the data directly rather than doing so by assigning it to a variable and then calling the variable.

I want to do more
-----------------

-   Experimented with pandoc tables and tried to use (unsuccessfully as I didn't have any regression output) stargazer to generate tables.
-   Also experimented with the side by side layout in the first task.

NOTE
----

All citations for my code are in my link [here](https://github.com/navysealtf9k/STAT545-hw-Farouk-Abdullah/blob/master/Hw03/hwo03.md)
