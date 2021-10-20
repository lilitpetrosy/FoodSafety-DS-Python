# FoodSafety-Python
Python Data Science Project on analyzing all of San Francisco restaurant's food safety.

![](banners/FoodSafety.png)

## Introduction
In this project, we will investigate restaurant food safety scores for restaurants in San Francisco. The scores and violation information have been [made available by the San Francisco Department of Public Health](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores-LIVES-Standard/pyih-qa8i). The project focuses on extensive data explorations and visualizations. The following project inclusdes two notebooks: First notebook focuses on exploring the data and data pre processing while teh second notebook conducts statistical test and visualizations on the modified data.


## Notebooks
  
  ### **FoodSafety.ipynb**
  > In this part of teh subject we work with *[bzip2](https://sourceware.org/bzip2/)* type data files. These data files can be accessed in the *[data](https://github.com/lilitpetrosy/FoodSafety-DS-Python/tree/main/data)* forlder. 
  > *The content of the data folder.*
  > ![](banners/FoodSafetyData.png)
  > The next steps are looking into zip codes of the city of San Francisco and determining score association with the location of the restaurats of bus.csv 
  > dataframe.
  > ![](banners/zipcodemap.jpeg)
  > Forther data exploration consists of analyzing the Inspections dataframe and combining our modified dataframes together for later use in the coming notebook.
  
  ### **FoodSafetyB.ipynb**
  > The notebook focuses on finding patterns in the data through data visualizations. Findong correlation between the first score of the restaurant with their 
  > second score.
  > ![](banners/correlation)
  > Additionally we look at restaurant score distributions over time. The timeline for our comparisson is 2017, 2018, and 2019.
  > ![](banners/boxplot)
  > Some of our final visualizations include geometric data. In particular we have included geospatial hexbin plot of average scores of restaurants all over San 
  > Francisco.
  > Personal note, I have used the map myself when deciding my next restaurant ventures in San Francisco and it has not dissapointed so far 🍜. The plot shows the highest concentration of restaurants with high average restaurant ratings near the Chinatown area.
  > ![](banners/geoviz)

  > Im no food blogger, but if you are interested in good restaurants to dine in when visiting the bey area, here is a [good github list](https://github.com/vahaknp/curations/blob/master/locations/SanFrancisco.md) for you.
