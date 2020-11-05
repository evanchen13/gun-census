# US Gun Background Check & Census Data Analysis
This project was completed as part of Udacity's Data Analyst Nanodegree.

This analysis looks at data from two sources. The first is the [FBI's National Instant Criminal Background Check System (NICS)](https://www.fbi.gov/file-repository/nics_firearm_checks_-_month_year_by_state_type.pdf/view). Whenever an individual wants to undergo a transaction involving firearms or explosives, Federal Firearms Licensees (FFLs) have to input a background check into the system in order to make sure that the individual is eligible to complete the transaction. The data not only includes gun sales, but also other transactions such as concealed carry permits, rentals, private sales, and so on.

The other data comes from the US census and provides statistics by state for a variety of metrics. Most of this data is from the time period between 2010 and 2016.

In this analysis, I combine these two data sources to look at the relationship between gun background checks and demographic data. First, I plot the overall trend of background checks and gun sales over the time period represented by the data. Additionally, I zoom in specifically on handgun, long gun, and multiple-gun sales to see if the frequency of these particular transactions have changed over time. Next, I show which states have the most total background checks, as well as which states are growing the fastest in this area. Finally, I examine the general demographic profile of states with higher background checks. In particular, I focus on race, veteran status, immigrant status, education, income, and population density.

Here are the questions I answer in this analysis:
- What is the overall trend of background checks and gun sales?
- What is the overall trend of background checks split by gun category?
- Which states have had the largest overall and largest growth in background checks per capita?
- What demographic data correlates with background checks per capita by state?

## Requirements
- Jupyter Notebook
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scipy

## Installation
To get the Jupyter Notebook running, execute the following in the command line and select `gun-census.ipynb` from the Jupyter Notebook dashboard. The conda environment setup is optional; I have provided the base environment in `base.yaml`.
```
$ git clone https://github.com/evanchen13/gun-census.git
$ cd gun-census
$ conda env create -f base.yaml
$ jupyter notebook
```

## Additional Resources
- [BuzzFeedNews nics-firearm-background-checks GitHub Repository](https://github.com/BuzzFeedNews/nics-firearm-background-checks/blob/master/README.md)

## License
The contents of this repository are covered under the [GNU General Public License v3.0](https://github.com/evanchen13/gun-census/blob/master/COPYING).
