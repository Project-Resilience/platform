# Community Garden and Education Program

A project that villagers can implement to directly impact food security within their small community.

| [![Goal 2](../images/sdgs/E-WEB-Goal-02.png)](https://sdgs.un.org/goals/goal2) | [![Goal 4](../images/sdgs/E-WEB-Goal-04.png)](https://sdgs.un.org/goals/goal4) |
|-------------------------------------------------------------------------------|-------------------------------------------------------------------------------|

## Decision makers

- Village leaders

## Objective
To enhance food security, improve nutritional outcomes, and promote sustainable agricultural practices within a small
community through the establishment of a community garden coupled with an education program.

## Possible Data Attributes

### Context Attributes
1. **CommunitySize** (Numerical Integer): The population of the village.
2. **LandAvailability** (Categorical): {Low, Medium, High} - Availability of land for gardening.
3. **WaterSource** (Categorical): {River, Well, Rainwater, None} - Primary source of water for the garden.
4. **Climate** (Categorical): {Tropical, Dry, Temperate, Continental, Polar} - Climate of the village's location.
5. **SoilFertility** (Categorical): {Poor, Moderate, Rich} - Natural fertility of the soil where the garden will be established.
6. **PrevAgriculturalExperience** (Categorical): {None, Basic, Experienced} - The community's previous experience with agriculture or gardening.
7. **EconomicStatus** (Categorical): {LowIncome, MiddleIncome} - General economic status of the village.
8. **CurrentFoodSecurityLevel** (Categorical): {Low, Moderate, High} - Current level of food security in the community.
9. **NutritionKnowledge** (Categorical): {Low, Moderate, High} - General level of nutritional knowledge within the community.
10. **CommunityEngagement** (Categorical): {Low, Moderate, High} - Level of community interest and willingness to participate in communal projects.

### Action Attributes
1. **GardenSize** (Categorical): {Small, Medium, Large} - Size of the community garden based on land availability and community size.
2. **CropVariety** (Categorical): {Single, Multiple} - Whether the garden will focus on a single crop or multiple crops for diversity.
3. **IrrigationMethod** (Categorical): {Manual, Rainfed, IrrigationSystem} - Method of watering the garden.
4. **TrainingSessions** (Numerical Integer): Number of educational sessions provided to the community on gardening and nutrition.
5. **CommunityParticipation** (Categorical): {Volunteer, RotationalDuty, AssignedRoles} - How the community will participate in the garden's upkeep.

### Outcome Attributes
1. **FoodSecurityPostProject** (Categorical): {Low, Moderate, High} - Level of food security after the project implementation.
2. **NutritionalDiversity** (Categorical): {Low, Moderate, High} - Variety in the nutritional value of food available to the community post-project.
3. **SustainabilityIndex** (Numerical Integer): Score from 1 to 10, evaluating the long-term sustainability of the garden project.
4. **Cost** (Numerical Integer): Calculated based on garden size, crop variety, irrigation method, and training sessions.
