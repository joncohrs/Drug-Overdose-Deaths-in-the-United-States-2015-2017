# **Analysis of drug overdose death in the United States from 2015-2017**
This repository contains analytical code, findings, and charts based off of the CDC's Vital Statistics Rapid Release. Specifically, this repository processes and analyzes the CDC's drug overdose death data by year, geography, and specific drug combinations.

## About the data
The analyses in this repository use data from the CDC's database. The "Multiple Cause of Death" codes are established at the [CDC database](https://www.cdc.gov/nchs/nvss/vsrr/drug-overdose-data.htm)

MCD Codes:
* Opioids (T40.0-T40.4,T40.6)
* Synthetic opioids, excl. methadone (T40.4)
* Heroin (T40.1)
* Natural & semi-synthetic opioids (T40.2)
* Cocaine (T40.5)
* Psychostimulants with abuse potential (T43.6)
* Methadone (T40.3)

## Data Files
Contains provisional overdose death counts from the CDC's Vital Statistics Rapid Release.
* `VSRR_Provisional_Drug_Overdose_Death_Counts.csv` : The default download from the Vital Statistics Rapid Release. Contains 12-month rolling provisional death counts by state, year, month, and type of drug.

## Analysis
The analyses were conducted in Jupyter Notebooks, using Python programming language.
* `drug_overdose_death.ipynb` : Reads the `VSRR_Provisional_Drug_Overdose_Death_Counts.csv` to produce Min/Max/Mean statistics and time-series charts for drug overdose deaths by year, geography, and specific drug combinations.
