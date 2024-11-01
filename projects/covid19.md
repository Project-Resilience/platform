# Non-pharmaceutical interventions for COVID-19

<!-- Describe the project in one sentence, e.g. A project that... -->
Authorities have been responding in a variety of ways to the COVID-19 crisis. Many different non-pharmaceutical
interventions (NPIs) have been implemented at different stages of the pandemic and in different contexts. However,
there is little experience or guidance on how well they work, and computational modeling has therefore become a crucial
tool for making informed decisions on how to prevent the spread of the disease, as well as how to restart the economy.

The goal of this project is to predict what the number of cases will be, according to the non-pharmaceutical
intervention plan that is implemented, and to optimize the plan to minimize the number of cases while minimizing the
economic impact of the pandemic.

An [XPRIZE competition](https://www.xprize.org/challenge/pandemicresponse) was organized, with many teams participating
worldwide, to:
- first predict the number of cases according to NPI plans
- then optimize the NPI plan to minimize the number of cases while minimizing the economic impact of the pandemic.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->
[goal_03_link]: ../goals/goal_03.md
[goal_16_link]: ../goals/goal_16.md

<!-- Insert SDG Icons and links-->
| [![Goal 03](../images/sdgs/E-WEB-Goal-03.png)][goal_03_link] | [![Goal 16](../images/sdgs/E-WEB-Goal-16.png)][goal_16_link] | ![](../images/sdgs/empty.png) |
|--------------------------------------------------------------|--------------------------------------------------------------|-------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- National leaders (E.g. Presidents, Prime Ministers and health ministers)
- Public Health Authorities
- Scientific Advisors
- Local leaders (E.g. Governors, mayors and regional authorities)

## Objectives

To minimize the number of COVID-19 cases while minimizing the economic impact of the pandemic.

## Interactive application

<!-- Provide a link to the interactive application -->
The user interface is available here: [COVID-19 NPIs](https://evolution.ml/demos/npidashboard/)

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in can be described by the following time series:

- Historical number of COVID-19 cases, daily
- Historical NPIs implemented, daily

### Actions

<!-- Describe what the decision makers can do achieve their objectives -->
Decision makers can decide, on a daily basis, what the intervention plan should be:
- C1_School closing
- C2_Workplace closing
- C3_Cancel public events
- C4_Restrictions on gatherings
- C5_Close public transport
- C6_Stay at home requirements
- C7_Restrictions on internal movement
- C8_International travel controls
- H1_Public information campaigns
- H2_Testing policy
- H3_Contact tracing
- H6_Facial Coverings

See the description of [Containment and closure policies](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md#containment-and-closure-policies)
and [Health system policies](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md#health-system-policies) for more details. 

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
- Number of COVID-19 cases over time (Minimize)
- Stringency of intervention plans over time (Minimize)

## Data

<!-- Describe the data that is used to evaluate the decisions -->
The dataset of historical cases and NPIs is available here: [OxCGRT_latest.csv](https://raw.githubusercontent.com/OxCGRT/covid-policy-tracker-legacy/main/legacy_data_202207/OxCGRT_latest.csv)

The data was collected according to this [codebook](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md)

More info in the [OxCGRT](https://github.com/OxCGRT/covid-policy-dataset) repo.

## Code

<!-- Point to the repo that contains the code -->
The code for this project is available here: [covid-xprize](https://github.com/cognizant-ai-labs/covid-xprize)

## References

<!-- Provide a list of references or other resources used in the project -->
- The Oxford Covid-19 Government Response Tracker project: [OxCGRT](https://www.bsg.ox.ac.uk/research/covid-19-government-response-tracker)
- The XPRIZE Pandemic Response Challenge: [XPRIZE Pandemic Response Challenge](https://www.xprize.org/challenge/pandemicresponse)
- The XPRIZE Pandemic Response Challenge technical details: [Technical setup, assessment and results](https://evolution.ml/xprize/)
- The XPRIZE Pandemic Response Challenge GitHub repo: [covid-xprize](https://github.com/cognizant-ai-labs/covid-xprize)
- The Global Partnership on Artificial Intelligence (GPAI)’s project report: [Pandemic Resilience: Developing an AI-calibrated Ensemble of Models to Inform Decision Making](https://gpai.ai/projects/responsible-ai/RAI06%20-%20Pandemic%20Resilience%20-%20Developing%20an%20AI-calibrated%20ensemble%20of%20models%20to%20inform%20decision%20making.pdf) (2023)
- Research paper: [From Prediction to Prescription: Evolutionary Optimization of Non-pharmaceutical Interventions in the COVID-19 Pandemic](https://ieeexplore.ieee.org/document/9366776) (2021)


## Discussion

<!-- Provide a link to a space for discussion or comments -->
(no discussion yet)

[Back to the list of projects](../README.md)