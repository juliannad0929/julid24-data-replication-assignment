There are three data sets:
1. Cross-sectional NYC mobility and COVID-19 data (ZCTA-level)
2. Longitudinal NYC COVID-19 data (Borough-level)
3. Longitudinal NYC mobility data (ZCTA and borough-level)
4. Geographic coordinates for NYC (ZCTA-level)
5. Regression output for Figure 4 (ZCTA-level)


Dataset 1: Cross-sectional NYC mobility and COVID-19 data (ZCTA-level)
File name: Cross-sectional_COVID19_mobility_zcta.csv
Variable names and descriptions:
borough - NYC borough
ZCTA - NYC zip code tabulation area
cumincidence - COVID-19 cumulative incidence (NYC DOHMH COVID-19)
mobility_April_11 - main measure of mobility on April 11 (NYC MTA subway) 
median_income - median income (American Community Survey)
gt_75_yrs - percent of individuals age >75 years (American Community Survey)
all_essential - percent essential workers (American Community Survey)
health_essential - percent healthcare essential workers (American Community Survey)
nonhealth_essential - percent non-healthcare essential workers (American Community Survey)
nonwhite_Hispanic - percent non-white and/or Hispanic/Latino (American Community Survey)
uninsured - percent uninsured (American Community Survey)
le_highschool - percent with a high school education or less (American Community Survey)
rate_positive - rate of positive COVID-19 cases per 100,000 population
percent_positive_over_tests - percentage of positive tests out of the total number of tests
rate_tests - the rate of total tests per 100,000 population

Dataset 2: Longitudinal NYC COVID-19 data (Borough-level)
File name: Longitudinal_COVID19_borough.csv
Variable names and descriptions:
date - date
borough	- NYC borough
incidence - incidence
cumincidence - cumulative incidence
rate_positive - rate of positive COVID-19 cases per 100,000 population (NYC DOHMH COVID-19)
percent_positive_over_tests - percentage of positive tests out of the total number of tests (NYC DOHMH COVID-19)
rate_tests - the rate of total tests per 100,000 population (NYC DOHMH COVID-19)

Dataset 3: Longitudinal NYC mobility data (ZCTA and borough-level)
File name: Longitudinal_Mobility_zcta_borough.csv
Variable names and descriptions:
date - date
borough - NYC borough
ZCTA - NYC zip code tabulation area 
mobility - measure of mobility (NYC MTA subway)

Dataset 4: Geographic coordinates for NYC (ZCTA-level)
File name: 4._Map_Mobility_zcta
Variable names and descriptions:
ZCTA - NYC zip code tabulation area
long - longitude
lat - latitude
Feb_29 - measure of mobility on February 29 (NYC MTA subway) 
March_7 - measure of mobility on March 7 (NYC MTA subway) 
March_14 - measure of mobility on March 14 (NYC MTA subway) 
March_21 - measure of mobility on March 21 (NYC MTA subway) 
April_11 - measure of mobility on April 11 (NYC MTA subway) 


Dataset 5: Regression output for Figure 4 (ZCTA-level)
File name: 5._Regression_output
Variable names and descriptions:
Variable - Predictor for the regression
RiskRatio - risk ratio
LowerLim - lower 95% confidence interval
UpperLim - upper 95% confidence interval
Outcome - Outcome for the regression