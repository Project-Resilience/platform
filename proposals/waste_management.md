# Waste Management and Recycling

<!-- Describe the project in one sentence, e.g. A project that... -->
A Waste Management and Recycling use case for urban areas aiming at optimizing waste collection routes and schedules to
improve efficiency, reduce emissions, and increase recycling rates. This scenario involves analyzing various context
attributes to design and implement effective waste management strategies.

<!-- Insert SDG Icons and links-->
| [![Goal 11](../images/sdgs/E-WEB-Goal-11.png)](../goals/goal_11.md) |
|---------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- City Planners
- Waste Management Companies
- Environmental Protection Agencies

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To optimize waste collection routes and schedules to improve efficiency, reduce emissions, and increase recycling rates

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **PopulationDensity**: Numerical integer (people per square kilometer)
2. **AreaType**: Categorical (Residential, Commercial, Industrial, MixedUse)
3. **WasteGenerationRate**: Numerical integer (kilograms per capita per day)
4. **RecyclingParticipationRate**: Categorical (Low, Medium, High)
5. **ExistingWasteCollectionFrequency**: Categorical (Daily, BiWeekly, Weekly, Fortnightly)
6. **Season**: Categorical (Spring, Summer, Fall, Winter)
7. **DayOfWeek**: Categorical (Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, Sunday)
8. **TrafficCondition**: Categorical (Low, Medium, High)
9. **WasteSeparationPolicy**: Categorical (None, Voluntary, Mandatory)
10. **PublicAwarenessLevel**: Categorical (Low, Medium, High)

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **AdjustedCollectionFrequency**: Categorical (Daily, BiWeekly, Weekly, Fortnightly) - Adjusting the frequency of waste collection based on waste generation rates and area type.
2. **RouteOptimization**: Categorical (NotApplied, Basic, Advanced) - Implementing route optimization algorithms to reduce travel distance and time.
3. **RecyclingIncentives**: Categorical (None, Low, Medium, High) - Offering incentives to increase recycling participation rates among residents and businesses.
4. **WasteSeparationEnforcement**: Categorical (None, Soft, Strict) - Enforcing waste separation policies to improve recycling efficiency.
5. **EducationCampaigns**: Categorical (None, Online, PublicEvents, Comprehensive) - Conducting public education campaigns to raise awareness about waste management and recycling.

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **CollectionEfficiency**: Categorical (Low, Medium, High) - Efficiency of waste collection operations, considering factors like completion time and coverage. (Maximize)
2. **RecyclingRate**: Numerical integer (percentage of waste recycled) (Maximize)
3. **EmissionsReduction**: Numerical integer (percentage reduction in emissions compared to baseline) (Maximize)
4. **Cost**: Numerical integer (calculated based on action attributes, operational costs, and potential savings, measured in thousands of dollars) (Minimize)

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