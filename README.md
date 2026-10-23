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
most commonly base R (R Core Team, 2026), Python (Python Software Foundation, 
2026) and associated public-license packages. 

Specialist software tools: 

* Maps were generated using OpenStreetMap (Fellows & Stotz, 2025) or dependent 
data-mapping packages (see, for example, Loecher & Ropkins, 2015)
* bivariate polar plots (wind-speed versus wind direction versus pollutant 
surface plots) were generated using openair (Carslaw & Ropkins, 2012) 
* triangle/ternary plots were generated with loa (Ropkins, 2024)
* other plots were generated using ggplot2 and related packages (Wickham, 2026)
* data surfaces were fitted using mgcv (Wood, 2025) 
* source apportionment models were fitted using ESAT (Smith et al, 2024) and 
reference source profiles from respeciate (Ibarra-Espinosa & Ropkins, 2025)

## Addition: 

