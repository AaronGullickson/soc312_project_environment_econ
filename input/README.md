# World Bank's World Development Indicators and Heritage Foundation's Index of Economic Freedom

The data we are using comes from the [World Bank's World Development Indicator's](https://databank.worldbank.org/data/source/world-development-indicators#) and the [Heritage Foundation's Index of Economic Freedom] (https://www.heritage.org/index/). The World Bank collects data through officially recognized international sources, using national, regional, and global estimates. The Heritage Foundation's Index of Economic Freedom uses twelve indicators dealing with national economies, ranging from unemployment rates to national debts to construct the final score.

Below are the variables included in the dataset, along with descriptions of them:

- **country**: This is a nominal variable giving the country name.
- **region**: This is a nominal variable giving the region to which the country belongs. Countries were assigned to five categories: Americas, Asia-Pacific, Europe, Middle East and North Africa, and Sub-Saharan Africa. Country designations were determined by the Heritage Foundation.
- **neoliberal_score**: The Economic Freedom Index, ranging from 0 (least free) to 100 (most free). The index was constructed from 12 variables, including property rights, judical effectiveness, government integrity, tax burden, government spending, fiscal health, business freedom, and labor freedom.
- **co2_capita**: The metric tons of carbion dioxide emitted divided by country population. Carbon dioxide emissions are mostly the result of the burning fossil fuels like oil, gas, and coal, and biomass. In other words, this  measure gives how much carbon dioxide is emitted per person in the pertinent year (2014).
- **age_dep_ratio**: the ratio of dependents-people younger than 15 or older than 64-to the working-age population-those ages 15-64. Data are shown as the proportion of dependents per 100 working-age population.
- **pct_urban**: The percentage of people living in urban areas as defined by national statistical offices. The data are collected and smoothed by United Nations Population Division.
- **pop_density**: The midyear population divided by land area in square kilometers
- **gdp_capita**: Gross domestic product divided by midyear population. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2010 U.S. dollars.
- **life_expect**: The expect lifespan of a newborn given that current mortality trends continue throughout their life.
- **imports_lower_income**: Merchandise imports from low- and middle-income economies outside region are the sum of merchandise imports by the reporting economy from other low- and middle-income economies in other World Bank regions.

In the original data, there are missing values for some observations on some of these variables. To simplify our analysis, I have omitted countries with missing values.