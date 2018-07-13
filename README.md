# registers-cdap-pipeline
Cask CDAP pipelines for registers

### Contains the folling piplines
- Import companyhouseData csv file to CDAP dataset
- Import Legal Unit data from csv to CDAP dataset
- Import VAT data from csv to CDAP dataset
- Import PAYE data from csv to CDAP dataset
- Import SIC07 data from csv to CDAP dataset

## Prerequsites
Cask CDAP sandbox sandbox environment installed

## Deployment Instructions
From the CDAP UI Create a black pipeline, then in the right hand corner select import then select one the JSON pipline files.

Once imported, open the File Step Properties and change the Path* to the location of the datafiles