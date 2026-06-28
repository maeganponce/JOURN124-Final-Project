# Protein in Starbucks Drinks

## Data Sourcing

The dataset was downloaded from Kaggle, posted by Rachael Tatman in collaboration with Starbucks. [Link to Dataset.](https://www.kaggle.com/datasets/starbucks/starbucks-menu/data) The original source for the data is the official [Starbucks website.](https://www.starbucks.com/menu/catalog/nutrition#view_control=nutrition&drink=brewed-coffee)

The dataset is based on the Starbucks menu from 2015. It may be outdated and fail to reflect current menu options. Some drinks listed in the dataset have missing data.

Menu labeling requirements set by the Food and Drug Administration legally require chain restaurants with 20+ locations to list calorie counts and provide written nutritional information.

Providing false informations could result in fines, product seizures, injunctions to halt sales, criminal prosecution, class action lawsuits, and severe reputational consequences. Thus, the data provided by Starbucks is reasonably trustworthy.

## Data Analysis

Link to [Starbucks Drinks](https://docs.google.com/spreadsheets/d/1wST1Gs_KWrpvbDZKvlQDv4_uY5zDmPmVElSazJOhqbY/edit?usp=sharing) Google Sheet.

After downloading the dataset into Google Sheets, I applied a filter to remove drinks with missing data from display.

I began sorting through different values, filtering to see which drinks stood at the extremes of calorie, fat, and protein content. Due to recent trends in the dietary realm, I took a special interest in protein.

I created a new column to look at the percent of protein in regard to the amount of calories. I used `=DIVIDE()` with the "Protein" column as the first argument and the "Calories" column as the second argument, then converted the values to percentages.

I created different pivot tables for the "Protein" and "Calories" columns as well as my new "Protein/Calories %" column and sorted the drinks in descending order by each of these values.

I created bar charts of the top 10 drinks in each category. I found "Protein" and "Protein/Calories %" to be the most interesting comparison, and took that into Datawrapper to create visualizations.

## Data Visualizations

