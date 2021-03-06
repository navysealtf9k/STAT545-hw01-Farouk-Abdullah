README
================
Abdullah Farouk
2017-10-19

I highlight the various tasks I carried out, along with my thoughts on what was easy and difficult for me to achieve. Please refer [here](https://github.com/navysealtf9k/STAT545-hw-Farouk-Abdullah/blob/master/Hw05/Hw05.md) if you want to see what my analysis looks like.

Progress Report
===============

This format was thought of after peer reviewing the following [assignment](https://github.com/Jenncscampbell/STAT545-hw-Campbell-Jennifer/tree/master/hw02)

Factor management
-----------------

### Drop Oceania. Filter the Gapminder data to remove observations associated with the continent of Oceania. Additionally, remove unused factor levels. Provide concrete information on the data before and after removing these rows and Oceania; address the number of rows and the levels of the affected factors.

-   This was a fairly easy and straighforward task.
-   Helped me get my fingers wet playing with factors.

### Reorder the levels of country or continent. Use the forcats package to change the order of the factor levels, based on a principled summary of one of the quantitative variables. Consider experimenting with a summary statistic beyond the most basic choice of the median.

-   Once again this seemed fairly straightforward to carry out.
-   Chose IQR as my function of choice as it provides a good description of the variability in my quantitative variable of choice; life expectancy.

Visualization design
--------------------

### Explore the effects of arrange(). Does merely arranging the data have any effect on, say, a figure?

-   Noticed interesting things about the arrange function.
-   Learned about how and why the fct\_reorder function shows trends better graphically.
-   Had a hard time plotting the grpahs. TA Derek helped me figure out my incorrect call to the Rbrewer function.

Writing figures to file
-----------------------

### Use ggsave() to explicitly save a plot to file.

-   Chose to experiment with the png filetype and the pdf graphic device.

File I/O
--------

### Experiment with one or more of write\_csv()/read\_csv() (and/or TSV friends), saveRDS()/readRDS(), dput()/dget(). Create something new, probably by filtering or grouped-summarization of Singer or Gapminder. I highly recommend you fiddle with the factor levels, i.e. make them non-alphabetical (see previous section). Explore whether this survives the round trip of writing to file then reading back in.

-   Enjoyed this part.
-   Wrote and read back in csv.
-   Used rds functions to retain level reordering commands.

I want to do more!
------------------

### Pick a handful of countries, each of which you can associate with a stereotypical food (or any other non-controversial thing … sport? hobby? type of music, art or dance? animal? landscape feature?). Create an excerpt of the Gapminder data, filtered to just these countries. Create a new factor – you pick the name! – by mapping the existing country factor levels to the new levels. Examples: Italy –&gt; wine, Germany –&gt; beer, Japan –&gt; sake. (Austria, Germany) –&gt; German, (Mexico, Spain) –&gt; Spanish, (Portugal, Brazil) –&gt; Portuguese. Let your creativity flourish

-   Most time intensive component of the assignment.
-   Had difficulty gathering data from websites as they were not in tsv or csv form.
-   Had difficulty matching levels correctly. Figured out neat work around to overcome this.
-   Could not use kable to print out my table unfortunately.

NOTE
----

All citations for my code are in my link [here](https://github.com/navysealtf9k/STAT545-hw-Farouk-Abdullah/blob/master/Hw05/Hw05.md)
