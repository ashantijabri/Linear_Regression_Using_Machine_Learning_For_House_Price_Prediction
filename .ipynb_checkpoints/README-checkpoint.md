<img src="https://hips.hearstapps.com/hmg-prod.s3.amazonaws.com/images/gettyimages-684098860-ii-1558361781.jpg?crop=0.667xw:1.00xh;0.0586xw,0&resize=980:*" style="float: left; margin: 20px; height: 200px">

### Overview

Across the country, housing prices are rising like never before - and faster than ever.

The *S&P CoreLogic Case-Shiller National Home Price NSA Index*, which tracks price changes of single-family homes, indicates that in November 2020, housing prices had risen 9.5 percent from the previous November. At the end of 2019, the average home was worth around \\$245,000. It’s now worth more than \$266,000, according to Zillow estimates.

This raises some serious questions about what our economy is doing, and why. The unemployment rate jumped in April 2020 to a level not seen since the 1930s — and still stood at 6.3 percent in January 2021. So where are people getting the money to buy homes? Why do they feel comfortable doing so? And what makes home sellers so confident that their homes will sell at increased rates during a global pandemic?

The saying goes that the market always corrects itself, but at what cost? We know that some of the factors behind the spike in home prices are due largely in part to all-time low-interest rates, and a ripe secondary market taking advantage of incredibly cheap mortgage-backed securities. This has created a sweet spot of sorts between supply and demand for homes, that has all the makings for a bursting bubble culminating with a massive refinance boom. 

The question for realtors, home buyers, sellers, and appraisers, then becomes "What are the proper metrics and criteria for pricing a home?" At this current time, following market trends make sense; do what your neighbors are doing, what your competitors are doing, and rake in the profits. But that is not a sustainable long-term strategy. Either housing prices continue to rise, as will inflation, or the market will correct itself, and we'll have to adapt to a new norm.

### Problem Statement

I hypothesize that currently, economic uncertainty has little effect on the overall housing market's profitability, and by being able to accurately predict house price in the form of a percentage relative to the mean of the national annual house price report of comparables, we will be able to account for future home price trends, given interest rate estimates. I will be using the Ames, Iowa housing dataset to make my predictions. This is a data set of single family homes sold between the years 2006-2010. This is extremely important for the success of our project, as being able to compare home pricing trends during the 2008 financial crisis will give us an even stronger basis for our hypothesis. We will be building a linear regression model for our predictions and analysis.

---

### Data Sets

* [`ames_clean`](./datasets/ames_clean.csv): Ames, Iowa Housing Data
* [`Interest Rates`](./datasets/rates.dta): Interest Rates From 1959 to 2014
* [`Unemployment Rates`](./datasets/unemployment_2020.xlsx): 2020 Unemployment Rates
* [`US_House_Data`](./datasets/us_house_data.csv): Annual Zillow House Prices

---

### Summary of analysis

Though it is possible to predict predefined home prices, more work must be done to approprietly predict future house prices, given a more robust list of features that include interest rate, unemployment, and mortgage-backed security rates. Our OLS model was most succesful for predicting price when compared to the Ridge and Lasso methods.

----

### Sources

https://www.aeaweb.org/content/file?id=1639

https://data.bls.gov/timeseries/LNS14000000

https://themortgagereports.com/70539/record-high-prices-record-low-mortgage-rates-during-covid

https://tradingeconomics.com/united-states/housing-index

https://www.fhfa.gov/AboutUs/Reports/Pages/US-House-Price-Index-Report-1Q2020-March.aspx

https://www.corelogic.com/insights-download/home-price-index.aspx

https://www.zillow.com/research/data/

https://search.proquest.com/openview/8445d673a16aae6e9d55721df681977a/1?pq-origsite=gscholar&cbl=30062

https://en.wikipedia.org/wiki/Federal_funds_rate

https://en.wikipedia.org/wiki/Timeline_of_the_United_States_housing_bubble

https://en.wikipedia.org/wiki/United_States_housing_bubble

https://files.zillowstatic.com/research/public_v2/zhvi/Metro_zhvi_uc_sfr_tier_0.33_0.67_sm_sa_mon.csv

