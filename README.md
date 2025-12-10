# Data-cleaning-with-python

# 🏡 Airbnb Open Data – Data Cleaning Project

## This project demonstrates data cleaning and preprocessing on Airbnb open dataset using Python and Pandas.
## The goal is to clean raw listing data and prepare it for analysis or modeling.

# 📁 Dataset Information

## Dataset contains columns like:

### id

### name

### host id

### host_identity_verified

### host name

### neighbourhood group

### neighbourhood

### latitude / longitude

### country / country code

### price

### service fee

### minimum nights

### number of reviews

### last review

### reviews per month

### availability

### house_rules

### license



# 🎯 Project Tasks

This project focuses ONLY on data cleaning, not analysis.


## ✔ 1. Load the dataset

Using Pandas (CSV).


## ✔ 2. Explore the dataset

df.head()

df.info()

df.describe()

Checking missing values

Checking column datatypes


## ✔ 3. Clean Missing Values

Drop missing rows where important columns are empty

Fill less important text values with “Not specified”

Convert missing dates to NaT



## ✔ 4. Remove Duplicates

Checked based on id, host id, and name.


## ✔ 5. Export the Cleaned Dataset

Saved as:
cleaned_data.csv



# 🛠️ Tools Used

Python

Pandas

Google Colab
