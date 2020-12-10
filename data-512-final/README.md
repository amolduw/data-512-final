
# COVID-19 Demographic disparities 

## Project Motivation:
The global health crisis of year 2020, COVID-19 is spreading human suffering, killing people, impacting businesses and changing lives of people forever. It isn't only a disease, but it is a human, economic and social crisis. The coronavirus disease (COVID-19), is attacking societies at their core. Though COVID-19 pandemic affects all segments of the population, it is observed that there is significant demographic disparity in COVID-19 cases and its impact. COVID-19 seems particularly detrimental to members of those social groups in the most vulnerable situations, continues to affect populations, including people living in poverty situations, older persons, persons with disabilities, youth, and indigenous peoples. Early evidence indicates that that the health and economic impacts of the virus are being borne disproportionately by poor people. I am personally deeply saddened with COVID-19 outbreak itself, however it's more disturbing to see that certain segments of society has to suffer more than usual, adding to their existing difficulties.

As a student of Human Centered Data Science, I am intrigued to study the COVID-19 cases and their impact on various segments of population and analyze if there are significant demographic disparities of this pandemic. This was revealing analysis project to study how COVID-19 impact is seen at varying segments of people demographics of certain ethnicities, age groups, income groups and geographic locations. I am interested in analyzing COVID-19 cases data by applying Human Centered Data Science practices so as to come up better answers to find any significant disparities in COVID-19 impact. This analysis will be useful to raise awareness in society as well as governmental agencies so that appropriate actions can be taken to minimize the COVID-19 impact on all segments of society. 


## Research Questions:  
This project focuses its analysis on COVID-19 case surveillance data to understand demographic disparities in COVID-19 cases and their varying degree of impact on different segments of society.

- Are people from specific age-group more prone to COVID-19 infection or death than other age-groups?
- Is COVID-19 mortality rate more prevalent in specific race and ethnicity (combined) segment than others?


## Data Source
There are various sources of data available on internet to perform this study. I found one reliable source of data at 'Center of Disease Control and Prevention' website [cdc.gov](https://www.cdc.gov/). These deidentified data include demographic characteristics, exposure history, disease severity indicators and outcomes.

Dataset Links: [COVID-19 Case Surveillance data](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf/data) and [COVID-19 deaths and populations](https://data.cdc.gov/NCHS/Distribution-of-COVID-19-deaths-and-populations-by/jwta-jxbg/data) 

## Terms of use
Terms of Use for these datasets are documented in detail at [COVID-19 Case Surveillance Public Use Data](https://data.cdc.gov/Case-Surveillance/COVID-19-Case-Surveillance-Public-Use-Data/vbim-akqf/data) and [Public Domain U.S. Government](https://www.usa.gov/government-works).

## Directory Structure
```bash
├── plots
├── data
├── hcds-final-project.ipynb
├── ReadMe.md
├── LICENSE

```

## Requirements
[Python v3.x](https://www.python.org/)

[Seaborn latest version](https://seaborn.pydata.org/index.html)

## Findings:
This human centered data science project helped me get answers to my research questions, discover surprising facts as well as validate some of the related work findings. The detailed multi-faceted analysis performed in this project has helped me learn that people in age-groups '20-29 Years', '30-39 Years' and '40-49 Years' are top three groups getting COVID-19 infection. This is probably because these age groups might have to go out more often than others and possibly not following social distancing guidelines because of lower chances of having serious health complications. Though these groups are high on infection rate, the mortality rate is much higher in older population. Especially '80+ Years', '70-79 Years' and '60-69 Years' are top 3 age-groups with highest COVID-19 mortality rate. This most probably happens due to co-morbidities and lower immunity in these age-groups. 

Adjusting the data for age differences in race groups widens the gap in the overall mortality rates between all other groups and Whites, who have the lowest rate. As we found in race and ethnicity analysis, we found that as per Age-unadjusted data, the 'Non-Hispanic White' group is suffering most from COVID-19. As we addressed population distribution difference by using weighted population distribution and as we used age-adjusted COVID-19 death rate, we discovered that the 'Hispanic' and 'Non-Hispanic Black' groups found to be most impacted groups. 

## Visualizations
The salient visuals revelaed through data analysis are included here for quick glance.

### COVID-19 cases distribution by Age-Group
![COVID-19 cases distribution by Age-Group](https://github.com/amolduw/data-512-final/blob/main/data-512-final/plots/COVID-19%20cases%20grouped%20by%20Age-Group.png)

### COVID-19 death rate distribution by Age-Group
![COVID-19 death rate distribution by Age-Group](https://github.com/amolduw/data-512-final/blob/main/data-512-final/plots/COVID-19%20death%20rate%20grouped%20by%20Age-Group.png)

### COVID-19 Age-unadjusted death percentage and Unweighted population distribution by Race and Ethnicity
![COVID-19 Age-unadjusted death percentage and Weighted population distribution by Race and Ethnicity](https://github.com/amolduw/data-512-final/blob/main/data-512-final/plots/Age%20unadjusted%20COVID-19%20death%20percentage%20and%20Weighted%20population%20distribution%20by%20Race%20and%20Ethnicity.png)

### COVID-19 Age-adjusted death percentage and Weighted population distribution by Race and Ethnicity
![COVID-19 Age-unadjusted death percentage and Weighted population distribution by Race and Ethnicity](https://github.com/amolduw/data-512-final/blob/main/data-512-final/plots/Age-adjusted%20COVID-19%20death%20percentage%20and%20Weighted%20population%20distribution%20by%20Race%20and%20Ethnicity.png)

## Conclusion
COVID-19, a global health crisis is impacting lives of people all over the world. It isn't only a disease, but it is a human, economic and social crisis. The coronavirus disease is attacking human societies and businesses at their core. Though COVID-19 pandemic affects all segments of the population, it is observed that there is significant demographic disparity in COVID-19 cases and its impact. As observed throughout analysis performed in this project, the mortality effects of COVID-19 are much severe in old age people community as well as people in non-Hispanic Blacks and Hispanics race and ethnicities. By continuously monitoring any such disparities, bringing it to attention of authorities and take appropriate steps to overcome these disparities is very critical. Moreover, going beyond COVID-19, taking human centered learnings from this, we all should work towards addressing long pending structural inequality in communities along racial/ethnic lines with respect to a wide range of outcomes including education, employment, income, health care, and living conditions. 
  
## License
This project is available under the [MIT License](https://github.com/amolduw/data-512-final/blob/main/data-512-final/LICENSE)
