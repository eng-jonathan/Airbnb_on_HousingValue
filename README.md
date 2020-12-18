# Is Airbnb Good for Housing Prices?

### Overview
This report aims solve the controvery of encouraging Airbnb's in NYC.

It's developed in R and incorporates linear and quadratic regression, data removal and munging, and statistical modeling and analysis.
___
### Data
*NYC Open Data*: A free public data source published by NYC agencies
*InsideAirbnb*: An independent and non-commercial toolset of Airbnb data
___
### Methodology:
Uses linear regression, estimated by Ordinary Least Squares to estimate housing value.
<p align="center">
log(HousingPrice) = α + <β1 Percent.Airbnb>+ <B2Xlog_Gross_Square_Feet + B3XResidential_Units> + <B4XTax_Class + B5XBuilding_Class_Category> + <B6XYear_built>+ <B7XSale_Year> + <B8XNeighborhood > + ε
</p>
  
### Multi-Regression Analysis

### Results
A 0.165 percentage-point increase in the concentration of shortterm rentals leads to a 5.049% increase in the housing sale price. To ensure the possible negative effecst are accounted for, New York City should first create and police regulations that protect the neighborhood and its people from inappropriate uses of Airbnb, then encourage Airbnb rentals rather than reduce them, as this will appreciate housing prices in the neighborhood.
