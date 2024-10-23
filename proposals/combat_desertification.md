# Combat Desertification Programs

<!-- Describe the project in one sentence, e.g. A project that... -->
We focus on developing a decision support system to predict and evaluate the effectiveness of various strategies to
combat desertification. This system aims to assist policymakers and land managers in making informed decisions on the
best approaches to prevent or reverse desertification in vulnerable areas.

<!-- Insert SDG Icons and links-->
| [![Goal 15](../images/sdgs/E-WEB-Goal-15.png)](../goals/goal_15.md) |
|---------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Land Managers
- Policy Makers
- Environmental Protection Agencies

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To prevent or reverse desertification in vulnerable areas.

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **RegionType** (Categorical): ['Arid', 'SemiArid', 'DrySubhumid']
2. **SoilType** (Categorical): ['Sandy', 'Loamy', 'Clay', 'Silty']
3. **AnnualRainfall** (Numerical, mm/year): Continuous values based on historical data
4. **TemperatureRange** (Categorical): ['Low', 'Moderate', 'High']
5. **VegetationCover** (Numerical, %): Continuous values from 0 to 100
6. **LandUse** (Categorical): ['Agricultural', 'Pastoral', 'Conservation', 'Urban']
7. **PreviousDesertificationMeasures** (Categorical): ['None', 'Afforestation', 'WaterManagement', 'SoilConservation']
8. **PopulationDensity** (Numerical, people/km²): Continuous values
9. **EconomicStatus** (Categorical): ['LowIncome', 'MiddleIncome', 'HighIncome']
10. **Year** (Numerical, Integer): Year of the data record

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **DesertificationStrategy** (Categorical): ['Afforestation', 'SustainableAgriculture', 'WaterHarvesting', 'SoilAmendment', 'ProtectedAreaEstablishment']
2. **FundingLevel** (Categorical): ['Low', 'Medium', 'High']
3. **CommunityInvolvement** (Categorical): ['None', 'AwarenessCampaigns', 'DirectParticipation']
4. **TechnologyUse** (Categorical): ['None', 'Basic', 'Advanced']
5. **MonitoringFrequency** (Categorical): ['None', 'Annual', 'SemiAnnual', 'Quarterly']

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **DesertificationChange** (Categorical): ['Increased', 'NoChange', 'Decreased'] (Maximize)
2. **BiodiversityImpact** (Categorical): ['Negative', 'Neutral', 'Positive'] (Maximize)
3. **EconomicImpact** (Categorical): ['Worse', 'NoChange', 'Improved'] (Maximize)
4. **Cost** (Numerical, USD): Calculated based on FundingLevel, TechnologyUse, and MonitoringFrequency (Minimize)

## Data

<!-- Describe the data that is used to evaluate the decisions -->
(none)

## Code

<!-- Point to the repo that contains the code -->
(none)

## References

<!-- Provide a list of references or other resources used in the project -->
(none)

## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)