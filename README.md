# cloud-makeup



## => ETL PROCESS OVERVIEW

storage: s3
pipeline: glue
data warehouse: redshift

## Steps: 

### 1. Fetch data: 
	Python scripts to fetch data from (API, csv, json) and combine and load this data into s3
### 2. Transform the data:
	Transformations logic on glue
### 3. Load data:
	Pushing the transformed data into redshift
### 4. Build a visualization on top of redshift
	PowerBI

===========================================


## => DATASET

DATA SET (API): http://makeup-api.herokuapp.com/

