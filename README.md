# Surf's Up
Weather analysis with Python, SQLite, SQLAlchemy, and Flask

## Overview
The purpose of this analysis was to examine weather trends (precipitation, temperature) in "June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round." In order to do that we performed the following:

- Accessed meteorological data in a SQLite file;
- Written queries to examine temperature data collected in the months of June and December;
- Calculated summary statistics (especially min, max, and average temperatures collected).

## Results
The collected data presents a pretty ideal location for a year-round surf-and-ice cream business.

![June Temps](https://github.com/tarini-mi7/surfs_up/blob/main/Resources/june_temp.png) ![Dec Temps](https://github.com/tarini-mi7/surfs_up/blob/main/Resources/dec_temps.png)

Summer and winter average temps differ by less than 4 degrees. This shows that the year-round weather isn't highly variable, and it's rarely too cold for a scoop of mint-chocolate chip and some tight curls.

![Temps](https://github.com/tarini-mi7/surfs_up/blob/main/Resources/temp_histogram.png)

Most temperature observations ranged within about 4 degrees on either side of this average. This says that the majority days are within close range of the average, and that the average temp isn't rare weather. Not only are you unlikely to encounter freezing waves, but your double-scoop cone of rocky road is also unlikely to melt before you can eat it.

![Precipitaion](https://github.com/tarini-mi7/surfs_up/blob/main/Resources/precipitation%20.png)

Less than 3/4 of daily rainfall measurements, over a three year period, show less than 0.14 inches. This data, modified from work done in the module, shows that average rainfall is fairly light. This means that you don't have to worry about bad weather at the beach or your triple-scoop sundae having an unwanted topping of rain drops.

## Summary
In short, Oahu is a great place to invest in a surf-and-scoop shop. The weather is pleasant and moderate throught the year. The lows are rarely too low and the highs are rarely too high. And while it may occasionally experience torrential downpours, most days are clear.

If one wanted to expand this analysis with more data, I would suggest collecting:

- Average hours of sunshine per day;
- Average wind speeds on the coast. These measurements would help determine quality of surfing and how many optimal hours of operation the shop could have.
