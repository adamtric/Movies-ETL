# Movies-ETL

## Purpose

The purpose of this project is to extract and transform(clean and merge) datasets. After these steps are taken, we want to load this data into an SQL database to make the data more digestible.

## Results

In order to transform the data, multiple functions were created. This included the clean_movie function, which included the change_column_name function, and the extract_transform_load function, which included the parse_dollars function, and the fill_missing_kaggle_data function.

The clean_movie function cleaned out alternative movie titles from our dataset as well as renamed and regrouped columns with similar namess. The extract_transform_load function, extracted the data we wanted to compare into legible dataframes, and further cleaned the data within key columns we wanted to look at. The function also loaded the data into an SQL database for us.
