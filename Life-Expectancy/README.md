## Predicting Life Expectancy Using Health and Economic Indicators
###### Note: this was a semester-long group project I completed for a university statistics course. Only my contributions to the project are included here.

## Summary
Each group was tasked with finding an interesting dataset to explore using linear regression. My group decided on a Kaggle dataset with life expectancy data, including other health, education, economic, and geographic information. Our main focus was on how we can accurately predict life expectancy using polio vaccination coverage, alcohol consumption, GDP per capita, and economic development status. Particularly, we hoped to investiagate how the quantitative varibales predicted life expectancy, and if this differed according to development status. 

## Objectives
* Clean data into a useable dataset
* Conduct an exploratory data analysis
* Transform any necessary variables
* Create multiple linear regression models
* Conduct hypothesis tests
* Construct confidence intervals
* Create data visualization to illustrate findings

## Datasets
One dataset from Kaggle was used. This data was already compiled from multiple sources for us. 
* [Life Expectancy Dataset](https://github.com/kalikadesai/data-analyst-portfolio/blob/main/Life-Expectancy/Life-Expectancy-Data-Updated.csv)

## Conclusions
To summarize our findings, our main predictors of life expectancy were polio vaccination coverage, alcohol consumption, and GDP per capita. We used a dummy variable for economic development status to investigate how the effects of these predictor variables differed between developed and developing countries. Our main results conclude that the baseline life expectancy for developed countries is higher than developing countries. In addition, we can see that the effects of polio vaccination, alcohol consumption, and GDP per capita do differ depending on development status. For developing countries, polio vaccinations and GDP per capita have the largest impact on life expectancy. In particular, GDP has the largest effect, seeing a significant increase in life expectancy with a 1 unit increase in GDP. Conversely, alcohol consumption and life expectancy in developing countries have a negative relationship. As consumption increases, life expectancy decreases. This exemplifies the negative health affects alcohol has and how it impacts longevity. For real world applications, this shows the importance of public health and sustainable economic growth in order to increase the life expectancy of of a developing country. For instance, increasing the spread of vaccination programs for polio, as well as other common diseases, in order to increase vaccination coverage can greatly improve life expectancy. Additionally, anti-drinking campaigns can prove to be effective in decreasing consumption. In terms of GDP, which has the biggest effect on life expectancy, investing in good infrastructure, healthcare, sanitation, and education can indirectly increase life expectancy by increasing a country's GDP. 

Looking at developed countries, we can see that the effects of polio vaccinations, alcohol consumption, and GDP per capita on life expectancy are smaller. For polio vaccinations, there is still a positive relationship, but life expectancy does not increase as much as in developing countries. This shows that while still positive, polio vaccinations do not increase life expectancy in developed countries as developing countries. For alcohol consumption, this was the most vague variable for developed countries. It's estimate was not statistically significant, indicating that there is no significant difference in its effect between developed and developing countries. This can speak to the phenomenon that richer countries tend to drink more alcohol. So here, GDP has more influence over alcohol consumption. Similar to polio, GDP per capita also has a smaller effect in developed countries. The fact that the effect of the predictor variables are smaller in developed countries speaks to the diminishing returns. We can see that as development status is reached, marginal improvements in health and economic factors have less of an impact. This can show the importance of resource allocation. While vaccinations and higher GDP are important in every country, they are especially important in helping developing countries increase their life expectancies the most.

## Full Report
You can view the full analysis, including code and plots here:
[View Life Expectancy Report](Predicting-Life-Expectancy.html)
