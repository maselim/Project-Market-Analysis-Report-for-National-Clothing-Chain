# Project-Market-Analysis-Report-for-National-Clothing-Chain
Project: Market Analysis Report for National Clothing Chain

### overview
## Project Description
An online national clothing chain needs your help creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:
Shirt: $25
Sweater: $100
Leather Bag: $1,000
They need you to conduct an analysis to determine the best product to advertise to each customer.
Image Information

"fashionistas" by [ embr ] is licensed under CC BY-NC-SA 2.0
"French Connection @ Shopper's Stop, Garuda Mall" by teemus is licensed under CC BY-NC-SA 2.0
Project Instructions
In this project, you will use population statistics from the US Census Bureau to determine where the greatest income exists around the country and whether there is a correlation between sales and income. We don’t know the incomes of our customers, but we should be able to predict it by looking at their purchase history and locations and comparing that against the census data. Additionally, we want to analyze our inventory, specifically customer ratings and return rate and see if there’s a correlation between the two.

## Draw conclusions
Draw conclusions from your analysis and use visuals to answer the following questions:

Analysis Questions:

What is the correlation (R2 value) between sales and income?
What is the correlation (R2 value) between customer ratings and product return rate?
What are the linear regression formulas to predict customer sales and customer incomes?
Which customer do you predict has the highest income?
Which product will be advertised the most?
Present your analysis
You’ll need to present your analysis as a 1 page written summary and visual report in Power BI. Use the following visuals to present your data:

Income Distribution: Histogram
Household Income by Location: Map
Correlations: Scatter Plot with Trendline and Card with R^2 value
Use other visuals as-needed to further present the results of your analysis.

Histogram
Although you will need to determine the parameters of the histogram(s) for your project, think about what a histogram is intended to do. In the example below, you can see that the histogram gives you a clear understanding of the distribution of values and helps you visualize the shape of the data. We can see here that it's a right-skewed distribution with a peak of around $40k and an average that is probably a bit to the right of the peak.

Your histogram(s) should also convey important statistics about the data you analyze, so you'll probably want to have at minimum 4 columns but preferably more.

Additionally, although there is a histogram visual you can download from the Power BI marketplace (if you have access to that resource) it's recommended that you use a column chart instead so that you can use a DAX formula to specify the ranges and number of columns (more on this in the detailed instructions).
Detailed Instructions

Import the census data, customer list, purchase list, and state list into Power BI. You’ll use the “Get Data” button to start the import process. Make sure you select each of the available tables within each Excel file. There should be 7 total tables:
Avg Income by State
Customer List
Incomes by State
Industries
Product Inventory
Purchase List
State List
Set up the data in Power Query so that all the columns are correctly formatted and structured. Some of the tables will require steps in Power Query to be correctly set up.
Set up your table relationships. All tables you import should be tied into the table relationships. Avoid many-to-many relationships as they’re not needed and will cause issues with cross-filtering.
Review the table relationships and confirm if they are properly set up. Most of the tables should follow a star schema and the overall set up should look similar to the sample image:
## Detailed Instructions

Import the census data, customer list, purchase list, and state list into Power BI. You’ll use the “Get Data” button to start the import process. Make sure you select each of the available tables within each Excel file. There should be 7 total tables:
Avg Income by State
Customer List
Incomes by State
Industries
Product Inventory
Purchase List
![image](https://github.com/maselim/Project-Market-Analysis-Report-for-National-Clothing-Chain/assets/52356062/2d20ccbb-6139-483f-a798-9b47cefab6b6)
![image](https://github.com/maselim/Project-Market-Analysis-Report-for-National-Clothing-Chain/assets/52356062/6eca2b7f-23c5-4ec5-a535-f2d7a904b6bd)

State List
Set up the data in Power Query so that all the columns are correctly formatted and structured. Some of the tables will require steps in Power Query to be correctly set up.
Set up your table relationships. All tables you import should be tied into the table relationships. Avoid many-to-many relationships as they’re not needed and will cause issues with cross-filtering.
Review the table relationships and confirm if they are properly set up. Most of the tables should follow a star schema and the overall set up should look similar to the sample image:
