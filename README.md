# Roadmap 
## Day 1
- [Intro to `ggplot2`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#ggplot2-package)
- [Visualizing distributions](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#showing-data-distributions)
- [Changing the appearance of plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#controlling-the-appearance-of-graphs)
- [Graphing distributions across groups](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#graphing-distributions-across-groups)
- [Boxplots and violin plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#boxplots)
- [Scatter plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#scatter-plots)
- [Line plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day1#line-plots)

## Day 2
- [Introduction to `dplyr`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#introduction-to-dplyr)
- [Heatmaps](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#heatmaps)
- [Alluvial diagrams](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#alluvial-diagrams)
- [Primer on `tidyr`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#primer-on-tidyr)
- [Bar plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#dataviz-barplots)
- [Advanced bar plots and `lubridate`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day2#advanced-bar-plots-and--lubridate)

## Day 3
- [Coefficient plots](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#coefficient-plot)
- [Predictive probabilities](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#predictive-probabilities-plot)
- [Maps using `geom_polygon()`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#using-geom_polygon)
- [Introduction to `sf`](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#sf-package)
- [Choropleth maps](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#choropleth-maps)
- [Stamen map server](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#using-stamen-map-server-in-r)
- [Plotting density on a map](https://github.com/thereseanders/workshop-dataviz-fsu/tree/master/Day3#density-map-of-fine-particulate-matter-pollution)

# Info
## Software requirements
You should have both [R](https://www.r-project.org) and [RStudio](https://www.rstudio.com) installed on your machine. 

In this workshop, we will be using `R` together with the integrated development environment (IDE) RStudio. In addition to offering a "cleaner" programming development than the basic `R` editor, RStudio offers a large number of added functionalities for integrating code into documents, built-in tools and web-development.

## Prerequisites
There are no formal prerequisites for this workshop. However, I am assuming that participants have a basic understanding of `R` programming, in particular:

* Setting a working directory,
* Installing and loading packages,
* Reading and writing data,
* Basic data formats (scalar, vector, data frame),
* Basic variable types (numeric, character, factor, logical),
* Basic vector and data frame operations, such as subsetting, transforming variables, merging, reshaping, etc.

If you are unfamiliar with `R` or would like to brush up on your skills, take a look at my [intro to data management workshop](https://github.com/thereseanders/Workshop-DataManagement-tidyverse). The first two sessions go over basic `R` functionality and programming principles. The latter four sessions introduce data management operations using packages from the [`tidyverse`](https://www.tidyverse.org/packages/) suite. I also recommend taking a look at [`R` for Data Science](https://r4ds.had.co.nz) website and/or book for a great resource on learning `R` and data management. 

## Getting help
The key to learning `R` is: Google! This workshop will give you an overview over data visualiztion in `R`, but to become truly proficient you will have to actively use it yourself, trouble shoot, ask questions, and google! The `R` mailing list and other help pages such as [StackOverflow](http://stackoverflow.com) offer a rich archive of questions and answers by the `R` community. For example, if you google "recode variable in r" you will find a variety of useful websites explaining how to do this on the first page of the search results. Also, don't be surprised if you find a variety of different ways to execute the same task.

RStudio has a useful help menu. In addition, you can get information on any function or integrated data set in `R` through the console, for example:

```{r}
??geom_tile
```

## Credits
The teaching material is inspired by a course on *Statistical Computing and Data Visualization* by [Abbass Sharif](https://www.alsharif.info).

Packages used: 
[dplyr](https://dplyr.tidyverse.org), 
[fivethirtyeight](https://github.com/rudeboybert/fivethirtyeight), 
[gapminder](https://cran.r-project.org/web/packages/gapminder/index.html), 
[ggalluvial](https://cran.r-project.org/web/packages/ggalluvial/vignettes/ggalluvial.html), 
[ggmap](https://github.com/dkahle/ggmap), 
[ggplot2](https://ggplot2.tidyverse.org), 
[hflights](https://cran.r-project.org/web/packages/hflights/index.html), 
[lubridate](https://lubridate.tidyverse.org), 
[maps](https://cran.r-project.org/web/packages/maps/index.html), 
[pscl](https://cran.r-project.org/web/packages/pscl/index.html), 
[raster](https://cran.r-project.org/web/packages/raster/index.html), 
[readr](https://readr.tidyverse.org), 
[rmapshaper](https://github.com/ateucher/rmapshaper), 
[sf](https://github.com/r-spatial/sf), 
[tidyr](https://tidyr.tidyverse.org), 
[tmaptools](https://github.com/mtennekes/tmaptools), 
[viridis](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html).

Additional data sources used:
- Armed Conflict Location & Event Data Project (ACLED), [https://www.acleddata.com](https://www.acleddata.com)
- United States Environmental Protection Agency Air Data, [https://www.epa.gov/outdoor-air-quality-data](https://www.epa.gov/outdoor-air-quality-data)

## Contact
Creator and instructor: Therese Anders [(tanders@usc.edu)](tanders@usc.edu)

## License
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This project is licensed under the terms of the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

Feel free to use/adapt the teaching materials, but do not use them commercially/sell them, and share them under the same license.
