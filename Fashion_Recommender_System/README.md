# mids-w207-marque-intae-nikhil-kisha-final-project-REPO
mids-w207-marque-intae-nikhil-kisha-final-project-REPO

Objective - predict the article_ids each customer will purchase during the 7-day period immediately after the training data period.

Link to Kaggle Project - https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/data

Team : Intae Kim, Kisha Kim, Nikhil PrasannaKumar, Marque Green

**Data Folder Structure**

* articles.csv - detailed metadata for each article_id available for purchase
* customers.csv - metadata for each customer_id in dataset
* transactions_train.csv - the training data, consisting of the purchases each customer for each date, as     well as additional information. Duplicate rows correspond to multiple purchases of the same item. 


**Notebook Files**
1. Final_Project_EDA.ipynb : This was used to do exploratory data analysis of above 3 data sets.
2. Final_Project_KNN_Model.ipynb : This notebook was used to run baseline collaborateive filtering method using KNN.
3. Final_Project_LightFM_Model.ipynb : This notebook was used to run LightFM, which is the main hybrid model ran for this project. Includes model evalualtion, hypertuning and final model result.


**Final Presentation** : W207-Final Project - H&M Personalized Fashion Recommendations.pdf