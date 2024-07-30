# UNEMPLOYMENT ANALYSIS IN CANADA

# Overview
This project was developed with the finality to explain a model that could illustrate the possible future situation in the case of unemployment in Canada regarding the dataset. Furthermore, this model conjured up a suitable comprehension of forecasting application.

# WHAT KIND OF LIBRARIES ARE APPLYING TO THIS ANALYSIS?
- PANDAS AS PD
- NUMPY AS NP
- MATPLOTLIB
| LIBRARIES  | ABBREVIATION |
|------------|--------------|
| PANDAS     | pd           |
| NUMPY      | np           |
| MATPLOTLIB | plt          |

Its neccesary install this libraries to follow the present project.

# DATA TRANSFORM
Date                                                          0
Calgary CER Unemployment rate (%)                             0
Alberta Unemployment Rate (%)                                 0
Canada Unemployment rate (%)                                  0
Calgary (CMA) Average Hourly Wage Rate ($)                    0
City of Calgary Building Permits Residential Value ($)        0
City of Calgary Building Permits Non-Residential Value ($)    0
Calgary (City) Total Housing Starts (units)                   0
Calgary (CMA) Total Housing Starts (units)                    0
Calgary (CER) Retail Sales ($billions)                        2
Calgary (CMA) Inflation Rate (%change)                        0
dtype: int64
-Applying **Unemployment.fillna(0)** the Nan values will be filled by 0 
# DATA COLUMNS CONSIDERED
'Calgary CER Unemployment rate (%)', 'Alberta Unemployment Rate (%)', 'Canada Unemployment rate (%)'
# STADISTIC ANALYSIS
In this context the idea is apply Z-score table to know measures the number of standard deviations from the mean. A z-score close to 0 indicates the value near the mean, possitive z-score indicates above the mean, and negative z-score below the mean. Calgary Unemployment rate shows peaks around 2020-06 to 2021-08 with z-scores exceeding 1.5, indicating significatly higher employment compared to the mean. Values dip down below mean mostly between 2022-09 to 2023-12. Alberta Unemployment rate indicates higher unemployment rates with peaks similarly around 2020-05 to 2021-08 with z-scores around 1.5. Values from 2022-08 to 2023-12 indicates lower unemployment rates compared to the mean. Peaks around 2020-04 to 2020-12 with scores around 1.8 , indicating higher unemployment rates.

# ANALYSIS OF UNEMPLOYMENT RATE GRAPH
  All three regions show a higher unemployment rates around the same time, considering from 2020 to around 2021. Calgary's trend and Alberta's trend follows the   
  same  trend , with a sharp increase and peak around 2020, the recovery appears slighly better than Calgary but still shows higher rather rates than the national 
  average for most of the period. The Canada tendency increase the same as Calagary's or Alberta's but not as sharply as the mentioned regions.

# ANALYSIS SMOOTHED UNEMPLOYMENT RATE GRAPH
  The smoothed Unemployment graph  compares the original unemployment rates with the smothed rates for Calgary,Alberta, and Canada. The smoothed lines provide a   
  clearer view of the overall trends, reducing noise or fluctuation.
  The smoothed line for Calagary and Alberta shows a clear upward starting in early 2020, peaking around mid-2020, and then gradually go down. This indicates a   
  mainly impact  on the province , with a slow but steady recovery. Canada shows a more moderate peak and a smoother decline, indicating a more stable national 
  recovery. This suggests that the national economy has been more resilient compared with the regional provinces.  
# ANALYSIS IN TERMS OF THE ECONOMICS
  All three regions show a similar trend with unemployment rates peaking around 2020 due to the COVID-19 pandemic and gradually decreasing afterward
  Calgary and Alberta shows a higher unemployment rate comparing with Canada as a nation due to regions could specify dependencies in terms of macroeconomics such    as health factors (COVID-19). Furthermore, it is relevant the comprenhension into the "ceteris paribus" due to whatever factor that  increase or decrease in   
  health, politics or social could rebound in the economic situation.

# SUGGESTION 
  During the present 
  



