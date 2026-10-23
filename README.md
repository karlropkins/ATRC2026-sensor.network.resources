# ATRC2026-sensor.network.resources 

Open Research resources used for the ATRC2026 paper 'Sensor Network Workflows 
for Turning Big Data into Evidence: A Case Study of Lagos'

##  Data 

The data used in this work was downloaded from LAMATA’s Air Quality Network 
Application Programming Interface (API) service, but similar is also available 
via open repositories, including: 

* OpenAQ (https://openaq.org/) 
* IQAir (https://www.iqair.com/)    

## Preliminary Analysis

For this work, data was analysed using a combination of open-research software, 
most commonly base R, Python and associated public-license packages: 

* R Core Team, R v.4.6.1 (https://www.R-project.org/)
* Python Software Foundation, Python v3.1. (http://www.python.org) 

Specialist software tools: 

* Maps were generated using OpenStreetMap or dependent 
data-mapping packages
    * OpenStreetMap, R package v0.4.1 (https://CRAN.R-project.org/package=OpenStreetMap)
    * loa, R package v0.3.1.2 (https://CRAN.R-project.org/package=loa) 

* Bivariate polar plots (wind-speed versus wind direction versus pollutant 
surface plots) were generated using openair 
    * openair, project pages (https://openair-project.github.io/openair/) 
    * openair, R package v3.1.0 (https://CRAN.R-project.org/package=openair) 

* Triangle/ternary plots were generated with loa
    * loa, R package v0.3.1.2 (https://CRAN.R-project.org/package=loa)

* Other plots were generated using ggplot2 and related packages 
    * ggplot2 project pages (https://ggplot2.tidyverse.org/)
    * ggplot2, R package v4.0.3 (https://CRAN.R-project.org/package=ggplot2)

* data surfaces were fitted using mgcv
    * mgcv, R package v1.9-4 (https://CRAN.R-project.org/package=mgcv)

* source apportionment models were fitted using ESAT and 
reference source profiles from respeciate 
    * ESAT, Python/Rust package (https://github.com/quanted/esat)  
    * respeciate, R package v0.4.2 (https://github.com/atmoschem/respeciate)

## Additional: 

* Other data visualisation options 
    * VisQuill (https://visquill.com)
