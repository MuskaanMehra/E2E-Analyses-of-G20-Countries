
# E2E Analyses of G20 Countries

Analytics project in which I analysed 16 Socio-economic indicators of G-20 Countries from 2015-20 using World Bank Data.


## Tableau Visualization

### Dashboard-01
Designed Tableau dashboard containing following visualizations:
1. Inflation rate over the years
2. Countrywise Unemployment rate
3. Access to Electricity
4. Efficacy of Govt. Education spending

[ Link for Dashboard-1](https://public.tableau.com/app/profile/muskaan.mehra/viz/Book1_16822282348440/Dashboard1)

![Dashboard-1](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/dashboard%201.png)

### Dashboard-02
Designed Tableau dashboard containing following visualizations:
1.  GDP v/s Gross Capital Formation
2.  Exports v/s Imports
3.  Mobile Subscriptions v/s GNI
4.  FDI Distributions

[Link for Dashboard-02](https://public.tableau.com/app/profile/muskaan.mehra/viz/G20CountriesAnalysis/Dashboard1)

![Dashboard-02](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Dashboard-02.png)

## Analyses using Python 
Used Python, Pandas, Matplotlib and Seaborn to perform analyses.


```javascript
import wbdata
```

wbdata is the python library used to access data from World Bank API.
###  List of Socio-Economic indicators

- Gross Domestic Product (GDP)
- Gross National Income (GNI)
- Inflation rate
- Unemployment rate
- Poverty rate
- Life expectancy
- Literacy rate
- Access to electricity
- Mobile phone subscriptions 
- Government expenditure on education
- Foreign direct investment (FDI)
- Exports of goods and services
- Imports of goods and services
- Gross capital formation 
- Agricultural production index
- Agricultural land area





### Distribution Histogram
The figure shows distribution histogram for each indicator with 16 sub-plots arranged in a 4x4 grid.

![histogram](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Histogram.png)
### Outlier Detection

Outlier Analysis is the process of identifying outliers or abnormal observations in a
dataset.
Outliers are visualised using Box Plot.


![outlier box plot](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Outliers.png)

The Bar graph shows outlier percentage for each indicator.

![outlier percentage](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Outlier%20Percentage.png)
### Correltaion

1. A correlation heatmap shows a 2D correlation matrix between two discrete dimensions, using colored cells to represent data
![Heatmap](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Heatmap.png)

2. Jointplot showing relation between GDP and GNI.

![Joint plot a](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Jointplot%20a.png)
From above graph we can conclude that both parameters are linearly correlated.

3.Jointplot showing relation between Gross Capital Formation and Poverty rate.

![Joint b](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/JointplotB.png)
Both parameters are inversely related.

4. Jointplot between Government expenditure on education and Life Expectnacy.

![Joint c](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Jointplot%20C.png)
### Life Expectancy
Below graph shows percentage change in Life Expectancy from 2015-20

![Life expectancy](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/Life%20Expectancy.png)
South Africa having highest positive change of +2% and Mexico having highest negative change of -6.2%
### Foreign Direct Investment

The graph shows percentage change in FDI from 2015-20
![FDI](https://github.com/MuskaanMehra/E2E-Analyses-of-G20-Countries/blob/main/Assets/FDI.png)

Japan reporting +1100% change in FDI while Italy with -271% change in FDI.
