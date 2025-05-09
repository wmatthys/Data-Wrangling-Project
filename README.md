# Data-Wrangling-Project
A Descriptive and Analytic Analysis of Crime vs. Unemployment in Nine L.A Neighborhoods


## Folder Outline
| Folders | Description |
|----------|----------|
| Data    | Main storage for project data   |
| Data/Raw   | Base datasets   |
| Notebook    | code for project   |
| Data_Dict    | Defined features of dataset  |
| Report     |   Final project code and analysis report |



## Table of Contents
- [Folder Outline](#folder-outline)
- [Project Overview](#project-overview)
- [Project Code](#project-code)
- [Sources of Data](#sources-of-data)
- [Data Dictionary](#data-dictionary)



## Project Overview
We are analyzing the effect that unemployment has on crime in various neighborhoods in L.A. This will be an analysis done on nine communities in the Los Angeles area and their respective unemployment rates. 


## Project Code
wmatthys_rtabares_DRAFT.ipynb (beta) and wmatthys_rtabares_project.ipynb (final) contains the code that was used to derive the analysis out of the data. 


## Sources of Data

- LAPD Arrest Data: (https://catalog.data.gov/dataset/arrest-data-from-2020-to-present) (csv file upload)
- Unemployment Census Tracts: (https://data.lacounty.gov/datasets/lacounty::unemployment-census-tract/explore?location=33.733638%2C-118.298767%2C6.48&showTable=true) (Scraped)



## Data Dictionary

| Column                     | Type    | Source            | Description                                                         |
|----------------------------|---------|-------------------|---------------------------------------------------------------------|
| Report ID                  | Numeric | la_crime2023       | Unique crime ID                                                     |
| Arrest Date                | Date    | la_crime2023       | Date of crime                                                       |
| Area ID                    | Numeric | la_crime2023       | Unique ID of Community                                              |
| Community                  | Text    | both              | Neighborhood crime was committed in                                  |
| Age                         | Numeric | la_crime2023       | Age of perpetrator                                                  |
| Sex Code                   | Text    | la_crime2023       | Sex of perpetrator                                                  |
| Charge Group Description   | Text    | la_crime2023       | Group of Charge (homicide, burglary, etc..)                         |
| Charge Description         | Text    | la_crime2023       | Specifics of charge (Ex. Robbery → Carjacking)                      |
| Address                    | Text    | la_crime2023       | Street address of crime committed                                   |
| Percent Unemployed         | Numeric | unemployed_grouped | Percent of population in the community that is unemployed           |
| Supervisor District        | Numeric | unemployed_grouped | District that the community is in (mainly used to group the data)   |


