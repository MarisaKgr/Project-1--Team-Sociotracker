# Team-Sociotracker - Gentrification of Richmond
The correlation between the city's gentrified neighborhoods, crime rates, and cost of housing.

Team Members: Angela Angulo, Bonnie Bailey, Joseph March, and Marisa Kiger

## Motivation and Summary
### Gentrification
The process whereby the character of a poor urban area is changed by wealthier people moving in, improving housing, and attracting new businesses, typically displacing current inhabitants in the process.

### Hypothesis
An expectation that crime reported will decrease as average housing values increase for neighborhoods.

### Research Questions
-How does gentrification affect crime rates?

-how does the rate of crime correlate to the cost of housing?

### Why did we ask these questions?
Gentrification is not something that occurs overnight. It is a process over time. Our study is to determine whether or not crime rates were affected throughout this time frame by looking at trends over multiple years. Then to determine how the cost of housing in these gentrified areas correlated to that crime rate.

### Summary
While there is a weak negative correlation between housing values and crime rate in all of Richmond overall, we do see patterns arise among the 7 gentrified neighborhoods we reviewed.

## Data
Data pulled on crime rates and housing prices based on neighborhoods in Richmond.

### Resources:
- Crime Data- https://www.richmondgov.com
- Zillow- https://www.zillow.com/research/data/
- Google Maps/Street View
- Census Data- https://www.census.gov/quickfacts/fact/table/richmondcitycountyvirginia,richmondcityvirginia/PST045219
- Mapline- https://mapline.com/

## Process
Due to the large amount of data, we chose to narrow the field to 7 of the regions that have shown the most gentrification and growth since the Year 2000:
- Shockoe Bottom
- Scott’s Addition
- Church Hill
- Church Hill North
- Oregon Hill
- Manchester
- Jackson Ward

## Tools Used
- Python
- Jupyter Notebook
- Pandas
- NumPY
- SciPY
- Matplotlib

## Output
Scatter Plot - Total Crime vs Average House Value 2000-2020
![crimevshousing](/Output/Images/TotalCrimevsAverageHousingValue_scatter.png)

Line Graph - All Neighborhoods in RVA Average House Value 2000-2020
![avghousingvalue](/Output/Images/AvgHousingValueforAllRVAvsGentNeighborhoods_line.png)

Line Graph - All Neighborhoods IN RVA Reported Crime 2000-2020
![crimeallneighborhoods](/Output/Images/TotalCrimeforAllRVAvsGentNeighborhoods_line.png)

Bar Graph - Total Crime by Neighborhood 2000 and 2020
![crimebyneighborhood](/Output/Images/TotalCrimebyNeighborhood_boxplot.png)

Line Graphs - Average Housing vs. Total Crime (first by all of Richmond then by Neighborhoods)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeALLRVA_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeCHURCHHILL_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeCHURCHILLNORTH_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeJACKSONWARD_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeMANCHESTER_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeOREGONHILL_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeSCOTTSADDITION_line.png)
![avghousingvstotalcrime](/Output/Images/AvgHousingvsTotalCrimeSHOCKOEBOTTOM_line.png)

Box and Whisker Analysis - Crime and Average House Value 2000-2020
![boxwhisker](/Output/Images/TotalCrimeat2000and2020_boxwhisker2.png)
![boxwhisker](/Output/Images/AvgHousePriceat2000and2020_boxwhisker2.png)

## Findings
- The overall correlation was weak between total crime and average house value for Richmond as a total.
- 4 of the 7 selected neighborhoods did show an inverse relationship between the total crime rate and average house value.
- 3 of the 7 selected neighborhoods did not behave as expected.

## Conclusion
We did not find what was expected in each case, potentially because neighborhoods are developing at different rates. Location and distance from the city center may also affect results. Percentage of commercial real estate vs residential could have impacts as well.

## Contacts
Angela Angulo: anguloag@vcu.edu

Bonnie Bailey: bonnie.lyn@hotmail.com

Joseph March: josephmarch@gmail.com

Marisa Kiger: marisa_krg@yahoo.com
