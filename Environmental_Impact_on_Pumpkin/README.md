# Background
Giant Pumpkin competitions have grown in popularity over time and have evolved into a highly competitive sport among farmers with substantial cash prizes and even an organizing body called the Great Pumpkin Commonwealth (GPC) [5] that establishes standards, eligibility requirements, and hosts regional competitions that enable qualification into an annual national championship. While giant pumpkins are the original, largest, and most popular GPC category, other plant species from the Cucurbitaceae (“Cucurbit”) family can be entered which includes field pumpkins, squashes, gourds, and watermelons. A niche but passionate community of growers, researchers, and aficionados have developed novel seed genetics as well as cultivation techniques in order to maximize the harvest weight of this family of gourds, with champion pumpkins frequently weighing in at over 2,000 lbs [8].

While there are many factors that a grower can control that contribute to the harvest weight of a pumpkin and other Cucurbits such as choice of seed genetics, cultivation method, and the skill of the grower, one of the most important factors in pumpkin plant growth and fruit production is environmental conditions such as temperature and precipitation. The goal of this research study is to investigate the impact of environmental factors on the weight of Cucurbits entered into official GPC competitions in the United States and determine whether certain climate conditions, and therefore geographic location, have an advantage over others when choosing where to grow a competitive giant pumpkin or cucurbits.

# Objective
Our research question is:
What impact do temperature and precipitation have on the weight of giant pumpkins and other cucurbits grown in the United States that were entered into official GPC competitions between the years 2013 - 2021.

# Data
In order to answer this question, we evaluated all competitive entries in official GPC competitions from 2013 - 2021 and modeled the official competition weight of the pumpkin or cucurbit as a function of the weather conditions it was grown under, while controlling for additional factors. Given weather is a complex system and pumpkins are grown over many months, we considered several different aggregated weather metrics such
as maximum daily temperature, minimum daily temperature, and amount of daily precipitation.

1. Pumpkin/Cucurbit Data
We obtained official GPC weights of pumpkins, tomatoes, squashes, and watermelons from the Giant Pumpkins data [4] set which was pulled from www.bigpumpkins.com. This data set included the city and state it was grown in, the year of the competition, and the type of the Cucurbit (Giant Pumpkin, Field Pumpkin, Giant Squash, Giant Watermelon, or Tomato).

2. City Coordinate Data:
City coordinate data was obtained from the World Cities Database [10] on Kaggle. This data was used to cross reference cities in the official GPC weight data set and determine their latitude and longitude.

3. Weather Data:
Weather data was obtained from National Oceanographic and Atmospheric Association Climate Data [2] which provided daily minimum temperature, daily maximum temperature, daily rainfall, and other climate data from weather stations across the United States. The coordinates of each pumpkin/Cucurbit was compared to the coordinates of all weather stations to determine its nearest weather station. The selected weather metrics were then aggregated over the growing months for each year and associated with that pumpkin/cucurbit record.


# Methods
Various regression models have been built and tested with the dependent variable being the cucurbit weight in pounds.


# Conclusion
Our research question aimed to determine the causal relationship between weather attributes and cucurbit weight. Unfortunately, our model did not have practical significance in regards to our weather variables. While we have determined that weather does have a statistically significant effect on pumpkin weight, as mentioned previously, the coefficients of our weather variables were so low that we cannot provide recommendations to growers of how their practices should change. Ultimately, while we can say that weather does have an effect on pumpkins, we cannot confidently say how different weather affects the growth of pumpkins.
We can suggest that further exploration needs to be done on factors that affect cucurbits. Due to the limitation of the data, other external factors that may have impacted the cucurbit weight were not included in our research, namely the specific growing methods individual growers used. There should be follow up research to explore the omitted variables such as external growing methods and irrigation systems to better understand the explanatory relationship between the omitted variables and the outcome variable.
