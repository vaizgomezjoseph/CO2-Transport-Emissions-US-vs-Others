# CO2-Transport-Emissions-US-vs-Others
Using the World Development Indicators (WDI) dataset, I compared CO2 emissions from transport for the United States against several different countries. A slideshow presentation of this project for general audiences is available [here](https://www.slideshare.net/JosephVaizGomez/co2-emissions-from-transport-united-states-vs-others).

## Introduction
As part of a [course](https://courses.edx.org/certificates/9c1add8702cf40bbbeae73785527be97) mini project I completed on edX, I explored the IMDB Movie and World Development Indicators (WDI) datasets. After initial exploration, I decided to work with the WDI dataset. I wanted to focus on a specific area of CO2 emissions attributed to the United States. In particular, I was curious to see if the dataset offered a way to measure the effects of ICE vehicle activity.

Upon review of the available indicators, I decided to examine the historical and per capita CO2 emissions from transport for all respective countries.

### Motivation
With awareness of the global climate crisis growing year by year, governments and world leaders are being pressured to take action. With respect to this issue, what is the role of the United States? In particular, how has the transport sector of the United States played a role, and how does it compare to several other developed countries? A better understanding of the United States's relative contributions to CO2 emissions from transport can inform decisions for its respective citizens, politicians, and workers in the transport sector.

The following research questions were written to guide the exploration efforts for this project:
1. How do the CO2 emissions from transport for the United States compare to other developed countries?
2. How does the United States compare to other developed countries regarding CO2 emissions **per capita** from transport?

## Background and Setup
### Dataset
The WDI is an extensive time-series dataset offered and maintained by the World Bank. According to the [World Bank website](https://datacatalog.worldbank.org/dataset/world-development-indicators), these development indicators are compiled from officially-recognized international sources and include national, regional, and global estimates for each. At the time of publication for this document, the dataset available on Kaggle included over 1300 unique indicators and a temporal range from 1960 to 2015.

### Technologies
- Jupyter Notebooks
- Python (3.7.4 or later)
  - Pandas (0.25.1 or later)
  - Matplotlib (3.1.1 or later)
  - NumPy (1.17.2 or later)
  
### Setup
After downloading the available 'DSE 200X Mini Project.ipynb' file or cloning the repository, run the notebook and follow the instructions within the notebook to run the desired cells. The datasets featured in this project can be found at the following links.
- [IMDB Movie Dataset](https://grouplens.org/datasets/movielens/)
- [World Development Indicators Dataset](https://www.kaggle.com/worldbank/world-development-indicators)

## Findings
Several other countries were selected to compare against the United States with respect to CO2 emissions from transport. Developed countries with relatively larger populations and data available from 1971 to 2011 were favored for comparison.
### 2011 and Cumulative CO2 Emissions from Transport
<div class="column">
    <img src="https://github.com/vaizgomezjoseph/CO2-Transport-Emissions-US-vs-Others/blob/main/Images/2011_Emissions.png" alt="alt text" width=425 height=500>
</div>
<div class="column">
    <img src="https://github.com/vaizgomezjoseph/CO2-Transport-Emissions-US-vs-Others/blob/main/Images/Cumulative_Emissions.png" alt="alt text" width=425 height=500>
</div>

- In 2011 alone (left), the United States contributed just over 1.6 million kilotons of CO2 emissions from transport, which far exceeds the contributions from the 7 other nations combined.
- The cumulative CO2 emissions from transport over a 41 year period (right) tell a similar story. Over that time period, the United States also produced more CO2 emissions than the 7 other nations combined.
- However, this is not the full story. Population is another variable to consider.

### Population Growth
<img src="https://github.com/vaizgomezjoseph/CO2-Transport-Emissions-US-vs-Others/blob/main/Images/Population_Growth.png" alt="alt text" width=1000 height=400>

- Over the same 41 year period that the United States contributed more CO2 emissions than the 7 other countries combined, the collective population of those 7 countries exceeded that of the United States.

### CO2 Emissions per Capita
<img src="https://github.com/vaizgomezjoseph/CO2-Transport-Emissions-US-vs-Others/blob/main/Images/Per_Capita_Emissions.png" alt="alt text" width=1000 height=400>

- For nearly every year in the recorded period, the average United States citizen contributed more metric tons of CO2 emissions from transport than the average citizen of any of the other countries.
