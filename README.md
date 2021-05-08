# project-one
LB_analysis notebook uses the following datasets in Resources: 
metrovacancy05to19.csv
metrovacancy15_19.csv
metrohomeown05_14.csv
metrohomeown15_19.csv
metro_rentvacancy05_14.csv
metro_rentvacancy15_19.csv

Housing_data_selectedcounties_10yrs is informed by pop analysis and pulls from the census api to build a dataframe; dataframe is exported as housingsortedcsv.
merge_dc_withselected states uses the census api to pull additional data about Washington DC and uses the housingsortedcsv to create a new dataframe; exports housing_w_dc as a csv. 
housing_market_analysis uses the housing_w_dc csv to group the dataframe and plot a few line graphs. the line graphs for the select counties are stored in the Resource folder. 
