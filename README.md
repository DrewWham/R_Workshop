# Introduction to Data Wrangling in R: Importing, Reshaping, Visualizing Data

## Before the workshop:
### 1)Download and install R and RStudio
Follow the below links download and install the appropriate version of R and R Studio for your operating system
* [R](https://www.r-project.org)
* [RStudio](https://www.rstudio.com/products/RStudio/)

### 2)Download the files in this repository to your desktop 
Download the workshop files by clicking the green "clone or download" button and then click "Download ZIP". Move the resulting folder to your desktop.

### 3)Download the workshop data
Download the data we will use in the workshop from the below link. The resulting file should be a compressed "2008.csv.bz2" file. Uncompress the file and move the file into the R_Workshop folder on your desktop. Once it is uncompressed you should have a 689.4mb file named "2008.csv" in R_Workshop folder. 
* [2008 Flight Data](http://stat-computing.org/dataexpo/2009/2008.csv.bz2)

## Opening R, setting working directory, Base R, downloading & loading packages
* [Base R - Cheatsheet](http://github.com/rstudio/cheatsheets/raw/master/base-r.pdf)
* [R Studio - Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/rstudio-ide.pdf)

`setwd("~/Desktop/R_Workshop")`

`source("Workshop_Packages.R")`

`install.packages("data.table")`

`library(data.table)`

## Data Structures,Loading Data, Indexing & Functions

`DT<-fread("2008.csv")`

## Data Wrangling

### Data Wrangling Package Cheetsheets
* [datatables](https://github.com/Rdatatable/data.table/wiki/Getting-started)([cheatsheet](http://datacamp-community.s3.amazonaws.com/6fdf799f-76ba-45b1-b8d8-39c4d4211c31))([cheatsheet2](https://s3.amazonaws.com/assets.datacamp.com/img/blog/data+table+cheat+sheet.pdf))
* [dplyr](http://dplyr.tidyverse.org)([cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf))
* [reshape2](https://cran.r-project.org/web/packages/reshape2/reshape2.pdf)([cheatsheet](http://rstudio-pubs-static.s3.amazonaws.com/14391_c58a54d88eac4dfbb80d8e07bcf92194.html))

### Data Wrangling with data.table

## Dates and Strings with lubridate and stringr
* [lubridate - Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/lubridate.pdf)
* [stringr - Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/strings.pdf)

## Data Visualization with ggplot2
* [ggplot2 - Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)
