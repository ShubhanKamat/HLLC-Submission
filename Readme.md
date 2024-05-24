# Analysis of Key Factors Influencing US Home Prices - Shubhan Kamat

This repository presents an analysis of key factors influencing US home prices over the last 20 years. The analysis is conducted as part of the assessment for the Quantitative Analytics team interview for the position of Analytics Engineer with Home.LLC.

## Overview

In this analysis, an attempt is made to identify and explore factors that have a significant impact on US home prices at the national level. Publicly available data sources are utilized to gather information on these factors, and models are constructed to understand their relationship with home prices.

The S&P Case-Schiller Home Price Index is used as a proxy for the home prices in this analysis.


## Dataset
Publically available datasets were used for this analysis.
    
Following is the detailed list of the data sources:

1) Disposable personal income (per capita) : https://fred.stlouisfed.org/series/A229RX0
2) Moody's Seasoned Aaa Corporate Bond Yield : https://fred.stlouisfed.org/series/AAA
3) Brave-Butters-Kelley Real Gross Domestic Product : https://fred.stlouisfed.org/series/BBKMGDP
4) New Privately-Owned Housing Units : https://fred.stlouisfed.org/series/COMPUTSA
5) Consumer Price Index: All Items: Total for United States : https://fred.stlouisfed.org/series/CPALTT01USM657N
6) S&P CoreLogic Case-Shiller U.S. National Home Price Index : https://fred.stlouisfed.org/series/CSUSHPISA
7) Federal Funds Effective Rate : https://fred.stlouisfed.org/series/FEDFUNDS
8) 30-Year Fixed Rate Mortgage Average in the United States : https://fred.stlouisfed.org/series/MORTGAGE30US
9) Monthly Supply of New Houses in the United States : https://fred.stlouisfed.org/series/MSACSR
10) New Houses for Sale by Stage of Construction, Completed : https://fred.stlouisfed.org/series/NHFSEPCS
11) Population : https://fred.stlouisfed.org/series/POPTHM
12) National Totals of State and Local Tax Revenue: T01 Property Taxes for the United States : https://fred.stlouisfed.org/series/QTAXT01QTAXCAT1USNO
13) Homeownership Rate in the United States : https://fred.stlouisfed.org/series/RHORUSQ156N
14) Financial Market: Share Prices for United States : https://fred.stlouisfed.org/series/SPASTT01USM661N
15) Unemployment Rate : https://fred.stlouisfed.org/series/UNRATE
16) Construction Materials Index : https://fred.stlouisfed.org/series/WPUSI012011

The target variable for this analysis is the S&P Case-Schiller Home Price Index. 

The 'Datasets' folder contains the CSV files with the data.

The 'Data.ipynb' notebook has the entire analysis.



