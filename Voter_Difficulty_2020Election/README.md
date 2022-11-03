# Background
Every election cycle, accessibility and ease of voting is on top of our minds in order to encourage all voters to participate in the election process. Various campaigns focus on voter turnout, as the recent elections have been decided by very small margins. In order to promote voter turnout, we first need to understand the 2020 presidential election. We, as a non-profit data science organization specializing in political science, have received 2020 election data sets to further this research. American National Election Studies (ANES) is a foundation that provides high quality data from its surveys on voting, public opinion, and political participation in order to support research needs. Restricted time series data from ANES was used for our analysis.

# Objective
The analysis focuses on identifying whether voters from each party faced the same amount of difficulty in the 2020 presidential election. Our goal is to use data sets to compare difficulties that were faced in the 2020 presidential election, to help better prepare for the upcoming 2024 presidential election. Below key research question:
Did Democratic voters or Republican voters experience more difficulty voting in the 2020 election?
Results of this study could provide more in depth insight for the federal government election department, when creating policies on campaigns that impact voter turnout and ensuring that Democrats and Republicans voting difficulty is not biased. Furthermore, this could increase the equality in the voting process.

# Data
Data from the 2020 American National Election Study (ANES). The data set is observational and is based on a sample of survey respondents from the YouGov platform. ./Data

As a part of our analysis, we reduced the original data set to a smaller sample through data wrangling to eliminate unnecessary or incomplete information. The data set was reduced to four columns: “2020 Case ID”, “Party of Registration (Pre-election)”, “Voter Turnout 2020”, “How Difficult it was to Vote”. The most important variables in our analysis were difficulty voting (response variable) and the Party of Registration (explanatory variable). The variables for 2020 Case ID and Voter Turnout 2020 served to ensure that each voter had a unique ID in the data set and to validate that each respondent voted in the 2020 election. 

# Methods
From the ANES data, features have been selected from 1771 available variables. Then, test was run to compare the voter difficulty.

Few consideration have been made to identify an adequete statistical test. First, this is not two measures on the same sample given that one interview can be only either Democrat or Republican, not both. This allowed us to follow the unpaired test decision tree. Next, given the ordinal dataset, the data gathered is not in an interval or ratio scale. This has led us to choose to conduct the Wilcoxon Rank-Sum Test - Comparison version.

Null hypothesis tested is that the probability that a draw from difficulty faced by Democrats (D) ranks higher than a draw from difficulty faced by Republicans (R) is the same as the probability that a draw from difficulty faced by Republicans ranks higher than a draw from difficulty faced by Democrats.
(P(R > D) = P(D > R))

# Conclusion
Our study provided evidence that from a statistical perspective, both groups did not experience the same difficulty when voting in the 2020 presidential election. However, due to the type of test that we performed, the ordinal nature of the data, and the number of ties present in the question studied, the effect size we were measuring was far too small to have practical significance.

Our next step is to design a study that addresses some of the limitations that we encountered in this study to hopefully get a practical result in the future. To address these limitations, we hope to be involved in the complete data collection process, with the goal of collecting rich data that will have less ties to quantify the difficulty voting and be able to compare two groups more effectively.
