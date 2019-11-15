# tanzania-mobile-money

The train dataset contains demographic information and what financial services are used by approximately 10,000 individuals 
across Tanzania. This data was extracted from the FSDT Finscope 2017 survey and prepared specifically for this challenge. 

This dataset is the geospatial mapping of all cash outlets in Tanzania in 2012. Cash outlets in this case included commercial 
banks, community banks, ATMs, microfinance institutions, mobile money agents, bus stations and post offices. This data was 
collected by FSDT.

### The survey has five main objectives:

• To understand the behaviour (cash flow management, investing, saving etc.) and define
the financial service needs of consumers (individuals, farmers, business owners)

• To establish credible benchmarks and measure the effectiveness of financial inclusion

• To provide insights into policy, regulatory and market obstacles to access and usage
of financial services

• To provide insights which will feed into innovation within the financial and real sectors

• To highlight opportunities for policy review needed to drive financial sector
development 

### Methodology.

The methodology used in the survey was sampling.

Sampling Design - A multi-stage stratified sampling approach was used to achieve a representative sample
of individuals aged 16 years and older. The sample frame was based on the 2012 Tanzania
Population and Housing Census. The various stages of the selection of the sample are
discussed below.

Key sampling statistics - From the sampling done,they targeted 1, 000 Enumeration Areas, with 10 Interviews per in each area
they achieved to do the survey successfully in 998 areas. Their targeted Sample was 10,000 Respondents, 
they were able to achieve respondents which equate 9459 which is a 95% achieved despondence rate and only 7094 are available 
in the dataset. 

Data collection period: April to July 2017

In this report, I will visualize the Data with graphs. To cover the relationships the between the variable to be able to compare describe and define all the relationships from the results got from the survey.

### Results:

1. From Examination of my dataset. I can conclude that there are no missing values. The type of dataset we working on is a Pandas Dataframe with 37 data columns and 7094 entries. The data types in this dataset are float(2) and intent(35).

2. The data split is 56% to 44%, where 56% is females which are a total of 3972. Females that have mobile money are 1971 and those without mobile money are 2001. Males in the whole dataset are 3122 in total with 1959 having mobile money and 1163 without mobile money. The average age of a female with mobile money is 36 and the average age of a female without mobile is 39. The average age of a female with mobile money is 37 and the average age of a female without mobile is 43. 

3. - Males use mobile money more than females.
   - More young people use mobile money than elders so our data set is more skewed to the left.
   - Married people use mobile money more than divorced, widowed or single people and still more married people do not have mobile money than all the other relationship status people.
   - People that do not have land ownership use have the highest percentage on the piechart and do not use Mobile money, and those who do have land have the lowest percentage and do not use mobile money also.
   - With income types people without mobile money do not use mobile money besides in the trading type of income.

4. - People with access to Mobile services use Mobile money than those who do not have access to mobile services.

5. - From our map we are able to identify how our data is spread throughout our area which is Tanzania. From This we can conclude that most of the people are from the cost and their main source of income is Trading which can be justified by them being from the costal areas.
   - 68% of Tanzanians depend on only one income source, while the rest have more than one. 41% of Tanzanians depend on agricultural activities to meet their expenses, 20% on casual labor, 18% depend on other people and 14% on their own business activities. The 18% whoare dependents are mainly women.
   - From the map we are also able to identify that most of the people in our data set are frtom rural areas, this also justifies why more people do noy use mobile money.
   
### Conclusion: 

There are still so many factors that affect the rate of usage of mobile money in Tanzania. Some of the factors that can be looked at is the accessibility of money services like banking. 

Resources used : Finscope.pdf (https://www.fsdt.or.tz/wp-content/uploads/2017/09/FinScope-Tanzania-2017-Insights-that-Drive-Innovation.pdf)