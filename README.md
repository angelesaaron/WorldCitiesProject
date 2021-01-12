# World Cities Project

Worked on a volunteer project for Jon Tesser of NYC & Co. Ran substantial statsical analysis and created assocaited data visualizations corresponding to Global World Cities dataset.

## Overview

* Ran statistical analysis on World City Tourism raw data from 2019-2028
* Wrote unique queries in R, to sort and manipulate city, country and regional data points
* Computed percentile metrics on included world, and U.S. cities
* Modeled tourism fluctuation and year-year change to a transformed regression and quantified associated metrics

## Process
* Received dataset with tourism information for about 600 cities, within 88 countries.
* Each city had the number of corresponding domestic and international overnight visitors from 2019 to projected 2028. 
* Had the freedom to get creative with my analysis, and pull whatever insights I deemed relevant.

## Data Manipulation
* Wrote standard data queries in R to sort and organize data by country and region
* Additional queries were included to compute year-year percent increase and specific focus metrics
* Used base R, dplyr and other packages

## Mapping Combined Tourism
* Conducted initial overview analysis on combined tourism within cities, countries and regions
* Sought to find an initial sense of a trend, and potential effect of COVID-19 pandemic.
![](/images/VisitorsBoxPlot.png)
  * Fig. 1:Boxplot mapping the number of total visitors in each Country (clustered cities) from 2019-2028.
![](/images/Visitors:year.png)
  * Fig. 2: Line graph indicating the number of visitors for each Region (clustered cities within clustered countries) from 2019-2028.

## Understanding Year-Year Change (amidst pandemic)
* Computed year to year percent increase for increments within 2019 to 2028 for combined travel
![](/images/PercInc-Total.png)
 * Fig. 3: Line graph indicating the year-year percent increase for intervals between 2019 and 2028
* Observed a percent decrease for most regions from 2019-2020 indicative of the effect of the COVID-19 pandemic.
* Year-year increase rises and then remains positive within the bounds of data
* Curve flattens out and the percent increases 0 as tourism appears to stabilize.


