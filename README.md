
# E2E Analyses of G20 Countries

Analytics project in which I analysed 16 Socio-economic indicators of G-20 Countries from 2015-20 using World Bank Data.



```javascript
import wbdata
```

wbdata is the python library used to access data from World Bank API.
##  List of Socio-Economic indicators

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





## Distribution Histogram
The figure shows distribution histogram for each indicator with 16 sub-plots arranged in a 4x4 grid.

![histogram](https://user-images.githubusercontent.com/126495070/233435455-52fbff37-8060-4d34-9b73-651e989c1e0c.png)
## Outlier Detection

Outlier Analysis is the process of identifying outliers or abnormal observations in a
dataset.
Outliers are visualised using Box Plot.


![outlier box plot](https://user-images.githubusercontent.com/126495070/233435829-0eb07939-df4d-440d-b046-35869f6a6e05.png)

The Bar graph shows outlier percentage for each indicator.

![outlier percentage](https://user-images.githubusercontent.com/126495070/233435886-2402361f-fa17-4ba8-831d-984010ce628f.png)
## Correltaion

1. A correlation heatmap shows a 2D correlation matrix between two discrete dimensions, using colored cells to represent data
![Heatmap](https://user-images.githubusercontent.com/126495070/233436031-de9865bf-37f1-46f1-a43c-ba5db771c85a.png)

2. Jointplot showing relation between GDP and GNI.

![Joint plot a](https://user-images.githubusercontent.com/126495070/233436118-bb8f69be-d1a1-4901-a72a-3e4ad5445cdb.png)
From above graph we can conclude that both parameters are linearly correlated.

3.Jointplot showing relation between Gross Capital Formation and Poverty rate.

![Joint b](https://user-images.githubusercontent.com/126495070/233436185-771d058a-7100-43b8-a048-72688a4ab5d8.png)
Both parameters are inversely related.

4. Jointplot between Government expenditure on education and Life Expectnacy.

![Joint c](https://user-images.githubusercontent.com/126495070/233436252-e8497608-00e5-4c82-8e93-6c47c59640a3.png)
# Life Expectancy
Below graph shows percentage change in Life Expectancy from 2015-20

![Life expectancy](https://user-images.githubusercontent.com/126495070/233436314-9899ffaf-2774-4bf3-90ef-d5dd6db416d4.png)
South Africa having highest positive change of +2% and Mexico having highest negative change of -6.2%
## Foreign Direct Investment

The graph shows percentage change in FDI from 2015-20
![FDI](https://user-images.githubusercontent.com/126495070/233436357-1e3416dc-e0d1-4ff4-8e16-319eb3454f89.png)

Japan reporting +1100% change in FDI while Italy with -271% change in FDI.
