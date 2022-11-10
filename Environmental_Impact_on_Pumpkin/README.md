# Background

Giant Pumpkin competitions have grown in popularity over time and have evolved into a highly competitive sport among farmers with substantial cash prizes and even an organizing body called the Great Pumpkin Commonwealth (GPC) that establishes standards, eligibility requirements, and hosts regional competitions that enable qualification into an annual national championship. While giant pumpkins are the original, largest, and most popular GPC category, other plant species from the Cucurbitaceae (“Cucurbit”) family can be entered which includes field pumpkins, squashes, gourds, and watermelons. A niche but passionate community of growers, researchers, and aficionados have developed novel seed genetics as well as cultivation techniques in order to maximize the harvest weight of this family of gourds, with champion pumpkins frequently weighing in at over 2,000 lbs.

While there are many factors that a grower can control that contribute to the harvest weight of a pumpkin and other Cucurbits such as choice of seed genetics, cultivation method, and the skill of the grower, one of the most important factors in pumpkin plant growth and fruit production is environmental conditions such as temperature and precipitation. The goal of this research study is to investigate the impact of environmental factors on the weight of Cucurbits entered into official GPC competitions in the United States and determine whether certain climate conditions, and therefore geographic location, have an advantage over others when choosing where to grow a competitive giant pumpkin or cucurbits.

**Objective** - Our research question is "What impact do temperature and precipitation have on the weight of giant pumpkins and other cucurbits grown in the United States that were entered into official GPC competitions between the years 2013 - 2021"

**Data Files**

* pumpkin.csv - We obtained official GPC weights of pumpkins, tomatoes, squashes, and watermelons from the Giant Pumpkins data set which was pulled from www.bigpumpkins.com. This data set included the city and state it was grown in, the year of the competition, and the type of the Cucurbit (Giant Pumpkin, Field Pumpkin, Giant Squash, Giant Watermelon, or Tomato).
* citycoordinate.csv - Data was obtained from the World Cities Database on Kaggle. This data was used to cross reference cities in the official GPC weight data set and determine their latitude and longitude.
* weather.csv - Data was obtained from National Oceanographic and Atmospheric Association Climate Data, which provided daily minimum temperature, daily maximum temperature, daily rainfall, and other climate data from weather stations across the United States. The coordinates of each pumpkin/Cucurbit was compared to the coordinates of all weather stations to determine its nearest weather station. The selected weather metrics were then aggregated over the growing months for each year and associated with that pumpkin/cucurbit record.


**Notebook Files**
1. data_preparation.ipynb : This was used to perform explanatory data analysis, select features, and data cleansing to be used for model building.
2. Environmental_Impact_on_Pumpkin.Rmd : This was used to build linear models and run statistical hypothesis tests to identify causal relationship.


**Final Report** : Environmental_Impact_on_Pumpkin.pdf

