# Education and Skill Development Programs

<!-- Describe the project in one sentence, e.g. A project that... -->
A project aiming at reducing inequality within and among countries by developing education and skill development programs.

<!-- Insert SDG Icons and links-->
| [![Goal 10](../images/sdgs/E-WEB-Goal-10.png)](../goals/goal_10) | [![Goal 04](../images/sdgs/E-WEB-Goal-04.png)](../goals/goal_04) |
|------------------------------------------------------------------|------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Education Ministries
- Non-Governmental Organizations
- International Development Agencies
- Educational Institutions

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To improve education and skill development to reduce inequality within and among countries.

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **CountryDevelopmentLevel**
   - Possible values: `Developed`, `Developing`, `Underdeveloped`
2. **CurrentEducationIndex** (numerical, 0-1 scale)
3. **YouthUnemploymentRate** (numerical, percentage)
4. **AdultLiteracyRate** (numerical, percentage)
5. **GenderInequalityIndex** (numerical, 0-1 scale)
6. **RuralPopulationPercentage** (numerical, percentage)
7. **GovernmentEducationSpending** (numerical, percentage of GDP)
8. **AccessToInternet** (numerical, percentage)
9. **EconomicGrowthRate** (numerical, percentage)
10. **PopulationUnderPovertyLine** (numerical, percentage)

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **ProgramType**
   - Possible values: `BasicEducation`, `VocationalTraining`, `HigherEducation`, `AdultEducation`, `OnlineCourses`
2. **FundingAmount** (numerical, millions of USD)
3. **TargetDemographic**
   - Possible values: `Youth`, `Women`, `RuralPopulations`, `Unemployed`, `GeneralPopulation`
4. **ProgramDuration** (numerical, months)
5. **TechnologyIntegration**
   - Possible values: `High`, `Medium`, `Low`, `None`

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **ChangeInEducationIndex** (numerical, change in 0-1 scale) (Maximize)
2. **ChangeInYouthUnemploymentRate** (numerical, percentage change) (Maximize)
3. **ChangeInAdultLiteracyRate** (numerical, percentage change) (Maximize)
4. **ProgramReach** (numerical, number of individuals reached) (Maximize)
5. **Cost** (numerical, calculated as FundingAmount * ProgramDuration / EfficiencyFactor, where EfficiencyFactor is influenced by TechnologyIntegration and TargetDemographic) (Minimize)

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

[Back to the list of projects](../README)