# Project 4: Overview of the state of malnutrition in the World

## Objectives
Analysis of the state of malnutrition in the World using Food and Agricultural Organisation (FAO) data to analyse malnutrition,food security, and nutritional status.

## Mission
- Proportion of the population in the state of malnutrition.
- Number of persons that can be fed from the World's food supply.
- Number of persons that can be fed from the plant products.
- Calculate the proportion of internal food availability allocated to animal feed, attributed to loss, and concretely used for human.
  
## Data sources
- FAO data: aide_alimentaire (food aid or assistance), disponibilté_alimentaire (food availability), population, sous_nutrition (malnutrition).
  
## Data preparation
- Import the 4 datasets in csv.files.
- Use pandas library to manipulate data in csv. files in the form of dataframes.
- Explore the dataframes using different methodes (shape, head, tail, describe, info).
- Clean the data checking for duplicates, missing values, and inconsistencies; fill the missing data with zero as it does not make much difference.
- Change data type from string to numeric, convert tonnes to Kg.
- Filter out food based on plant products and animal products.
- Rename columns and create calculated columns.
- Join 2 dataframes.
  
## Data Analysis
- Data Exploratory; summary statistiques of the data
- Calculate the proportion of the global population in the state of malnutrition, countries with high number of malnutrition and those that received food assistance in 2017.
- Use pie chart to represent the proportion of internal food supply.
- Use horizontal bar chart to display the countries with the highest number of malnourished people.
  
## Insights
### Allocation of internal food supply 
<img width="650" alt="food" src="https://github.com/user-attachments/assets/98d13005-e5ce-4ee3-8df7-26c015a86850" />

### 10 top countries with the highest proportion of malnourished people in 2017
<img width="1241" alt="10 top countries with highest proportion of malnourished people in 2017" src="https://github.com/user-attachments/assets/d8758c00-d3eb-40d4-99f7-c123333ae789" />

- The proportion of food available for adults in 2017 is 107%.
- 88% of the population can be fed using plant products in 2017.
- Haiti has the highest number of malnourished people, followed by Democratic People's Republic of Korea and Madagascar in 2017.
- Republic Arabe Syrian received the highest food assistance in 2017.
- - Austria has the highest food availability per capita in 2017
  
<img width="632" alt="Countries with the highest and lowest food availability" src="https://github.com/user-attachments/assets/f9c5da3b-0c2c-4749-b5fd-f0cfe5c1b0bd" />

- 69% of plant products such as cereals are used for animal feed while 18% is for human consumption in 2017.
- Thailand exports 83% of the cassava produced in 2017.

## Recommendations
- Efforts should be made to channel food assistance to the countries that are worst hit by malnutrition.
- Countries need to improve their internal food availablity and also consume more before exportation.
- The use of plant products for human food is to be encouraged.
