# Track Information
* [Beginner Track](#beginner-track)
* [Science Track](#science-track)
* [Business Track](#business-track)
---
# Beginner Track 
[back to top](#track-information)\
Dataset: San Diego Housing Information [Download Link](https://drive.google.com/drive/folders/1_dTPxfUIFTR_k40Iv5IVX-meTxmWDbL_?usp=sharing)

#### Background Information
> San Diego was a little different 50 years ago from what it is today, including the racial distribution of people living in the area and such. The Census Bureau collected data from different ‘census tracts’, or small blocks of areas in a city divided for census purposes. These tracts are further divided into smaller ‘blocks’ for more specific divisions. \
We will be using two datasets collected in this time period, that contain information about the same ‘census tract’. The SD1970_population table will contain features like age, gender, race and marital status of San Diego residents in the 1970s, and the SD1970_housing table will contain features like average listing price/monthly rent, number of rooms, and kitchen/plumbing situations of their houses in the same year. The identifying feature for each row will be the tract (“Tract Name”) and block number (“Block Group”) combined, of the represented areas.\
Our goal is to experiment with the data given below and see if there is a common factor among houses with similar living conditions in San Diego, and what kinds of features in the population distribution is associated with features from the housing distribution.

#### Prompt/Rubric
> 1. Cleaning: Clean the dataset in accordance with what rows are relevant to the research\
> 1.1. Dealing with null values, duplicate/ambiguous rows, datatype\
> 1.2. Column Manipulation: lump similar columns together and get rid of unwanted columns. **Add columns “Total Male Persons” and “Total Female Persons” to the population dataframe, and include each column values for the 1st row (Census Tract 1, Block 1) in the report**.\
> 1.3. Data should be optimally cleaned, with similar columns combined together/dropped
> 2. Visualization: Examine the overall distribution of data using different plots\
> 2.1. Plotting: How big are each block/residential area? **What block is the second common, following San Diego?**\
> 2.2. Pandas: How is the pricing of houses distributed in San Diego? **What's the average price of all houses in San Diego?**\
> 2.3. Pandas: **What block has the highest average price (based on the owner-occupied average value)?**\
> 2.4. Plotting: Focus on various categories and find out the distribution of different people living in San Diego. For example, what's the age distribution for males in San Diego like, for females; what's the distribution for individuals with different races living in San Diego, etc.?
> 3. Machine Learning: Use machine learning (linear regression) to see what factors are correlated to the living conditions of houses.\
> 3.1. Define the condition of a house and what columns are relevant to it.\
> 3.2. Does the gender of occupants affect how expensive the house they live in is? What about age? Or marriage status? Perform linear regression on 2 or more features in the population dataset.\
> 3.3. Find a meaningful relationship between the residents of a house and its conditions using different machine learning techniques.
> 4. Analysis - Final Report\
> 4.1. Minimum 2 pages, double spaced, ~12 pt with clear & legible font\
> 4.2. Include all aspects of the 3 steps given above with details on the procedure.\
> 4.3. Must be a clear and concise communication of end results and final analysis\
> 4.4. Minimal grammatical/vocabulary errors and consistent formatting

*Questions in bold will be answered for correctness in the final report!!!*

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

#### Guidance on Report/Presentation
> - Section 1: Data Cleaning/Preprocessing\
>   In this section, breifly explain what you have done cleaning the data, what challenges you have encountered and how you resolved them. Also, state any assumptions you made here.
> - Section 2: Data Visualization\
>   In this section, 

Collected by the United States Department of Commerce. Bureau of the Census;\
Citation: University of California San Diego Data Services, 2005, "Block Group-Level Data, 1970: San Diego, California", hdl.handle.net/UCSD/21GY3 UNF:5:nZTGvV96cvLUqAgFl5TThg== University of California San Diego Social Science Data Collection [Distributor] V1 [Version]

---
# Science Track
[back to top](#track-information)\
Dataset: US Chronic Disease [Download Link](https://drive.google.com/drive/folders/1iOEwj4bPfopdtrzPdMft7plxDRHW5frC?usp=sharing)

#### Prompt
> 1. Clean the data. There are quite a few null values and some attributes names are relatively vague. It will help to clean up the data and state your assumptions.
> 2. In a manner, this is a dataset combined from different datasets, and is very open-ended to interpretation.\
> a. Use data visualization tools (Python Libraries, Tableau, etc.) to extract trends and patterns from the data. You must create an infographic with three or more related sections from any topic of interest. \
> b. Are there any questions that are common among different topics? Or, do any topics have the same type of questions? Create visualization graphs related to NLP to help present your results.
> 3. Present your results in the form of a research proposal. Explore the data and come up with a hypothesis (ie California has a bigger issue with obesity chronic illnesses in comparison to other states). Perform Experimental Testing on your proposal. This will help back up your findings as well.
> 4. Prepare a report containing your results from the analysis. It should contain the following: Intro, data cleaning/pre-processing, visualizations (at least 3), analysis, proposal, conclusion.

#### Metadata
> - Size: 154 MB 
> - Rows: 519,718 rows
> - Topics: 17 different Illnesses
> - Attributes: 34 attributes including time values, location, topic, questions, data value and units, and confidence limits with different stratifications.
> - Nulls: Null values are present (hint some columns are all null)

> Key terms:
> - StratificationCategory: different indicators (like race, gender, etc) that help filter responses for surveys to a particular demographic.   
> - StatificationId: ID terms that correspond to the categories.
> - ConfidenceLimit: Some values have uncertainty, thus a low confidence limit and high confidence limit are presented to give a range of possible values.

#### Guidance on Report/Presentation
> - Section 1: Data Cleaning/Preprocessing\
>   In this section, breifly explain what you have done cleaning the data, what challenges you have encountered and how you resolved them. Also, state any assumptions you made here.
> - Section 2: Data Visualization\
>   In this section, make sure that your visualizations are informative, creative, and relevant. State what tools you used to make the visualizations.
> - Section 3: NLP Analysis\
>   In this section, explain any techniques you used in details, including but not limit to how you transfrom the text data, what feature  techniques you used, and what models you applied. State the performance of your model. What did you find out from your NLP analysis?
> - Section 4: Hypothesis Testing\
>   In this section, perform a experimental/hypothesis test. Clearly state your assumption and designs of your test. Explain the significance of this test. Be sure to include which metrics you track and how you would make a decision based on the experiment results.
> - Section 5: Proposal and Conclusion\
>   In this section, propose a valid proposal based on your previous analysis on this dataset. Clearly state any concepts and the significance of your proposal. Breifly state your conclusion and make sure that you use evidence from data anaysis/visualizations to support your conclusion or validity of proposal.

Citation: “U.S. Chronic Disease Indicators (CDI).” U.S. Chronic Disease Indicators (CDI) | HealthData.gov, 27 Jan. 2020, healthdata.gov/dataset/us-chronic-disease-indicators-cdi.

---
# Business Track
[back to top](#track-information)\
Dataset: UBER Travel Time Analysis [Download Link](https://drive.google.com/drive/folders/1WcLKWilaMjGU-x8ezFVtyVM8-8O-PFIf?usp=sharing)

#### Prompt
> **Part 1**\
> In this track, you will have the opportunity to work with real-world UBER time-series data from the San Francisco area, spanning across the first and second quarters of 2019. The time-series data will be centered on **travel times** for UBER trips in the overall San Francisco area. Before you continue on, please review the metadata below. You will be required to **process**, **visualize**, and **analyze** the data while answering the following questions along the way:
> 1. For every Hotspot, recommend the appropriate BART station to get off of in order to **minimize travel time**. \
> a. Does the appropriate BART station change throughout the day? Throughout the week? 
> 2. Compare and contrast travel times between different BART stations and Hotspots based on these factors: **time of day, day of the week, and the direction of travel**. \
> a. Consider restructuring the data on the basis of some of the previously listed factors.   
> 3. What actionable recommendations are there for riders traveling from unique BART stations to Hotspots around the city? What about for tourists planning their way back home from Hotspots to BART stations?


> **Part 2**\
> In the first round, you were mainly interested in gaining a better understanding of the data that was available to you. However, one of the most important roles of a data scientist involves accurately predicting future data. You will now be asked to utilize **machine learning** to predict future UBER travel times on the various BART_Hotstpot / Hotspot_BART trips. Using the same data from the first round, complete the following objectives:
> 1. Develop a proposal for how travel times in San Francisco may change in the future? \
> a. Provide justification based on your analysis from the first round as well as any information relevant to the unique nature of time-series data.
> 2. Define a **machine learning model(s)** most appropriate for predicting future trip travel times. Develop datasets with these future travel times for a **minimum of six** BART_to_Hotspot / Hotspot_to_BART trips.\
> a. Consider varying the measure of time (daily, weekly, monthly) used when forecasting future travel times. 
> 3. Prepare and submit a report with visualizations of your findings for consumption by a cross-functional audience. Consider the following tasks:\
> a. Indicate interesting trends throughout the travel times, both real and predicted. \
> b. Provide recommendations on how UBER can improve travel times to the given Hotspots and/or BART stations. 

*Note: Feel free to incorporate other resources and go beyond what the prompt is asking. Express your creativity throughout the project!*

#### Metadata
> barts_to_all.csv
> - Size: 1.6 MB
> - Rows: 10873
> - Features: 8

> hotspots_to_all.csv
> - Size: 1.1 MB
> - Rows: 7821
> - Features: 8

> barts_hotspots.csv
> - Size: 686 KB
> - Rows: 3258
> - Features: 23

> hours_q1.csv 
> - Size: 24.4 MB
> - Rows: 633172
> - Features: 7

> hours_q2.csv 
> - Size: 24.5 MB
> - Rows: 635565
> - Features: 7

[Detailed information](https://docs.google.com/document/d/1dkL57TtXLGVWisro-Uiok8USebTi1NjkxygK_l_mBw0/edit?usp=sharing)

#### Guidance on Report/Presentation
> - Section 1: Data Cleaning/Preprocessing\
>   In this section, breifly explain what you have done cleaning the data, what challenges you have encountered and how you resolved them. Also, state any assumptions you made here.
> - Section 2: Data Visualization\
>   In this section, 

Citation: © United States Postal Service 2015 MultiNet North America © 2006 – 2015 TomTom
“Data retrieved from Uber Movement, (c) 2020 Uber Technologies, Inc.
