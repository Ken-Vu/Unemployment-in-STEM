# Unemployment in STEM



# Research Goals



# Dataset Used

To address this problem, we used data sets behind the fivethirtyeight story [The Economic Guide To Picking A College Major](https://fivethirtyeight.com/features/the-economic-guide-to-picking-a-college-major/) which can be found in the following GitHub repo: https://github.com/fivethirtyeight/data/blob/master/college-majors/women-stem.csv

All data is from American Community Survey 2010-2012 Public Use Microdata Series.

Our variables are as follows:

Header | Description
---|---------
`Rank` | Rank by median earnings
`Major_code` | Major code, FO1DP in ACS PUMS
`Major` | Major description
`Major_category` | Category of major from Carnevale et al
`Total` | Total number of people with major
`Sample_size` | Sample size (unweighted) of full-time, year-round ONLY (used for earnings)
`Men` | Male graduates
`Women` | Female graduates
`ShareWomen` | Women as share of total
`Employed` | Number employed (ESR == 1 or 2)
`Unemployed` | Number unemployed (ESR == 3)
`Unemployment_rate` | Unemployed / (Unemployed + Employed)
`Median` | Median earnings of full-time, year-round workers


# Tools Used

* Packages: dplyr, ggplot2
