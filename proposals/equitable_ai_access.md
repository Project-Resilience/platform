# PROJECT ISONOMIA - Ensuring Equitable Global AI Access

<!-- Describe the project in one sentence, e.g. A project that... -->
A project that measures, monitors, and reduces disparities in AI accessibility and
output equity by building an open benchmark, a universal minimum access standard, and
open-source governance tools — making AI-assisted access to information a measurable
public good, the way access to food, electricity and the internet have been before it.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->
[goal_10_link]: ../goals/goal_10.md
[goal_16_link]: ../goals/goal_16.md
[goal_09_link]: ../goals/goal_09.md
[goal_17_link]: ../goals/goal_17.md

<!-- Insert SDG Icons and links-->
| [![Goal 10](../images/sdgs/E-WEB-Goal-10.png)][goal_10_link] | [![Goal 16](../images/sdgs/E-WEB-Goal-16.png)][goal_16_link] | [![Goal 09](../images/sdgs/E-WEB-Goal-09.png)][goal_09_link] |[![Goal 17](../images/sdgs/E-WEB-Goal-17.png)][goal_17_link] |
|------------------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------|--------------------------------------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- National governments and digital policy ministries responsible for AI governance
  and public procurement of AI systems
- United Nations bodies — ITU, UNESCO, UNDP, Human Rights Council — working on
  AI equity, digital inclusion, and rights frameworks
- Multilateral standards bodies (ITU-T, ISO, OECD) developing AI governance instruments
- Civil society organisations working on digital rights, information access, and equity
- Academic institutions developing or independently auditing AI systems
- Enterprises deploying AI in cross-border or multi-jurisdictional contexts

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To measure, predict, and reduce global disparities in AI accessibility and output
equity, and to produce the evidence base and governance tools that enable decision
makers to close the gap between AI-served and AI-excluded populations.

PROJECT ISONOMIA pursues four primary strategic objectives, each mapped to specific UN SDG targets and the Global Digital Compact:


### Objective 1 — Universal Minimum AI Access Standard

Establish the internationally recognised definition of a universal minimum standard for AI accessibility — the floor below which no population should fall in terms of access to unbiased, uncensored, and culturally appropriate AI-assisted information and services. This minimum is defined in terms of functional outcomes, not technical specifications, drawing on the precedent of the FAO right-to-food framework and UNESCO internet access principles.

- SDG 10.3: Reduce inequality; ensure equal opportunity regardless of national origin or economic status
- SDG 16.b: Promote and enforce non-discriminatory laws and policies
- GDC Commitment: Promote inclusive, open, and safe AI for all


### Objective 2 — Evidence-Based Bias Taxonomy

Develop and maintain the globally validated taxonomy of AI bias types across geopolitical, cultural, linguistic, and data sovereignty dimensions, extending and standardising existing research and empirical frameworks into a dynamic, open-source, continuously maintained resource hosted in the AI and Data Commons.

- SDG 17.18: Build capacity for high-quality, disaggregated data
- SDG 17.19: Develop measurements of progress on sustainable development


### Objective 3 — Global AI Accessibility Standards

Produce binding-ready ITU-T Recommendations governing minimum standards for AI accessibility across jurisdictions, including prohibition of geofencing that excludes populations from equivalent AI access and requirements for model transparency regarding training data provenance and regional coverage.

- SDG 9.c: Significantly increase access to information and communications technology
- SDG 17.6: Enhance international cooperation on science, technology and innovation
- UDHR Article 19: Right to freedom of opinion and expression


### Objective 4 — AI Equity Benchmark: Continuous Global Monitoring

Build, maintain, and publicly publish an AI Equity Benchmark — a continuously updated, open dataset tracking AI accessibility disparities, bias indicators, and data sovereignty compliance across jurisdictions and model vendors — serving as the empirical foundation for UN reporting on AI equity within the SDG monitoring framework.

- SDG 16.10: Ensure public access to information and protect fundamental freedoms


## Deliverables

What will be built for this project?

<!-- Describe the deliverables of the project. For instance: -->

- [x] Publication: **Universal Minimum AI Access Standard** — functional floor definition below
      which AI service quality must not fall, expressed in outcome terms, developed
      through open multilateral consultation
- [x] Publication: **Global AI Access Gap Report** — annual publication mapping where the minimum
      standard is breached, by region and failure type (geofencing / censorship / cultural bias / linguistic exclusion)
- [x] API: **AI Equity Benchmark** — open, continuously updated dataset quantifying AI
      accessibility and output bias across jurisdictions and model families; public API
      for third-party model submission and evaluation
- [x] Publication: **Standards Proposals** — input documents for ITU-T, OECD, and UN governance processes based on benchmark findings
- [x] TOOL: **Open-Source Assessment Toolkit** — replicable tools enabling governments,
      civil society, and enterprises to run their own AI equity assessments
- [x] User interface: **Interactive Decision-Support Platform** — public-facing tool for exploring
      the AI access gap by jurisdiction and simulating policy interventions

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **JurisdictionIncomeLevel**
   - Possible values: `High-income`, `Upper-middle-income`, `Lower-middle-income`,
     `Low-income`, `LDC`, `SIDS`
2. **AIAccessibilityScore** (numerical, 0–100)
   - Proportion of major LLM families accessible without restriction in jurisdiction
3. **CensorshipPresenceIndex** (numerical, 0–100)
   - Frequency of undisclosed content filtering detected in model outputs
     when queried from the jurisdiction
4. **GeopoliticalBiasScore** (numerical, 0–100)
   - Degree of systematic geopolitically-structured output variation across
     available model families in jurisdiction
5. **CulturalRepresentationGap** (numerical, 0–100)
   - Divergence between model cultural assumptions and jurisdiction's documented
     norms, measured via structured scenario testing
6. **LinguisticCoverage** (numerical, percentage)
   - Share of jurisdiction's principal languages with adequate LLM training data
     coverage
7. **ConnectivityIndex** (numerical, 0–100))
   - ITU broadband access composite score for jurisdiction
8. **DigitalLiteracyRate** (numerical, percentage)
   - The percentage of a jurisdiction's population with sufficient digital skills to meaningfully use AI-assisted tools and services.
9. **AIGovernanceMaturity**
   - Possible values: `No framework`, `Ad Hoc`, `Defined`, `Operationalised`, `Enforced-Legally`, `Enforced-Legally and Technically`
    - Number and geographic diversity of accessible AI providers in jurisdiction

### Actions

<!-- Describe what the decision makers can do to achieve their objectives -->
Decision makers can take the following actions:

1. **PolicyIntervention**: Geofencing Prohibition, Censorship Disclosure Mandates,
     Procurement Standards, Local Model Investments, Multilingual Data Funding
2. **GovernanceInstrumentType**: Voluntary Guideline, National Regulations,
     Bilateral Agreements, Multilateral Standards
3. **BenchmarkAdoptionLevel**: Observer, Contributor, Binding References
4. **InfrastructureInvestment** (numerical, millions USD)
5. **CapacityBuildingScope**: Government, Civil Society, Private Sector, All
6. **EvaluationFrequency**: Continuous, Quarterly, Annual

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:


1. **ChangeInAIAccessibilityScore** (numerical, change in 0–100 scale) (Maximize)
2. **ChangeInCensorshipPresenceIndex** (numerical, change in 0–100 scale) (Minimize)
3. **ChangeInGeopoliticalBiasScore** (numerical, change in 0–100 scale) (Minimize)
4. **ChangeInCulturalRepresentationGap** (numerical, change in 0–100 scale) (Minimize)
5. **PopulationsReachingMinimumStandard** (numerical, millions of people) (Maximize)
6. **JurisdictionsAdoptingStandards** (numerical, count) (Maximize)
7. **BenchmarkLLMCoverage** (numerical, percentage of accessible LLMs evaluated) (Maximize)

## Data

<!-- Describe the data that is used to evaluate the decisions -->
The benchmark dataset will be assembled from:

- Multi-vendor LLM query testing across geolocation, topic, and language
- ITU Digital Inclusion datasets (broadband access, device penetration, digital literacy)
- UNESCO Internet Universality country assessments
- OECD.Stat indicators on AI governance and digital economy
- UN SDG monitoring datasets (SDGs 9, 10, 16, 17)
- Civil society documentation of access restrictions and censorship incidents

All data, methodology, and results are published openly on the Project Resilience
platform. Third parties may submit models for evaluation via a public API.



## Code

<!-- Point to the repo that contains the code -->
(none — repository to be established at project launch)

## Needs
<!-- What kind of help is currently needed for this project? -->

List of needs:
- **Increase awareness of decision makers** - Discuss the topic at UN driven AI events to attract attention of decision makers to this problem.
- **Contacts with decision makers** — national AI policy officials, ITU and UNESCO
  representatives, digital rights civil society organisations
- **UI/UX designers** — public-facing interactive decision-support platform
- **Data scientists** — LLM evaluation, bias detection methodology, longitudinal
  statistical analysis across heterogeneous data sources
- **Data** — regional LLM access restriction documentation, civil society censorship
  incident records, national AI governance maturity assessments
- **Compute** — continuous multi-vendor LLM querying at scale across geolocations
- **Legal and policy experts** — international standards processes (ITU-T, ISO, OECD),
  AI governance frameworks (EU AI Act, Global Digital Compact)
- **Linguists and cultural experts** — culturally grounded test scenario design for
  underrepresented languages and regions
- **Institutional partners** — academic institutions and national AI research bodies
  to contribute regional data and co-author benchmark reports
## References

1. OECD AI Principles (2024). Organisation for Economic Co-operation and Development.
   https://www.oecd.org/en/topics/sub-issues/ai-principles.html
2. UNESCO Internet Universality Indicators (2019). UNESCO, Paris.
   https://www.unesco.org/en/internet-universality-indicators
3. ITU Digital Inclusion Reports. International Telecommunication Union.
   https://www.itu.int/en/ITU-D/Digital-Inclusion/
4. FAO — The Right to Food (2004). Food and Agriculture Organisation, Rome.
   https://www.fao.org/right-to-food
5. United Nations — Universal Declaration of Human Rights, Article 19 (1948).
   https://www.un.org/en/about-us/universal-declaration-of-human-rights
6. EU Artificial Intelligence Act — Regulation (EU) 2024/1689 (2024).
   Official Journal of the European Union.
7. United Nations — Global Digital Compact (2024). UN General Assembly.
   https://www.un.org/global-digital-compact
8. MIT AI Risk Repository — AI Risk Taxonomy (2024).
   https://airisk.mit.edu
9. Project Resilience — ITU-T Global Initiative on AI and Data Commons.
   https://www.itu.int/en/ITU-T/extcoop/ai-data-commons/Pages/project-resilience.aspx
10. Evaluating Regional Biases, Geofencing, Data Sovereignty, and
Censorship in LLM Models.
    https://documents.trendmicro.com/assets/research-reports/unmanaged_ai_adoption.pdf

## Discussion

<!-- Provide a link to a space for discussion or comments -->
- [Ensuring Equitable Global AI Access](https://github.com/Project-Resilience/platform/discussions/94)

----
[Back to the list of projects](../README.md)
