# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## 1. Overview of Project
   ### 1a. Purpose
   For this project, Louise required an analysis and visualization of varying campaigns in relation to their launch dates and funding goals, to understand the reasoning behind those which succeeded and failed. In doing so, the purpose of this analysis was to distinguish patterns or trends in these campaigns, to better guide Louise in her own ventures. 

## 2. Analysis and Challenges

### 2a. Analysis of Outcomes Based on Launch Date

<img src="https://github.com/leilacf/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png">

   In the above line chart, one can see that May (111) and June (100) had the highest peaks of "succesful theatre campaigns" before hitting a rapid and continuous downward slope with a reducing success rate until October, during all of the years documented. This could indicate that the months towards end of spring and begining of summer are the best to launch a campaign. There was also a relatively low failure rate during this time as in May only 31% of campaigns failed on average while 68% of campaigns succeeded. Simimarly in June, there was a 32% failure rate with a 65% success rate. This can be compared with one of the lowest months of succesful campaigns, December, with only 37 succesfully launched campaigns. Campaigns launched in Decemeber, had a 46% failure rate and 49% success rate, however this month had the lowest amount launched--demonstarting that the winter/holiday time could be quite a rocky and unstable time to launch a campaign as historically based on this data, there seems to be a close split between failure and success. Therefore, based on this data visualization, one can conclude that all months contain risks and external variables that can affect the success rate of a campaign, but certain months such as May and June could prove to be more favorable months for a launch. 
          

### 2b. Analysis of Outcomes Based on Goals

<img src="https://github.com/leilacf/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png">

   The line chart above analyzes the success and failure rate of campaigns based on their goal amount for production in USD. One can see how for the ranges of "less than $1000, $1000-$4999, $5000-$9999, and $10000-$14999" there was a higher percentage of successful campaigns than there was for failed ones. The range of "$1000-$4999" had the most campaigns (534) demonstrating that many individuals might believe that this range is a feasible goal, in comparison to other ranges. The range of "$15000-$19999" has a success and failure rate of 50%, creating an even split. This may be due to the fact that this approachs a larger goal of $20,000, which may make investors and donators more meticulous with their financial decision-making. Lastly, the ranges from "$20000-$24999" until "greater than $50000" mostly have higher failure rates than success rates, and have fewer campaigns falling into those goal categories. Therefore, this data is very useful in demonstarting to indivduals like Louise, which ranges are more attainable and lead to higher chances of success rather than failure as it provides concrete parameters for the goals of these projects.

### 2c. Challenges and Difficulties Encountered

   In this analysis, I was not faced with any particular challenges but I can highlight a few instances that I believe can result to be difficult. 
   - The "deadline" and "launch" dates contained Unix timestamps rather than dates in the standard format, when attempting to convert this, if one accidentally alters the original timestamp, then the conversion will be incorrect
   - In creating the "Outcomes based on goals" chart and graph, the formula and input of the data was quite tedious and easy to mistype or copy a wrong number. Therefore, I can see how this could become a difficult task rapidly if not enough attention is paid to detail

## 3. Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - Firstly, the month of May had the most success in launched campaigns and highest amount of total campaigns (166). This could prove to be a favorable month to launch, unless too many campaigns take note of this and launch during May/June which would result in an increase of demand for funding, an increase of supply of possible campaigns, and increased competition--creating more difficult circumstances for success.
  - The months of January, March, September, November, and December had the lowest amount of total campaigns launched, low failure rate, and a range of 58%-61% success rate (aside from December which was 49%) which could indicate that December is a rather unstable time to launch, while the other months mentioned could increase chances of success as there is historically, less campaigns and therefore, less competition. 

- What can you conclude about the Outcomes based on Goals?
   - The data demonstrated that the projects were most succesful when their goal range was between "less than $1000" and "$10000-$14999". Once the goal approaches $20000, the chances are reduced to 50% success and failure as this data point could mark the beggining of what is viewed as too high of a goal. From this range onwards, most campaigns fail in reaching their goal rather than succeed. Lastly, there were two outlier categories, "$35000-$39999" and "$40000-$44999" which had a 67% success rate and a 33% failure rate. This data does not align with the trend established earlier, and is the product of only 6 succesful campaigns out of a total of 1047. These 6 campaigns cannot be used to accurately predict the success of other projects that have goals with higher ranges as they are unique points in this data set.

- What are some limitations of this dataset?
   - Certain limitations in this data include: geography and cultural bias, time constraints, and sample size. As for geography, data on launched campaigns was gathered from various countries which helps in diversifying the data and highlighting which types of projects were most succesful globally, but this introduces the risk of cultural bias. Perhaps, plays did not have much success in a certain country in a particular point in time, but soared in a different nation at the same point in time. This does not necessarily indicate that those plays should fall in the category of "failure" as an objective fact, but rather could be highlighting the preferences in types of entertainment/projects per country. Therefore, this can complicate the interpretation of the data if a multitude of factors are not included. Moreover, the data ranges from the year 1970-2017 but it is not consistent chronological data as the years jump around. Therefore, if one wanted to study a particular range such as "1970-1975", that cannot be done with this data set as the next year that is documented goes from "1970-2009". The large gaps in years documented, can place a constraint on being able to measure changes over time--therefore, a more detailed longitudinal study should be used for further research. Lastly, the sample size of this data set was a limitation stemming from the lack of years in documentation. A larger sample size is required to ensure that the sample can represent a population accurately. This is of critical importance in Louise's analysis as she is attempting to gather this information and apply it to a larger understanding of patterns in succesful and failed campagins, globally.

- What are some other possible tables and/or graphs that we could create?
   - Additional tables and graphs that could have been created include pie charts by country of types and % of succesful projects and failed projects, and stacked bar charts.
