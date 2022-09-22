# Projects
Assortment of projects either completed projects or future ideas.

## For Fun Projects
These projects are just for me to experiment with various models and try stuff out.

##### Customer Segmentation via K-Means Clustering (Python)
Based on UCI ML Repo's Online Retail dataset, segmented the customer base according to recency, frequency, and monetary value (RFM) scores. This script includes data that isn't on my devices, so anyone can rip it and stick it on their own devices to try it out.

## MS Program Portfolios

The zip file contains projects completed during my data analytics master's program. It contains projects completed in Python, R, and PostgreSQL. Below is a compiled list of the folder's contents. Each file is presented in Word documents as work submitted during the program.

##### Predicting Credit Default Likelihood via Logit and Decision Trees (R)
Classic German credit dataset where the goal is to determine whether an applicant will default on their loan written in R. There are two methods outlined in the writeup of the project: a logistic regression with a cut-off value as the default indicator and a second model using a decision tree. This project is written using R Markdown formatted into a Word doc.

##### Stock Price Forecasting via ARIMA Model (R)
Stock price index forecasting using an ARIMA model for time-series data using R. The data used in the project comes from the UCI Machine Learning Repository, an open-source repository of more "real-world" data than Kaggle or similar sites (http://archive.ics.uci.edu/ml/datasets/Dow+Jones+Index#).

##### Predictive Analytics for Financial Fraud via SAS Data Miner Neural Network (SAS Enterprise Miner)
Exactly what it sounds like. A dataset provided by Lu [Lu, S.-ping. (n.d.). Use of Enterprise Miner & Multivariate Statistical Analysis to Build Fraud-Detection Models. https://support.sas.com/resources/papers/proceedings/proceedings/sugi24/Stats/p261-24.pdf] was analyzed using SAS Enterprise Miner via a neural network model. 

##### Basic Python Scripts (Python)
This file contains variety of basic Python scripts outlined below:
  - CTA1 performs integer, float, and modulo division given 2 input values
  - CTA2 takes a string input and performs T/F checks on whether all characters within are alphanumeric, alphabetical, digits, lowercase, or uppercase.
  - CTA3 returns the cost of a vehicle based on key-value pair in constructed dictionary.
  - CTA4 takes 5 input values and determines the average, maximum, and minimum values of the list.
  - CTA5 takes 3 string inputs and concatenates them in reverse order.
  - CTA6 takes 2 lists of 10 values and outputs in Cartesian product format (x,y).
  - CTA8 simulates a basic vehicle inventory program that allows a user to add or delete vehicles based on inputs and outputs inventory to a txt file ('vehicle.txt').

##### Northwind PostgreSQL
This document outlines the ETL process of creating and populating a PostgreSQL instance of the popular Northwind database. The write-up includes SQL scripts and screenshots of additional scripts.
 
##### Database Fundamentals
Outlines the process for the creation of an inventory database from inception to ERD to table creation and population in PostgreSQL.

## Professional Scripts
Currently a couple of scripts created after my master's program and used during my career at one point or another.

##### yolosplit (Python)
This script will walk through a folder containing Darknet YOLO (we used v4) object training data and splitting the image and bounding box txt files into their appropriate test/train splits. It's a godsend for when you have hundreds of GB of images that you are processing for your model.

##### testtrainsplit (Python)
Once you use yolosplit.py to create and populate the test/train folders, you can use this script to create your object txt file that contains the bounding box information for each image that gets processed during training the model.
