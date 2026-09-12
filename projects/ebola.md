# Ebola prevention and control

<!-- Describe the project in one sentence, e.g. A project that... -->
A platform to simulate the spread of Ebola in a social setting
and evaluate prevention and control strategies.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->
[goal_03_link]: ../goals/goal_03.md

<!-- Insert SDG Icons and links-->
| [![Goal 03](../images/sdgs/E-WEB-Goal-03.png)][goal_03_link] | ![](../images/sdgs/empty.png) | ![](../images/sdgs/empty.png) |
|------------------------------------------------------|------------------------------------------------------|-------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- [Coalition for Epidemic Preparedness Innovations (CEPI)](https://cepi.net/)
- United Nations (UN), in particular the [World Health Organization (WHO)](https://www.who.int/)
- Red Cross of the Democratic Republic of the Congo (CRRDC) and its [Dignified and Safe Burial team](https://www.icrc.org/en/article/drc-ebola-red-cross-volunteers-carry-out-burials-and-build-trust-affected-communities)
- Doctors, practitioners and ONGs operating in situations where epidemics are spreading

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To help decision makers test different approaches in their fight against epidemics, in particular Ebola.

## Deliverables

<!-- Provide links to the deliverables of the project -->
<!-- For instance, a link to the interactive application -->
A simulator and user interface that decision makers can use to test different conditions.

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
Decision makers are monitoring a epidemic spreading in a community in which multiple actors are present. These actors can look positively or negatively towards external help, doctors and international organizations.

The situation can be described by the following attributes:
- a geographical region under study (e.g. a village, maybe with a hospital or a dispensary)
- a community, with:
  - different groups of people or individuals
  - a behavior for each of these groups or individuals
  - some level of infection in the community
- a virus and its characteristics:
  - Transmission mode: contact-based (e.g. Ebola), airborne (e.g. COVID19), vectorborne (e.g. Malaria via mosquitoes)
  - a R0

### Actions

<!-- Describe what the decision makers can do to achieve their objectives -->
Decision makers can choose between different approaches to fight the epidemic:
- suggest the use, carry and distribution of Personal Protection Equipment
- develop and distribute vaccines with different percentages of efficacy
- do widespread communication campaign
- actively fight misinformation
- build and manage hospitals
- recommend Dignified and Safe Burial practices

The platform allows the introduction of different agents and actors in the simulator to evaluate their possible behaviors.

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

- Spread of the epidemic
- Death toll
- Cost of the interventions

## Code

<!-- Point to the repo that contains the code -->
- The code for this project is available here: [TerraLingua Pandemics](https://github.com/GPaolo/terralingua-pandemics)
- The code for the simulation configuration tool is available here: [TerraLingua Launcher](https://github.com/GPaolo/terralingua_launcher)

## Needs
<!-- What kind of help is currently needed for this project? -->

List of needs:
- Contacts with decision makers
- UI/UX experts
- Biologists
- Sociologists

## References

<!-- Provide a list of references or other resources used in the project -->
- TerraLingua is the platform on top of which the simulator is built. [Paper](https://arxiv.org/abs/2603.16910) - [OpenSource Code](https://github.com/cognizant-ai-lab/terralingua)
- [Epydemix](https://www.epydemix.org/) is a platform that can help finetune the virus parameters in the simulation
- Recent set of [recommendations for the fight against Ebola](https://www.who.int/news/item/24-08-2026-second-meeting-of-the-ihr-emergency-committee-on-the-epidemic-of-ebola-bundibugyo-virus-disease-in-the-democratic-republic-of-the-congo-temporary-recommendations) from the WHO
- Information about the community engagement and communal burials, [which seem to be critical aspects in this fight](https://www.who.int/news/item/06-08-2026-africa-cdc-and-who-call-for-urgent--community-led-action-to-contain-ebola-in-the-drc)
- The way the virus spreads and kills people has been modeled following the [information from WHO](https://www.who.int/news-room/fact-sheets/detail/ebola-disease)
- The work of the [Red Cross volunteers on the ground](https://www.icrc.org/en/article/drc-ebola-red-cross-volunteers-carry-out-burials-and-build-trust-affected-communities)

## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)
