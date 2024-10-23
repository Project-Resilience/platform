# Water Quality Monitoring and Management

<!-- Describe the project in one sentence, e.g. A project that... -->
Prevent potential water quality issues by helping decision makers proactively manage their interventions.

<!-- Insert SDG Icons and links-->
| [![Goal 06](../images/sdgs/E-WEB-Goal-06.png)](../goals/goal_06) |
|------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Water Utility Managers
- Environmental Protection Agencies
- Health Authorities

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To predict potential water quality issues and recommend actions to prevent or address them

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **RegionType**: Categorical (Urban, Rural, Industrial, Agricultural)
2. **WaterSourceType**: Categorical (River, Lake, Groundwater, Reservoir)
3. **Season**: Categorical (Spring, Summer, Fall, Winter)
4. **RecentRainfall**: Categorical (None, Light, Moderate, Heavy)
5. **IndustrialActivity**: Categorical (Low, Medium, High)
6. **AgriculturalActivity**: Categorical (Low, Medium, High)
7. **PopulationDensity**: Integer (people per square kilometer)
8. **PreviousWaterQualityIndex**: Integer (0-100, with 100 being the best quality)
9. **TimeSinceLastInspection**: Integer (days)
10. **ReportedIssues**: Integer (number of water quality complaints in the last month)

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **InspectionFrequency**: Categorical (Monthly, Quarterly, Biannually, Annually)
2. **WaterTreatmentLevel**: Categorical (None, Basic, Advanced)
3. **PublicAwarenessCampaigns**: Categorical (None, Local, Regional)
4. **InfrastructureImprovement**: Categorical (None, Minor, Major)
5. **RegulationEnforcement**: Categorical (None, Increased)

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **WaterQualityIndex**: Integer (0-100, with 100 being the best quality) (Maximize)
2. **IncidentReports**: Integer (number of water quality incidents reported after actions) (Minimize)
3. **ComplianceRate**: Integer (percentage of industrial and agricultural entities in compliance with regulations) (Maximize)
4. **Cost**: Integer (total cost of actions in USD) (Minimize)

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