# Data Cleaning Assignment


## This project uses Python and JupyterLab to identify and address data quality issues in two datasets: US Census Annual Estimates and Google Search Monthly Activity.

## Dataset 1: US Census Annual Estimates

## Challenge 1: Population values were stored as text. I removed commas and converted them into integers.

## Challenge 2: There were 422 missing LocationID values and 9 missing GeoLocation values. I added columns to flag missing information without inventing replacements.

## Dataset 2: Google Search Monthly Activity

## Challenge 1: The Month column was stored as text. I converted it into a datetime format.

## Challenge 2: July 2025 was missing. I added the missing month, left its search count blank, and flagged it.

## Results: The Census dataset retained 477 records, and the Google Search dataset increased from 17 to 18 monthly records.

## Tools: Python 3.13, JupyterLab, pandas.