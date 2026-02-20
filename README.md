# **✈️ Passenger Traffic Forecasting – O.R. Tambo International Airport**
**📌 Project Overview**

This project aims to forecast monthly passenger traffic at O.R. Tambo International Airport using econometric, demographic, and external macroeconomic indicators.

The goal is to understand the drivers of passenger demand and build predictive models to improve forecasting accuracy for aviation planning and resource allocation.

**📊 Data Sources**
The dataset combines multiple structured and unstructured data sources:

**Passenger Traffic Data**

**Source:** Airports Company South Africa (ACSA)

**Format:** PDF reports

**Processing:** Extracted and cleaned using Power Query

Transformed into structured time-series dataset

**Crude Oil Prices**

Scraped using Python (BeautifulSoup)

Used as a proxy for:

Fuel cost

Airline operational cost pressure

**Econometric & Demographic Data**

CSV format

Indicators included:

GDP

Population growth

Inflation

# **Data Engineering & Preprocessing**

Time series alignment (monthly frequency)

Handling missing values

Feature scaling (where required)

Lag feature creation

Rolling statistics (moving averages)

COVID-19 structural break handling

Stationarity testing (ADF test)

Differencing (for SARIMA)

# **🔍 Exploratory Data Analysis (EDA)**

**Key insights:**

Strong seasonality in passenger volumes

Major structural break during COVID-19

Correlation between passenger traffic and:
* GDP
* Oil prices

Post-pandemic recovery trend with volatility

**Visualizations included:**

Univariate and bivariate analysis

Time series decomposition

Correlation heatmaps

Residual diagnostics

Trend and seasonality plots

