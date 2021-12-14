# Forest Cover Type Classification

## Abstract
The goal of this project was to use classification models to predict the types of forest covers in different wilderness areas around the United States of America based on certain factors.

## Data
The data was downloaded from **archive.ics.uci.edu** which contains cartographic variables.
- 581012 rows x 55 columns (Original)
- 536431 rows x 53 columns (Cleaned)


## Design

*Cleaning and Feature Engineering*

Dropped outliers and duplicates.
Modified some columns to reduce skewness and make the data more normally distributed.

*Target Imbalance*
Group some target classes together to reduce imbalance.

*Multiclass Classification*

Used OneVsRest classification to handle multiple classes in the target.

## Tools

Software Platform
- Jupyter Notebook

Programming Language
- Python
 
Python Libraries:
- Statistics libraries:
  - Sklearn
  - Statsmodels


- Data manipulation libraries:
  - Pandas
  - Numpy


- Visualization libraries:
  - Matplotlib
  - Seaborn
 

- Storage libraries:
  - SQLAlchemy 
  - Pickle

## Communication
Slides containing visualizations
