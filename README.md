# Data Warehouse - Project
![alt text](https://user-images.githubusercontent.com/61973543/89605738-8eae2100-d86e-11ea-879f-42c5fe23ada9.png)
## Overview
This project is part of the Business Analytics Project for the chair of Management Information Systems of the TU Bergakademie Freiberg in Summer Semester 2020.

The goal is to deliver a documentation and the development process for a data warehouse and a dashboard starting with operational data. The data will then be extracted and transformed via Pentaho Data Integration - an Open Source tool for ETL - Processing and finally integrated into Tableau Desktop to illustrate interesting patterns in the data set.

### Technologies used
* Tableau Desktop 2020.1
* Pentaho Data Integration 8.1

## Structure
### Folders
* [DIM_Tables](https://github.com/antivism/BA_Project/tree/master/DIM_Tables) contains the dimensional tables created to enrich the initial dataset given which also can be found at https://www.kaggle.com/rajanand/import-and-export-by-india
* [Data_Modeling](https://github.com/antivism/BA_Project/tree/master/Data_Modeling) holds the created UML-Diagram and an ADAPT-model for the dataset
* [Pentaho_Process](https://github.com/antivism/BA_Project/tree/master/Pentaho_Process) contains the Kettle-process (.ktr) for Pentaho Data Integration
* [Tableau_Data](https://github.com/antivism/BA_Project/tree/master/Tableau_Data) contains the Tableau Desktop Worksheets (.twb) created by Tableau Desktop
### Documentation files
* [Project_Documentation.pdf](https://github.com/antivism/BA_Project/blob/master/Project_Documentation.pdf) holds the complete development process conducted in German.
* [ETL_Documentation.pdf](https://github.com/antivism/BA_Project/blob/master/ETL_Documentation.pdf) contains a complete step-by-step guide to develop the ETL-pipeline in Pentaho Data Integration.
* [Tableau_Documentation.pdf](https://github.com/antivism/BA_Project/blob/master/Tableau_Documentation.pdf) holds a step-by-step guide to develop a quick map view and time-graph based on the transformed data.
