# SMBUD - Project

## Intro
This repository provides the material delivered as the final project of the Systems and Methods for Big and Unstructured Data course at Politecnico di Milano.

## Objective
The project specifications required searching for a publicly available dataset to be analyzed using a NoSQL technology, among the ones studied in the course. The set of technologies that were comprehensively covered from a practical point of view includes Neo4j, MongoDB, and Elasticsearch. Therefore, the objective was to put into practice the knowledge acquired during the course on one of these Database Management Systems (DBMSs), employing its corresponding querying language to extract valuable insights from the gathered data. More specifically, the request was to formulate and execute ten of these queries.

## Dataset Overview
The dataset selected for the analysis belongs to a bike-sharing company based in Chicago and was found on Kaggle at this [link](https://www.kaggle.com/datasets/karlachang/bike-share-divvy-datasets-from-nov2022-to-oct-2023/data). The web page contains a reference to a more complete [source](https://divvy-tripdata.s3.amazonaws.com/index.html), where data updated to November 2023 about rides performed by users of the bike-sharing system is available, divided by month. Whereas the technology adopted for the analysis is MongoDB.

## Repository Structure
The repository is structured as follows:
- `dump` folder contains a dump of the database
- `notebooks` folder contains 2 Python notebooks:
	- one dedicated to data cleaning
	- the other one for producing visualizations of query results
	- `data` folder: it is empty but should be filled with data available at the folder at this [link](https://polimi365-my.sharepoint.com/:f:/r/personal/10705522_polimi_it/Documents/Data?csf=1&web=1&e=EAosI3), which contains:
		- 3 CSV files used as the source of data for data cleaning process
		- `bike_sharing.csv` is the result of the data cleaning process	
- `queries` folder: it contains the text of the 10 queries generated in MongoDB
- `SMBUD Project - Laura Colazzo.pdf` is the report with all the details of the project development
