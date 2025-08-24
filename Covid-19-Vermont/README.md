###### Note: this was a semester-long partner project I completed for a university statistics course. Only my contributions to the project are included here.

## Summary
Each group was tasked with examining the Covid-19 story of a partciular state within the U.S. My partner and I chose to study Vermont during the Covid-19 pandemic. We were asked to look at the data on a county level in order to make comparisons across the state. We collected data on Covid statistics, public health policies, and Vermont-specific information. The goal of this project was to tell a story using real-world data. 

## Objectives
* Research Vermont and what makes it unique
* Collect data accordingly
* Clean data into a useable dataset
* Conduct an exploratory data analysis
* Create linear regression models
* Conduct hypothesis tests
* Create data visualization to illustrate findings

## Datasets
All datasets are on the county level within the state of Vermont. Sources include New York Times, U.S. Bureau of Labor Statistics, Vermont's Department of Health, and U.S. Department of Agriculture.
* [NYT Covid-19 Data](https://github.com/nytimes/covid-19-data/blob/master/us-counties.csv)
* [Education Data](Datasets/Vermont_Education.csv)
* [Income Data](Datasets/Vermont_Unemployment.csv)
* [Poverty Data](Datasets/Vermont_Poverty2023.csv)
* [Demographics Data](Datasets/Vermont_Demographics.csv)
* [Vaccination Data](Datasets/vaccinations.csv)
* [Mask Use Data](Datasets/mask-use-by-county.csv)

## Conclusions and Limitations
Vermont had a very early and strict response to COVID-19 from the state government. In addition to this, the entire population of Vermont strongly adhered to the set guidelines. This can be seen with high mask usage and vaccination rates. On average, 66% of the population always wore a mask during the official mask mandate period. Additionally, 85% of the population is fully vaccinated, one of the highest vaccination rates in the country. These statistics are regardless of county. We found that Vermont is a very homogeneous state with little variation in variables on the county level. Due to this, it was difficult to analyze the true effects of masks and vaccines on the COVID cases and deaths. Therefore, we found that seasonality was the largest predictor in determining the peaks and falls in cases. This means that during the holiday season when people were naturally indoors, gathering, and traveling more is when we saw the most notable changes in cases and deaths. Overall, Vermont had a very strong reaction to COVID which allowed them to minimize the negative effects.

Some limitations in our investigations to consider are that Vermont is a very small state in both population and area. It is also a very rural state as a whole. While in real life this was advantageous because it allowed for a decrease in the spread of COVID, it led to many uninteresting variables. In addition, there are only 14 counties in Vermont, all of which are very uniform. Since there is little variability across counties, it was difficult to compare data strictly on a county level.

## Full Report
You can view the full analysis, including code and plots here:
[View Covid-19 Vermont Report](Covid-Project.html)
