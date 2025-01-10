# Sales insights dashboard

## Problem Statement

A computer hardware manufacturer is facing some challenges. The sales director is having trouble tracking sales details all over the country. He has to shuffle through n number of excel files for every region which is quite tedious and 
never ending. We are going to create a dashboard visualization making it easier for him make data driven decisions which will help him make decisions to inmproves sales, profit and revenue.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a MySQL file.
- Step 2 : Created data model with star schema.
- Step 3 : Launching power query editor to perform data cleaning. Filtering out blank entries in zone in markets table.
- Step 4 : Filter '0' and negative values from sales amount column in sales transactions table.
- Step 5 : Added new conditional coulumn to convert USD to INR by editing DAX formula.
- Step 6 : Filtering out some duplicate entries found for currency INR and USD.
- Step 7 : Close and apply all these transformations.
- Step 8 : Create table named 'Base measure'. Create new measure under that table to bring out 'revenue' and 'sales qty'.
- Step 9 : Create single card for both revenue and sales qty.
- Step 10: Create bar chart to show revenue against zone/region and sales qty against region/zone.
- Step 11: Adding a slicer for year to track revenue by year. Also adding slicer for every month in each year. Changing 'cy date' format for the slicer to 'mmm yy'.
- Step 12: Plotted top 5 customers by revenue and top 5 products by revenue
- Step 13: Line chart plotted for revenue trend over the years.
