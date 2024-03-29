# Forbes 2022 Billionaires Analysis

![Screenshot 2023-02-01 015300](https://user-images.githubusercontent.com/110452335/215908764-c6a2a188-d90e-425d-820c-04351f7df17d.png) ![Screenshot 2023-02-01 015327](https://user-images.githubusercontent.com/110452335/215908971-bd16b3fb-d6ce-4da1-ae99-cf4959787423.png)
![Screenshot 2023-02-01 015419](https://user-images.githubusercontent.com/110452335/215908985-2a97854b-f3c3-4b13-a57d-62591c6d543f.png)
![Screenshot 2023-02-01 015556](https://user-images.githubusercontent.com/110452335/215909004-cefa86ca-16f6-4d1e-8132-444cd014f622.png)

# Introduction
Forbes World’s Billionaires is a documented report of an annual ranking of the net worth of the wealthiest billionaires in the world. The information is usually compiled and published every year since March 1987. Estimates of the net worth of each billionaire are cited in United States dollars regarding their documented assets while accounting for debts and other factors. On Forbes's 36th annual ranking, there were 2668 billionaires listed, 87 fewer than the previous year, 2021. 
In this project, I analyzed the Forbes Billionaires list 2022.

# Project Overview
This project aims to help identify the wealthiest Forbes 2022 billionaires, the most philanthropic billionaires, and the industry that drives them. Likewise, the project will analyze whether they are self-made or not. A visual map will show the distribution of billionaires across the world.

# Data Sourcing
I sourced the data set used for this Analysis from [Kaggle]( https://www.kaggle.com/datasets/jjdaguirre/forbes-billionaires-2022).
The dataset was in one spreadsheet that contained 2668 rows and 22 columns containing information on the wealthiest billionaires worldwide by ranking.

# Data Cleaning

## Microsoft Power BI
I cleaned the data using the power query editor and the Power BI desktop to carry out visualizations of the insights from my Analysis.

# Data Cleaning Process
Data cleaning is a process that prepares data for Analysis by removing and modifying incorrect, irrelevant, incomplete, improperly formatted, and duplicated data.

After importing the data to Power BI as a CSV, I transformed it based on the entire dataset.

## Power Query
I changed the column names of (personName, finaWorth, category, country of citizenship, Bio)  to Name, Worth, Industry, Country, and Biography, respectively.

I replaced the values on the gender column from M and F to Male and Female, respectively.

I then removed the Month, Year, residenceMSA, and no of siblings columns since they were not to be used for this Analysis.

The Worth column was multiplied by 1,000,000 and then formatted to billions in United States Dollars.The data was then loaded to the Power BI desktop to create insights through visualizations.

## Power BI Desktop
I created the following DAX measures to help in visualization; Average age, Average worth, Countries, Females, Males, Industries, Maximum worth, Minimum worth, Net worth, Oldest, Organizations, Philanthropic, Total Billionaires, and Youngest.

# Analysis
I added a cover page for the work on the newly created page and renamed it Cover. On the second page, I did an Analysis of the data to draw insights on the following:
1.	Top 5 richest billionaires
2.  Bottom 5 richest Forbes billionaires.
2.	The proportion of 2022 Forbes billionaires by industry.
3.	Top 5 youngest billionaires.
4.	Self-made billionaires by Gender.

On the third page, I derived insights based on the following:
1.	Forbes 2022 Billionaires by country
2.	Total billionaires by Gender and total countries.

I added a filter on Gender to compare males and females worldwide.
[Interact with my Dashboard and report here](https://drive.google.com/drive/folders/1RWERDoByVdB6YO_c68NKY_LcRGVz8w2W?usp=sharing)

# Conclusions
1.	Most of the billionaires featured on the Forbes list in 2022 were male.
2.	The Technology industry drives most of the philanthropic billionaires.
3.	The average worth of a billionaire on the list is 4.76 billion.
4.	Only 396 out of the 2668 billionaires had a high philanthropic score.
5.	Most Male billionaires are self-made, whereas most female billionaires are not self-made.
