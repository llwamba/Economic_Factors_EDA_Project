# Economic_Factors_EDA_Project

## World Development Statistics

### Problem Statement

Economic development is a complex topic that can be influenced my many factors, and in the present project the focus will be on analazing the relationship between the Gross National Income (GNI), life expectancy, and population growth. These 3 elements provide an idea about the economic situation of a country, and the well being of the population. The objective of this project is to find the relationship between these 3 factors. Understanding these connections helps us understand how a country's economy, people's health, and population size interact



---

### Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|country|object|gni_per_cap_atlas_method_con2021.csv, life_expectancy.csv, and population.csv|Name of the country|
|1900-2023_pop|float|merged_data.csv|Population of the country for each year (1900-2023)| 
|1900-2023_life_exp|float|merged_data.csv|Life expectancy of the country for each year (1900-2023)| 
|1900-2023|float|merged_data.csv|GNI per capita of the country for each year (1900-2023)| 


---

### Executive Summary

#### Datasets

The following are the 3 datasets used for this project. 

**Datasets Used**

* [`population.csv`](./data/population.csv): Population by Country
* [`life_expectancy.csv`](./data/life_expectancy.csv): Life Expectancy by Country
* [`gni_per_cap_atlas_method_con2021.csv`](./data/gni_per_cap_atlas_method_con2021.csv): Gross National Income (GNI) per capita in current US dollars

#### Data Cleaning
The data was cleaned. This included dropping unwanted missing values, changing data types to numeric, and making sure that all column names are lower case. After completing this cleaning, the 3 datasets were merged to merged to "merged_pop_lifeExp_gni.csv". The merged file was used for Exploratory Data Analysis, and for any further analysis.

* Which states have the highest and lowest for population, life expectancy, and GNI per Capita between 2003 and 2023?
* Which states have the top highest and lowest for population, life expectancy, and GNI per capita growth rate over the last 50 years from 1973 to 2023?
* Is there a relationship between population, life expectancy, and GNI per capita between 2013 and 2023?

#### Conclusions and Recommendations

##### Conclusions

* Countries with higher incomes tend to have longer life expectancies. This shows the importance of economic prosperity in improving health outcomes and life expectancy.

* Although there's a slight increase in population size when life expectancy improves, population size doesn't have a major influence on life expectancy. Other factors, such as healthcare, education, and lifestyle choices have an important role in life expectancy.

##### Recommendations
* Governments should prioritize policies that promote economic growth and increase gross national income (GNI) per capita. This is because higher GNI per capita is strongly associated with longer life expectancy.
* Even though there's a weak positive correlation between population size and GNI per capita, governments should focus on improving the quality of life for their citizens while population size is increasing overtime.


