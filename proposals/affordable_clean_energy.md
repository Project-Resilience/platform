# Affordable and clean energy

A project that simulates realistic scenarios for implementing energy efficiency programs across various sectors.

| [![Goal 7](../images/sdgs/E-WEB-Goal-07.png)](../goals/goal_07.md) | [![Goal 13](../images/sdgs/E-WEB-Goal-13.png)](../goals/goal_013.md) |
|--------------------------------------------------------------------|----------------------------------------------------------------------|

## Decision makers

- Energy program managers
- Policy makers
- Business leaders

## Objective
 
To identify and implement the most effective energy efficiency measures across different sectors
(residential, commercial, industrial) to reduce energy consumption and costs, considering the specific characteristics
and needs of each sector.

## Possible Data Attributes

### Context Attributes
1. **Sector**: Categorical (`Residential`, `Commercial`, `Industrial`)
2. **BuildingAge**: Integer (years)
3. **BuildingSize**: Integer (square meters)
4. **LocationClimate**: Categorical (`Cold`, `Temperate`, `Hot`, `Variable`)
5. **CurrentEnergyEfficiencyLevel**: Integer (1-10 scale, with 10 being the most efficient)
6. **EnergyConsumption**: Integer (kWh per year)
7. **PrimaryEnergySource**: Categorical (`Electricity`, `NaturalGas`, `Renewables`, `Mixed`)
8. **OccupancyRate**: Integer (percentage, relevant for commercial and residential sectors)
9. **OperatingHours**: Integer (hours per day, relevant for commercial and industrial sectors)
10. **EnergyCostPerkWh**: Float (USD)

### Action Attributes
1. **EfficiencyMeasureType**: Categorical (`InsulationUpgrade`, `HVACSystemUpgrade`, `LightingUpgrade`, `EquipmentUpgrade`, `RenewableEnergyInstallation`)
2. **InvestmentCost**: Integer (USD)
3. **ImplementationTime**: Integer (days)
4. **ExpectedLifeTime**: Integer (years)
5. **FinancingOption**: Categorical (`SelfFunded`, `Loan`, `Grant`, `IncentiveBased`)

### Outcome Attributes
1. **EnergyConsumptionReduction**: Integer (percentage)
2. **OperationalCostSavings**: Integer (USD per year)
3. **ROI**: Float (percentage, calculated as savings over investment cost)
4. **Cost**: Integer (USD, calculated based on `InvestmentCost` and potential financing impacts)

## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)
