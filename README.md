# CO2 Data Analysis Project

This project aims to understand factors that affect global and national CO2 emissions by analysing data from the World
Bank’s World Development Indicators, covering 930 variables from diverse areas such as finance,
health, education, energy and environmental factors. Ultimately my goal is to use machine learning
to model this large dataset and look for possible complex relations between CO2 emission and other
variables. 
<br>
<br>

```
WB_Merge_Files.py
```
Merge two seperate data files to one file for analysis.
<br>
<br>

```
WB_Initial_Analysis.ipynb
```
Initial study of the complete set of World Bank data, looking at the structure and content of the data.
<br>
<br>
```
CO2_Data_Cleaning.ipynb
```

```
CO2_correlations.ipynb
```


I initially performed an exploratory data analysis with a small subset of the data:
CO2 emissions, GDP (Gross Domestic Product) and population. I looked at CO2 emissions per
county and its possible correlation with GDP and population over a period of 15 years. We also look
at conditional correlations by grouping countries into two GDP per capita bands. 

All three variables show a high and positive correlation (0.8-1) for most countries. Nevertheless we find that when looking
at countries with GDP per capita > $ 30,000 this trend is reversed. Most of these countries show a
decrease in their CO2 emission over the 15 year period.

