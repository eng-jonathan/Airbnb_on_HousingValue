<a name="TOP"></a>

# Airbnb Influence on NYC Housing Values 

### Controversy
**Pros:** The ability to generate additional revenue will increase home prices and financial wellbeing of homeowners as the concentration of Airbnbs increase

**Cons:** Due to Airbnb's simplicity and ability to generate income, it is viewed that Airbnbs often violate health and safety laws, leading to unsafe homes, increase in traffic in quiet neighborhoods, and increase in people who do not care about the neighborhood during their short-term visit

[Jump to Results](#Results) 
___

### Overview
This [Report](https://github.com/eng-jonathan/Airbnb_on_HousingValue/blob/main/Report/Airbnb_on_HousingValue.pdf) aims resolve the controversy of encouraging Airbnb's in NYC.

It's [Developed in ***R***](https://github.com/eng-jonathan/Airbnb_on_HousingValue/blob/main/Report/Airbnb_on_HousingValue.Rmd) and incorporates data modeling, linear/quadratic regression, and multivariate analysis
___
### Data
*NYC Open Data*: A free public data source published by NYC agencies

*InsideAirbnb*: An independent and non-commercial toolset of Airbnb data

The data is combined using cross sectional data between 2013-2015, including Airbnb Concentration, Neighborhood Fixed Effects, and other influential variables. 
___
### Methodology:
Uses Multilinear regression, estimated by Ordinary Least Squares to estimate housing value. 
(Note: *Year Build* and *Neighborhood Fixed Effects* are hidden from image)

<img src = "Images/MultiRegression%20output.jpg" width = "1050">

<a name="Results"></a>
___
### Results
A 0.165 percentage-point increase in the concentration of short-term rentals leads to a 5.049% increase in the housing sale price. 

New York City should first create and police regulations that protect the neighborhood and its people from inappropriate uses of Airbnb, then encourage Airbnb rentals rather than reduce them, as this will appreciate housing prices in the neighborhood.
___
### In Short
**✓** Airbnb Concentration causes the prices of homes to appreciate 

**✗** Non-Locals may mistreat the neighborhood due to short-term stay. 
  * Solution: Policed environmental regulations 
