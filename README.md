# COVID-19-Mexico-Clean-Complete
This repository contains data and code used to clean Covid 19 data from Mexico.

The original data used to get a final csv si from:

* Corona Virus Data: https://www.gob.mx/salud/documentos/datos-abiertos-152127
* Data Dictionary: https://www.gob.mx/salud/documentos/datos-abiertos-152127

## Objective
This project aims to generate a data set that specifies geographically the number of positive cases of SARS-CoV-2 in Mexico.
In the CSV file it is specified the cases by State, Municipality	and date. 

## Notebook
* *Covid-19 Mexico Data Cleaning.ipynb* - This notebook describes the process of cleaning, formatting and feature selection of the data.

## Data
* *Covid_19_Mexico_Clean_Complete.csv* - Final csv, data by state and municipality.
* *Catalogo.xlsx* - It contains all the information related to the columns and their meanings.

### Differences in results
According to the official results obtained from: https://coronavirus.gob.mx/datos/

The main difference between the official data and this dataset is in the recovered cases. This is because the Mexican government only considers outpatient cases when counting recovered cases. This notebook considers outpatient and inpatient cases when counting recovered people.

The second difference is some rows that contained nonsense information(I think this was a data collection error by the institution), these were eliminated.
