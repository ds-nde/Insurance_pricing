# Insurance_pricing
Notebook on pricing insurance with regression

Motor insurance prices vary according to many factors. One of the most important is the
postcode where the insured vehicle is kept.  For this task, I investigated geographical variations in insurance pricing by examining data
on a postcode sector level. That is, the postcode less the final two characters (e.g. EC1R 3).
There are around 11,000 separate postcode sectors.
The aim is to use publicly available data on postcode sectors to gain insight into how the price
of motor insurance relates to geographic location.

Dataset 1 - quote_prices.csv
One million motor insurance quote prices with the postcode. Prices are the cheapest price
offered on a price comparison website.

premium_price: The total premium price for the quote
postcode: The postcode for the quote

Dataset 2 - postcode_sector_data.csv
Various publicly available data points for each postcode sector. These may correlate with the
premium price in various ways.

Column Description
postcode_sector: The postcode sector
relative_area: The relative area in km2of the sector
population_density: The mean population density of the sector 
multiple_deprivation_index: The mean of the multiple deprivation index, a government index measuring deprivation
income_deprivation_index: A related government index for income
employment_deprivation_index: A related government index for employment
crime_deprivation_index: A related government index for crime
rural_urban The category: of area that constitutes the postcode sector
distance_to_station: The mean distance to nearest station for properties in the sector
never_worked: If the sector has a high or average proportion
