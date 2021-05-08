# project-one: Population vs Vacancy Rates

# Team Members:
  ♦ Lora Brown
  ♦ Gaylen Fogerson
  ♦ Yusufu Kamara
  ♦ Britt Mann
  ♦ Ricci Sandoval
  ♦  
  
# Project Summary
For this project, our group's hypothesis was that an increase in a city's population would directly increase its vacancy rates, perhaps by raising the cost of housing. For data, we made API calls to pull CSV's of housing, population and vacancy data from the Census Bureau. We hoped to identify a pattern by examining the counties with high rates of population increase as well as the metro areas with the greatest increase in vacancies, by both rental and gross. If our hypothesis was correct, we would have expected to see the sharpest rises in vacancies occurring in the counties and states with the highest level of population increase.

What we found when examining this data was that although the highest rates of increase for vacancies did not match up with the highest rates of population increase, the inverse was also not true. The metro areas with the highest increases in vacancy were distributed without pattern throughout our population gain data. Because this information was calculated proportionally to the population size, we do not expect that town size (e.g. towns that grew over 100% because their population increased by 1,000 people) was a confounding factor. Additionally, studying metro areas instead of towns allowed us to capture the ÒsprawlingÓ effect of displaced people moving into adjacent communities.

At the end of our analysis, our group has concluded that the null hypothesis is the most likely. Literature on the topic lists population change as one of several factors that work in tandem with the specific factors of a city to create or minimize vacancies. Perhaps population increase, in combination with depressed wages or rising social instability, might predict a rise in vacancies. However, it is not a singular driver of vacancy by any means. 
  
# Team Member Notes:
→ LB_analysis notebook uses the following datasets in Resources: 
  - metrovacancy05to19.csv
  - metrovacancy15_19.csv
  - metrohomeown05_14.csv
  - metrohomeown15_19.csv
  - metro_rentvacancy05_14.csv
  - metro_rentvacancy15_19.csv

→ Housing_data_selectedcounties_10yrs is informed by pop analysis and pulls from the census api to build a dataframe; dataframe is exported as housingsortedcsv.
merge_dc_withselected states uses the census api to pull additional data about Washington DC and uses the housingsortedcsv to create a new dataframe; exports housing_w_dc as a csv.

→ Housing_market_analysis uses the housing_w_dc csv to group the dataframe and plot a few line graphs. the line graphs for the select counties are stored in the Resource folder. 
