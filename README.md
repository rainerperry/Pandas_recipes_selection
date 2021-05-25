## Recipes Selection with Pandas - manipulation of large food dataset

### Overview

This project uses a large public dataset and Pandas to select a small subset of the data based on specific criteria. 

**Objective:** For a new cooking website, 30 unique modern dessert recipes are needed. A selection is to be made from a public dataset from food.com. 

*image: screenshot from Kaggle.com - selected dataset*

![Main Menu](./images/Kaggle.jpg?raw=true "Kaggle Screenshot")


The relevant data available on kaggle.com contains two datasets:

1. Recipe dataset (522,517 recipes from 312 different catagories)
2. Reviews dataset (1,401,982 reviews from 271,907 users)


## Data Import
Both files in csv format are imported into Pandas.

![Main Menu](./images/first.jpg?raw=true "Import of CSV Files")



## Data Manipulation

In order to find the right selection from more than half a million options, the data manipulations of both sets include: <br/>
<br/>
-value counts<br/>
-df.loc<br/>
-data type and field conversions<br/>
-left join <br/>
-saving to cvs and more<br/>


## Final Selection
A final dataset containing 30 dessert recipes is reached and the file saved as a csv file for future use.

![Main Menu](./images/final.jpg?raw=true "Final Selection")






