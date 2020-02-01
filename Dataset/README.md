* [Beginner Track](#beginner-track)
* [Science Track](#science-track)
* [Business Track](#business-track)
---
# Beginner Track
Dataset: San Diego Housing Information [Download Link](https://drive.google.com/drive/folders/1_dTPxfUIFTR_k40Iv5IVX-meTxmWDbL_?usp=sharing)

#### Prompt
> Experiment with the data given and see if there is a common factor among houses with similar living conditions in San Diego.
> - Clean the dataset in accordance with what rows are relevant to the research
> - Examine the overall distribution of data using different plots
> - Use linear regression to see what factors contribute to the living conditions of houses.

#### Metadata
> SD1970_population.csv
> - File format: .CSV (comma-separated values)
> - Size: 588 KB
> - Rows: 1267 rows

> SD1970_housing.csv 
> - File format: .CSV (comma-separated values)
> - Size: 932 KB
> - Rows: 1267 rows

> Key terms: Census Tract
> - Census tracts are small, relatively permanent statistical subdivisions of a County
> - Uniquely numbered in each county with a numeric code
> - Census tracts average about 4,000 inhabitants
>   - Minimum Population – 1,200, Maximum Population – 8,000

[Detailed Information](https://docs.google.com/document/d/1tqs9xzabHg8Mh-SiPP16YxR-csN06R_fBX_IVWyQD_M/edit?usp=sharing)

#### Guidence on Report
> 

Collected by the United States Department of Commerce. Bureau of the Census;\
Citation: University of California San Diego Data Services, 2005, "Block Group-Level Data, 1970: San Diego, California", hdl.handle.net/UCSD/21GY3 UNF:5:nZTGvV96cvLUqAgFl5TThg== University of California San Diego Social Science Data Collection [Distributor] V1 [Version]

---
# Science Track
Dataset: US Chronic Disease [Download Link](https://drive.google.com/drive/folders/1iOEwj4bPfopdtrzPdMft7plxDRHW5frC?usp=sharing)

#### Prompt
> 1. Clean the data. There are quite a few null values and some attributes names are relatively vague. It will help to clean up the data and state your assumptions.
> 2. In a manner, this is a dataset combined from different datasets, and is very open-ended to interpretation.
> 3. Use data visualization tools (Python Libraries, Tableau, etc.) to extract trends and patterns from the data. You must create an infographic with five or more related sections from any topic of interest. Are there any questions that are common among different topics? Or, do any topics have the same type of questions? NLP may be useful. Create visualization graphs to present your results.
> 4. Present your results in the form of a research proposal. Explore the data and come up with a hypothesis (ie California has a bigger issue with obesity chronic illnesses in comparison to other states). Perform Experimental Testing on your proposal. This will help back up your findings as well.
> 5. Prepare a report containing your results from the analysis. It should contain the following: Intro, data cleaning/pre-processing, visualizations (at least 3), analysis, proposal, conclusion.

#### Metadata
> Size: 154 MB 
> Rows: 519,718 rows
> Topics: 17 different Illnesses
> Attributes: 34 attributes including time values, location, topic, questions, data value and units, and confidence limits with different stratifications.
> Nulls: Null values are present (hint some columns are all null)

> Key terms:
> - StratificationCategory: different indicators (like race, gender, etc) that help filter responses for surveys to a particular demographic.   
> - StatificationId: ID terms that correspond to the categories.
> - ConfidenceLimit: Some values have uncertainty, thus a low confidence limit and high confidence limit are presented to give a range of possible values.

#### Guidence on Report
> 

Citation: “U.S. Chronic Disease Indicators (CDI).” U.S. Chronic Disease Indicators (CDI) | HealthData.gov, 27 Jan. 2020, healthdata.gov/dataset/us-chronic-disease-indicators-cdi.

---
# Business Track
Dataset: UBER Travel Time Analysis [Download Link](https://drive.google.com/drive/folders/1WcLKWilaMjGU-x8ezFVtyVM8-8O-PFIf?usp=sharing)

#### Prompt
> **Part 1**\
> In this track, you will have the opportunity to work with real-world UBER time-series data from the San Francisco area, spanning across the second quarter of 2019 **(04/01/2019 - 06/30/2019)**. The time-series data will be centered on **travel times** for UBER trips in the overall San Francisco area. Before you continue on, please review the metadata below. You will be required to **process**, **visualize**, and **analyze** the data while answering the following questions along the way:
> 1. For every Hotspot, recommend the appropriate BART station to get off of in order to minimize travel time. \
> a. Does the appropriate BART station change throughout the day? \
> b. Throughout the week? 
> 2. Compare and contrast travel times between different BART stations and Hotspots based on these factors: time of day, day of the week, and the direction of travel. \
> a. Consider restructuring the data on the basis of some of the previously listed factors.
> 3. What actionable recommendations are there for riders traveling from unique BART stations to Hotspots around the city? What about for tourists planning their way back home from Hotspots to BART stations?

> **Part 2**\
> In the first round, you were mainly interested in gaining a better understanding of the data that was available to you. However, one of the most important roles of a data scientist involves accurately predicting future data. You will now be asked to utilize **machine learning** to predict future UBER travel times on the various BART_Hotstpot / Hotspot_BART trips. Using the same data from the first round, complete the following objectives:
> 1. Develop a hypothesis for how travel times in San Francisco will change, if at all, in the future? \
> a. Provide justification based on your analysis from the first round as well as any information relevant to the unique nature of time-series data.
> 2. Define a forecasting model(s) most appropriate to the UBER time-series data? (Check out the [tutorial](TODO: Link) for hints on forecasting algorithms) \
> a. Develop datasets with future travel times for a minimum of **six** BART-Hotspot / Hotspot-BART trips. 
> 3. Prepare and submit a report with visualizations of your findings for consumption by a cross-functional audience. Consider the following tasks:\
> a. Indicate interesting trends throughout the travel times, both real and predicted. \
> b. Provide recommendations on how UBER can improve travel times to the given Hotspots and/or BART stations. 

#### Metadata
> barts_all.csv
> - Size: 819KB
> - Rows: 5456
> - Features: 8

> hotspots_all.csv
> - Size: 564 KB
> - Rows: 3973
> - Features: 8

> barts_hotspots.csv
> - Size: 352 KB
> - Rows: 1638
> - Features: 23

> hours.csv 
> - Size: 98 MB
> - Rows: 2,091,869
> - Features: 7

[Detailed information](https://docs.google.com/document/d/1dkL57TtXLGVWisro-Uiok8USebTi1NjkxygK_l_mBw0/edit?usp=sharing)

#### Guidence on Report
> 

Citation: TODO
