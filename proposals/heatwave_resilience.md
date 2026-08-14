# HeatReady: Heatwave Preparedness and Response

<!-- Describe the project in one sentence, e.g. A project that... -->
Heatwave warnings often tell communities that dangerous heat is approaching without helping residents or city administrators translate that warning into timely, local action. 
This project proposes an AI-assisted heat-action service that combines authoritative warnings, weather forecasts, locally approved health guidance, verified cooling resources and neighborhood context. 
It would help individuals decide how to protect themselves and others while helping cities determine when and where to activate cooling centres, outreach, transport, water distribution and longer-term heat-mitigation measures.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->

<!-- Good Health and Well-being -->
[goal_03_link]: ../goals/goal_03.md
<!-- Sustainable Cities and Communities -->
[goal_11_link]: ../goals/goal_11.md
<!-- Climate Action -->
[goal_13_link]: ../goals/goal_13.md

<!-- Insert SDG Icons and links-->
| [![Goal 03](../images/sdgs/E-WEB-Goal-03.png)][goal_03_link] | [![Goal 11](../images/sdgs/E-WEB-Goal-11.png)][goal_11_link] | [![Goal 13](../images/sdgs/E-WEB-Goal-13.png)][goal_13_link] |
|--------------------------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------|

## Decision makers

- Residents, caregivers, outdoor workers and people at increased risk from heat
- City public-health departments
- Emergency-management and civil-protection authorities
- Municipal social-care, communications and urban-planning teams

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To help individuals decide how to protect themselves and others during extreme heat in a more effective and precise way than the generic warnings and suggestions currently provided by officials.
At the same time, the project aims at helping city administrators decide when and where to activate cooling resources, outreach, transport and other heat-response measures.

## Deliverables

What will be built for this project?

- [ ] Mobile-first web application for residents
- [ ] City operations dashboard and cooling-resource editor
- [ ] Dataset schema and adapters for authoritative alerts, forecasts and municipal resources
- [ ] Optional web-push and messaging integrations
- [ ] Documentation and evaluation report

## Data attributes

### Context

Data that could be taken into account for the decision:
- Official heat warnings and weather forecasts
- Daytime and nighttime heat, humidity, wind, radiation and thermal-stress indices
- Individual circumstances voluntarily selected by the user, such as being a caregiver, outdoor worker or person with limited mobility, without collecting medical diagnoses
- Location, opening hours and accessibility of nearby cooling resources
- Neighborhood population exposure and aggregated vulnerability indicators for city planning
- Capacity and operational status of municipal cooling resources
- Recent heat-related health and emergency-service demand, where aggregated data are available
- Local heat thresholds, languages, communications infrastructure and operational capacity

### Actions

Possible decisions to make:

Individuals can:
- Adjust outdoor activities, travel and work to avoid the hottest periods
- Cool their home, hydrate and choose an appropriate nearby cool place
- Check on relatives, neighbors or other people who may need assistance
- Subscribe to official updates and follow locally approved health guidance

City administrators can:
- Relay official warnings and publish locally approved protective guidance
- Open cooling centers or extend their opening hours
- Allocate staff, drinking water, transport and mobile outreach
- Prioritize neighborhoods with high exposure and low access to cooling resources
- Send approved messages through municipal notification channels
- Plan longer-term measures such as shade, trees, cool roofs and cooling infrastructure

### Outcomes

For individuals, the tool should support the following outcomes:
- Timely access to clear and authoritative warnings.
- Understanding of recommended protective actions.
- Ability to find an open, accessible cool place.
- Adoption of appropriate protective actions for themselves and others.
- Reduced exposure to dangerous heat, evaluated without collecting unnecessary personal or medical data.

For city administrators, the tool should show separate dimensions rather than one heat-risk or vulnerability score:
- Warning and response timeliness: time between an authoritative warning and municipal action.
- Cooling-resource coverage: the population within an agreed walking or transit time of an open cool place.
- Equity: neighborhoods where high exposure overlaps with limited adaptive capacity.
- Operational readiness: available capacity, staffing and freshness of facility information.
- Communication effectiveness: message delivery, comprehension, accessibility and language coverage.
- Health impact: changes in heat-related ambulance calls, emergency visits or hospitalizations over longer evaluation periods.

The target metrics could be:
- Longer-term change in aggregated heat-related illness and emergency-service demand
- Number or percentage of users who successfully find a verified cooling resource
- Use of optional reminders, resource directions and official notification subscriptions
- Time from an official warning to activation of city measures
- Percentage of the population within an agreed travel time of an open cooling resource
- Cooling-center utilization and outreach coverage

## Data

<!-- Describe the data that is used to evaluate the decisions -->
(none)

## Code

<!-- Point to the repo that contains the code -->
(none)

## Needs

List of needs:
- A pilot city and contacts with public-health and emergency-management decision makers
- Access to authoritative warning feeds and locally approved health guidance
- Verified municipal data on cooling centers, water points and other cooling resources
- Aggregated health or emergency-service data for evaluation
- Community partners for co-design, accessibility testing and outreach

## Contributors needed

- Public-health or epidemiology expert
- Meteorologist or climate scientist
- GIS and data engineers
- Web/PWA developers
- UX and accessibility specialists
- Risk-communication, translation and community-engagement contributors
- Privacy and security specialist
- Municipal operations liaison

## References

<!-- Provide a list of references or other resources used in the project -->
- WHO heat-health action planning: https://www.who.int/europe/activities/planning-heat-health-action/planning-heat-health-action
    - Guidance for governance, heat-health warnings, vulnerable populations, communication, health-system resilience, heat-exposure reduction and evaluation.
- WMO Common Alerting Protocol: https://wmo.int/activities/common-alerting-protocol-cap
    - Standard for distributing authoritative emergency warnings through multiple communication channels.
- WMO Severe Weather Information Centre: https://severeweather.wmo.int/sources.html
    - Directory of warnings and CAP feeds issued by national authorities; coverage and availability vary by country.
- MeteoAlarm API for Europe: https://api.meteoalarm.org/
    - Near-real-time official warning data from participating European meteorological services.
- ECMWF open forecast data: https://www.ecmwf.int/en/forecasts/datasets/open-data
    - Open global forecast data; forecasts should not be presented as official local warnings.
- ERA5-HEAT thermal-comfort data: https://cds.climate.copernicus.eu/datasets/derived-utci-historical
    - Historical UTCI and thermal-stress data useful for baselines and retrospective evaluation, not live alerts.
- Landsat surface-temperature data: https://www.usgs.gov/landsat-missions/landsat-surface-temperature
    - Useful for identifying persistent urban hot surfaces; land-surface temperature is not the same as air temperature or personal exposure.
- Population and built-up data: https://human-settlement.emergency.copernicus.eu/datasets.php
    - Global Human Settlement Layer data can support initial exposure estimates but should be validated against local census data.
- OpenStreetMap: https://www.openstreetmap.org/copyright
    - Can help seed maps of public facilities, parks, drinking-water points and transit, but municipal verification is essential.
- Web Content Accessibility Guidelines 2.2: https://www.w3.org/TR/WCAG22/
- https://tree-map.nycgovparks.org/ Every tree in new york city is mapped and this data probably has some interesting uses for the cases of cooling. 
    - It should be possible to do this for other cities through Satellite images
    - https://senseable.mit.edu/treepedia
    - https://github.com/OpenTreeMap/otm-core

## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)
