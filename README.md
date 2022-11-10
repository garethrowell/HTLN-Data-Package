# HTLN-Data-Package
----------------
Contains project notes and miscellaneous code for creating NPS HTLN data package components. The main areas are metadata (EML) and data validation including exploratory data analyses / data summary / certification documents for dataset publishing. Another objective is to write a set of standard operating procedures (SOP) for creating and publishing HTLN I&M data packages that might also be useful to others with similar datasets. The working example is the HTLN breeding bird protocol and database. Background info on HTLN breeding bird monitoring project is here:

https://www.nps.gov/im/htln/birds.htm

--------------------------------
# Notes

20221031

Successfully installed packages associated with NPSdataverse (yay!). 

https://github.com/nationalparkservice/NPSdataverse

20221110

Downloaded EML_Creation_Script.R from here

https://github.com/nationalparkservice/NPS_EML_Script

Created T-SQL script called BirdObservationThru2022.sql
Created .csv file called HTLNBreedingBirds_BirdObs.csv

Copied EML_Creation_Script.R to EML_Creation_Script_HTLNBreedingBirds.R

-----------------
# Tasks

Part I: Get up to speed with R...
x 1. Finish Grolemund (2014) Hands-On Programming with R
2. Complete R Tutorial - W3Schools
3. Complete Wickham and Grolemund (2017) R for Data Science
4. Take a deep dive into data visualization with Wickham's ggplot2: Elegant Graphics for Data Analysis (Use R!) on-line book

Part II: Learn about processing EML with R and that data sharing is a good thing...
x 1. Downloaded NPSdataverse packages for creating EML / data package
2. Study up on nationalparkservice repos - https://github.com/nationalparkservice/NPSdataverse; https://github.com/nationalparkservice/NPS_EML_Script,  https://github.com/nationalparkservice/DRR_Template, 
3. Custom NPS R packages provided through NPSdataverse to facilitate publication of datasets on the NPS Datastore

Part III. Create HTLN breeding bird data package
x 1. Create test .csv file from HTLN_Landbirds database
x 2. Downloaded EML_Creation_Script.R and copied a breeding birds local copy
3. ?



