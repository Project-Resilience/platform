# Women's Entrepreneurship Development Program

<!-- Describe the project in one sentence, e.g. A project that... -->
This program aims to support and empower women to start and grow their own businesses through training, mentorship,
and access to capital. It's designed to be implemented at a community or municipal level, targeting potential and existing female entrepreneurs.

<!-- Insert SDG Icons and links-->
| [![Goal 05](../images/sdgs/E-WEB-Goal-05.png)](../goals/goal_05.md) |
|---------------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Mentorship program managers
- Partners and investors
- Women entrepreneurs

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To optimize business creation by women through a structured program that provides training, mentorship, and access to capital.

## Interactive application

<!-- Provide a link to the interactive application -->
(none)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **CommunitySize** (Categorical): ['Small', 'Medium', 'Large']
2. **LocalEconomicStatus** (Categorical): ['Low', 'Medium', 'High']
3. **ParticipantEducationLevel** (Categorical): ['None', 'Primary', 'Secondary', 'Tertiary']
4. **BusinessStage** (Categorical): ['Idea', 'Startup', 'Established']
5. **Sector** (Categorical): ['Agriculture', 'Retail', 'Services', 'Manufacturing', 'Technology']
6. **AccessToInternet** (Categorical): ['No', 'Limited', 'Good', 'Excellent']
7. **PreviousBusinessExperience** (Categorical): ['None', '1-2years', '3-5years', '5+years']
8. **AgeGroup** (Categorical): ['18-24', '25-34', '35-44', '45-54', '55+']
9. **FamilySupport** (Categorical): ['None', 'Low', 'Moderate', 'High']
10. **LocalMarketOpportunities** (Categorical): ['Low', 'Moderate', 'High']

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can take the following actions:

1. **TrainingFormat** (Categorical): ['InPerson', 'Online', 'Hybrid']
2. **ProgramDuration** (Numerical Integer): [1, 12] - Duration of the program in months.
3. **MentorshipAvailability** (Categorical): ['No', 'Yes']
4. **FinancialSupport** (Categorical): ['No', 'Microcredit', 'Grant', 'Investment']
5. **NetworkingEvents** (Categorical): ['No', 'Yes']

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **BusinessLaunchRate** (Numerical Integer): [0, 100] - Percentage of participants who launch a business by the end of the program. (Maximize)
2. **BusinessSurvivalRate** (Numerical Integer): [0, 100] - Percentage of launched businesses that survive for at least 1 year. (Maximize)
3. **RevenueIncrease** (Numerical Integer): [0, 100] - Percentage of participants with existing businesses that see a revenue increase. (Maximize)
4. **Cost** (Numerical Integer): Calculated based on TrainingFormat, ProgramDuration, and FinancialSupport, with a base cost and adjustments for each parameter. (Minimize)

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