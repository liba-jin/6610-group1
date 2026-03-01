###### **Peter Adranly, Xuezhen Jin, Yung Chen Lin** 
###### **Group 1**
###### **AAI6610 Applied Machine Learning**
# 3D shape & Pharmacophore
## Overview
Our overall goal is to build a machine learning model to predict the potency of potential drug molecules against MERS and SARS.
### [Data](data)
The data folder contains the CSV file with the data used to train our models.
- antiviral_potency_2025_unblinded.csv
### [Notebooks](notebooks)
The notebooks folder has each of the individual codes that we did to both explore the dataset and begin the preliminary machine learning process.
- [XN_individual_check_in_1.ipynb](notebooks/XN_individual_check_in_1.ipynb) (Peter Adranly)
- [hw4_yungchenlin.ipynb](notebooks/hw4_yungchenlin.ipynb) (Yung Chen Lin)
- [w7.ipynb](notebooks/w7.ipynb) (Xuezhen Jin)
### SRC
The src folder holds our developing code for ongoing exploration and machine learning development.


## How to Run
### Step 1
Download the [Antiviral Potency](data/antiviral_potency_2025_unblinded.csv) dataset from the data folder.
### Step 2
Select which code youd like to run and download it from the src folder. Open that file through a platform like Visual Studio Code or Jupyter Notebooks.
##### *Additionally, you may need to set up your environment to work with Python when using Visual Studio Code*
### Step 3
Check to see if the path makes sense for where the dataset is on your device and run the code. If the code runs, then you have completed all the necessary steps!
### Step 4 (if needed)
A typical error that would occur is "No module named ______". This likely means that your environment isn't fully set up.
##### Run this in either a terminal open to the local file or in a cell within the code:
`pip install {Name of the missing module}`
Then try to run the code again.

