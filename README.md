# Data modeling with Apache Cassandra for a music app

# Description:
Business requirement:
Music store Sparkify requires to analyze user activity of their large dataset on their new music streaming app.
The company's objective is to improve customer service by having a highly available and fast data retrieval.

Objective:
1) To understand the business needs and then create ad hoc CQL queries in order to create an ETL pipeline

# Table of contents:
a) Jupyter Notebook containing Python scripts to create the ETL for Apache Cassandra queries:
- Data_modelling_Apache_Cassandra.ipynb

b) Event_data folder (directory of CSV files partitioned by date):
- event_data

c) A smaller event data csv file called event_datafile_new.csv that will be used to insert data into the Apache Cassandra tables :
- event_datafile_new.csv

d) Image of the denormalized data in the event_datafile_new.csv:
- image_event_datafile_new.jpg

# Installation:
To run the project in your local environment you'll need:
- Import python libraries:
import pandas as pd
import cassandra
import re
import os
import glob
import numpy as np
import json
import csv

- Jupyter Notebook
https://jupyter.org

- Apache Cassandra
http://cassandra.apache.org/download/
  
- Copies of the files mentioned above:

# Licence:
Open source. Simply do not plagiarize the code, or give credit where credit is due. 
