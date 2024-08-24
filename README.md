# Python Data Analysis With Automation

## Project Overview
The project was looking at  both HIV assays that reflexed from the Biorad instrument to the Geenius instrument. Any reactive result on the original machine automatically gets reflexed for confirmatory testing on the Geenius. The goal of the automated data pull was to see if there were any anomalies in the confirmatory test, i.e. a reactive result on the screen to a non-reactive result for confirmation.  If there were a consistent pattern of reactive to non-reactive this then is a red flag for the lab to see if the lab needs to re-calibrate the machines. 

## Data Sources
The SQL script pulls data from the following tables:

Order Table: Contains information on orders placed. <br/>
Results Table: Holds the results of the tests performed.<br/>
Assay Table: Provides details on the assays used. <br/>

## Python
Once the data is extracted using SQL, it is cleaned and processed in Python. The cleaning process involves standardizing formats, removing duplicates, and ensuring data accuracy.

## Automation
Finally, once the data has been approved by the lab manager the program is then automated using a batch file along with Task Scheduler. The program then ran on the 15th of every month.  


