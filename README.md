**DATA CLEANING STEPS**

1. Duplicate records were identified and removed using Remove Duplicate feature to ensure each entry appeared only once in the dataset.

2. Blank values were identified through Ctrl+G option and replaced text values with "Unknown" and numercial values with "0" (Ctrl+H)

3. Corrected some country names which was not correct using Find and Replace option.

4. Date fields, numeric values, and text columns were corrected using date, number and text format.

5. Added "Filter" option for every column header.

6. A calculated field was created to compute the average MDR-TB case estimate using the lower and upper case estimates available in the dataset. (Lower Estimate + Upper Estimate) / 2     =(Q2+R2)/2

7. Used Pivot Table to show how "MDR-TB cases change over time in different countries".
    Another Pivot Table used to show "Total MDR-TB burden per country".
    Another Pivot table used to "Analyze data coverage".  By Count 
    Another Pivot Table used to show "Average cases reported each Year".

8. Formated Cleaned Dataset as a "Table"

**KEY INSIGHTS**

1. Total MDR-TB Cases (Card)
 About 5 million cases show MDR-TB is a major global health problem.
2. Average MDR-TB Cases (Card)
 Around 2.15K average cases show the disease is widespread but varies by country.
3. Countries Reporting (Card)
 215 countries reported cases, showing MDR-TB affects almost the whole world.
4. Global Distribution Map
 Cases are higher in Asia and Africa, indicating key high-risk regions.
5. Gauge – Estimated MDR-TB Cases
 Around 5M cases highlight the ongoing challenge of controlling MDR-TB.
6. Trend Over Time (Line Chart)
 Cases are generally decreasing, showing improvement in control efforts.
7. Top 10 Countries (Bar Chart)
 A few countries have the highest cases, needing focused attention.
8. Distribution by Country (Pie Chart)
 Countries like India, China, and Russia contribute a large share of cases.
9. Cases by Year (Area Chart)
 Cases fluctuate but show an overall downward trend.
10. Year Slicer (Filter)
 Allows analysis of MDR-TB trends for specific years.
11. Country Slicer (Filter)
 Helps compare MDR-TB cases between different countries.
