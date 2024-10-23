# Flood Defense Systems

<!-- Describe the project in one sentence, e.g. A project that... -->
A project to reduce the risk of flooding in vulnerable areas by optimizing the design and implementation of flood defense systems.

<!-- Insert SDG Icons and links-->
| [![Goal 09](../images/sdgs/E-WEB-Goal-09.png)](../goals/goal_09.md) |
|---------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- City Planners
- Emergency Management Agencies
- Environmental Protection Agencies
- Infrastructure Developers

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To reduce the risk of flooding in vulnerable areas by optimizing the design and implementation of flood defense systems.

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **LocationType** (Categorical): ['Coastal', 'Riverine', 'Urban', 'Rural']
2. **ClimateRiskLevel** (Categorical): ['Low', 'Medium', 'High', 'VeryHigh']
3. **PopulationDensity** (Numerical, Integer): People per square kilometer
4. **EconomicActivityLevel** (Categorical): ['Low', 'Medium', 'High']
5. **PreviousFloodHistory** (Categorical): ['None', 'Minor', 'Moderate', 'Severe']
6. **SoilType** (Categorical): ['Sandy', 'Clay', 'Loam', 'Peat']
7. **InfrastructureAge** (Numerical, Integer): Years
8. **ExistingProtectionLevel** (Categorical): ['None', 'Basic', 'Enhanced', 'Advanced']
9. **BudgetAvailability** (Numerical, Integer): USD millions
10. **RegulatoryCompliance** (Categorical): ['Compliant', 'NonCompliant']

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **BarrierType** (Categorical): ['Levees', 'FloodWalls', 'SurgeBarriers', 'NaturalDefenses']
2. **ConstructionMaterial** (Categorical): ['Concrete', 'Steel', 'Composite', 'Natural']
3. **HeightIncrease** (Numerical, Integer): Meters (0 for no increase)
4. **FloodDetectionSystem** (Categorical): ['None', 'Basic', 'Advanced']
5. **CommunityEngagementLevel** (Categorical): ['None', 'Inform', 'Consult', 'Collaborate']

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **ReducedRiskLevel** (Categorical): ['Unchanged', 'Low', 'Medium', 'High'] (Maximize)
2. **ProjectCompletionTime** (Numerical, Integer): Months until completion (Minimize)
3. **MaintenanceCost** (Numerical, Integer): Annual cost in USD thousands (Minimize)
4. **TotalCost** (Numerical, Integer): Total project cost, including construction and maintenance over a 10-year period, in USD millions (Minimize)

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