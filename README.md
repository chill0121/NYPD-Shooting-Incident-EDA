# NYPD-Shooting-Incident-EDA
Exploratory Data Analysis of NYPD Shooting Incident Data

Using data from <https://catalog.data.gov/dataset>, and pulling the csv from, <https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic>.

The goal is to write a RMD file that cleans/transforms this data and sufficiently performs an EDA to better understand these shooting incidents from 2006 - 2021 (as of publish date). This RMD file will need to be knit by others so I will attempt to use minimal external packages, but I will list the ones used here as well as in the R setup chunk at the top of the RMD file.

I recommended knitting into HTML as it has been optimized for viewing in that format.
For whatever reason if you cannot knit the file or choose not to, you can simply open the .html file through github. It will direct you to a page of the raw HTML >> Right click anywhere >> Save As... >> open file.

Required R packages for knitting:
*install these packages before knitting using `install.packages('...')`*

- tidyverse
- lubridate
- ggplot2
- ggmap
- gridExtra
