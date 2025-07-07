# Project title

<!-- Describe the project in one sentence, e.g. A project that... -->
A project that uses the AquaCrop crop growth simulator to optimize irrigation and field strategies.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->
[goal_02_link]: ../goals/goal_02.md

<!-- Insert SDG Icons and links-->
| [![Goal 02](../images/sdgs/E-WEB-Goal-02.png)][goal_02_link] | ![](../images/sdgs/empty.png) | ![](../images/sdgs/empty.png) |
|--------------------------------------------------------------|--------------------------------------------------------------|-------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Farmers
- Agricultural policy makers

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To optimize crop yield, water usage, and field management costs.

## Deliverables

<!-- Provide links to the deliverables of the project -->
<!-- For instance, a link to the interactive application -->
The user interface is available here: [Irrigation Strategy App](https://irrigation-strategy.streamlit.app/)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->

- Weather data (daily high/low temperatures, precipitation, evapotranspiration)
- Future:
    - Soil features
    - Crop features

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->

- Irrigation strategy:
    - Current: soil moisture thresholds
    - Future: dynamic irrigation based on weather forecasts
- Field management:
    - Current: mulch percentage
    - Future: bunding, planting/harvesting dates, etc.

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->

- Yield (tonne/ha)
- Water usage (mm)
- Mulch percentage (%)

## Data

<!-- Describe the data that is used to evaluate the decisions -->
The AquaCrop simulator can be found here: [AquaCrop](https://www.fao.org/aquacrop/en/).
The Python implementation used in this project is found here: [AquaCropOS](https://github.com/aquacropos/aquacrop)

## Code

<!-- Point to the repo that contains the code -->
The code for this project is available here: [Code](https://github.com/danyoungday/praise)

## Needs
<!-- What kind of help is currently needed for this project? -->

List of needs:
- Contact with agricultural decision makers to validate contexts, actions, and outcomes
    - What context data is available?
    - Are SMT thresholds useful in practice? Would a dynamic schedule be more useful?

## References

<!-- Provide a list of references or other resources used in the project -->
- [AquaCrop](https://www.fao.org/aquacrop/en/)
- [AquaCropOS](https://github.com/aquacropos/aquacrop)
- [Code](https://github.com/danyoungday/praise)

## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)