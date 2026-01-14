# CO2 Data Analysis Project

This project aims to understand factors that affect global and national CO2 emissions by analysing data from the World
Bank’s World Development Indicators, covering 930 variables from diverse areas such as finance,
health, education, energy and environmental factors. Ultimately my goal is to use machine learning
to model this large dataset and look for possible complex relations between CO2 emission and other
variables. 
<br>
### Initial report
`CO2_Research_Note.pdf` : Initial research note covering exploratory data analysis carried out using Python Panadas and Microsoft Excel. This covers data cleaning, merging and formatting data, creation of visualisations, and analysis and discussion.
<br>

### List of scripts

`WB_Merge_Files.py` : Merge two seperate data files to one file for analysis.
<br>

`WB_Initial_Analysis.ipynb` : Initial study of the complete set of World Bank data, looking at the structure and content of the data.
<br>

`CO2_Data_Cleaning.ipynb` : Cleaned the data ready for further analysis. Removed variables with insufficient data, and countries with insufficient data. Also restructured the data using melt and pivot to allow for easier analysis. 
<br>

`CO2_Corr_ML.ipynb` : Analysis of correlations between the 3 initial variables CO2, GDP and Population. Running of inital ML Models on the data.
<br>

### Data

Due to the size of the data files it is stored online, and should be downloaded before running the scripts.
<br>
[CO2 Data](https://drive.google.com/drive/folders/14tcpo-dSg8R4hXBqF8zxwPLYdOb994gq?usp=sharing)
