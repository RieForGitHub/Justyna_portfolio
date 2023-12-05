# Justyna_portfolio

# Project 1: Audible Dataset - Data Analysis
## About
At first, I chose this project because I've been doing a lot of work on cleaning up data. But during this phase, I started asking questions about how audible sales have changed from 1998 to 2025, what kinds of audibles people like to listen to, and if there are any trends or connections between variables that could help improve sales strategies. The data for this project was obtained from [Kaggle Audible Dataset](https://www.kaggle.com/datasets/snehangsude/audible-dataset/data). The data analysis was conducted using SQL (BigQuery from Google), Excel and Tableau.

## About Data
The dataset was obtained from [Kaggle Audible Dataset](https://www.kaggle.com/datasets/snehangsude/audible-dataset/data). This dataset contains list of audbiobooks collected using web-scraping (re, Beautiful Soup, Selenium). The dataset comprises 9 columns and 82767 rows:

| Column       | Description           | Data type  |
| ------------- |:-------------:| -----:|
| name      | Name of the audiobook | STRING |
| author      | Author of the audiobook      |   STRING |
| narrator | Narrator of the audiobook      |    STRING |
| time      | Length of the audiobook | DATE |
| releasedate      | Release date of the audiobook     |   STRING |
| language | Language of the audiobook      |    STRING |
| stars      | The number of stars awarded to the audiobook | STRING |
| price     | Price of the audiobook in INR      |   STRING |
| ratings | The audiobook's rating      |    STRING |


## Asking Questions
To enhance audiobook sales, identify new strategies, and better understand the audience for targeting purposes, I needed to explore the following questions:

1. Who are the most-rated authors, and can their popularity boost sales?
2. Do different narrators for the same audiobook impact ratings and attract more attention from the audience?
3. What is the average audiobook price, and is there a correlation between higher prices and more ratings?
4. Does the duration of audiobooks influence selection? What is the optimal and maximum duration for maximum benefit?
5. Are there trends between the increasing number of audiobooks and their ratings?
6. Which language is most popular, aiding in better choices for the future?
7. Are there seasonal trends in audiobook purchases?
8. Is there any correlation between these variables which can improve sales?
9. How frequently do people choose higher volumes of audiobooks, and do other factors influence this choice?

## Steps Of Data Cleaning Using SQL
To properly analyze the data, the first step was cleaning:
1. Deleting repeated Writtenby and Narratedby
2. Changing format of time to minutes
3. Checking format of all languages
4. Separating stars number and ratings
5. Changing the format of price to FLOAT type, and renaming "Free" to "0"
5. Checking duplicates and deleting
6. Checking null values and deleting
7. Checking type of data and changing to correct type
8. Removing rest of columns
All the steps of cleaning the data are outlined in the [Audible_cleaning_data.txt](https://github.com/RieForGitHub/Justyna_portfolio/blob/main/Audible_cleaning_data.txt).

## Data Analysis Using SQL
The code used for data analysis is outlined in the [Audible_data_analysis.txt](https://github.com/RieForGitHub/Justyna_portfolio/blob/main/Audible_data_analysis.txt)


