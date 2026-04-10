# Optimizing Startup Investment Returns Through Unbiased Evaluation

<!-- Describe the project in one sentence, e.g. A project that... -->
A project that builds a financial model for venture capital and angel investors to maximize portfolio returns and minimize risk by identifying and correcting gender bias in startup evaluation — a systematic market inefficiency that causes investors to overlook high-performing opportunities.

<!-- Note: using reference-style links to let Jekyll's relative links
convert them to .html in GitHub pages -->
[goal_05_link]: ../goals/goal_05.md
[goal_10_link]: ../goals/goal_10.md

<!-- Insert SDG Icons and links-->
| [![Goal 05](../images/sdgs/E-WEB-Goal-05.png)][goal_05_link] | [![Goal 10](../images/sdgs/E-WEB-Goal-10.png)][goal_10_link] | ![](../images/sdgs/empty.png) |
|--------------------------------------------------------------|--------------------------------------------------------------|-------------------------------|

## Decision makers

<!-- List decision makers that could use this project-->
- Venture capital fund managers
- Angel investors
- Limited partners (LPs) in VC funds
- Startup accelerator and incubator program directors

## Objectives

<!-- Describe the objectives of the project in one sentence -->
To maximize portfolio returns and minimize investment risk by correcting a well-documented evaluation bias that distorts deal selection. Research by Kanze et al. shows that investors systematically ask male founders promotion-focused questions (about upside potential, growth, and aspirations) and female founders prevention-focused questions (about downside risk, losses, and threats). Examples of promotion-focused questions typically asked to men:

- "How do you plan to acquire new customers?"
- "What's your vision for scaling this?"
- "How big could this market get?"

Examples of prevention-focused questions typically asked to women:

- "How do you plan to prevent customer churn?"
- "What if a competitor enters your space?"
- "How will you avoid running out of cash?"

This framing bias creates a market inefficiency: founders fielding promotion questions can articulate ambitious visions, while those receiving prevention questions are pushed into a defensive posture, resulting in significantly less funding regardless of company quality. The result is that investors systematically underfund a segment that generates higher returns — BCG found that women-founded startups generate 78 cents per dollar invested vs. 31 cents for male-founded startups, and First Round Capital's data shows investments in female founders outperformed by 63%. The project aims to build a financial model that corrects this evaluation bias so that investors can capture these overlooked returns while building more diversified, lower-risk portfolios.

## Deliverables

What will be built for this project?

<!-- Describe the deliverables of the project. For instance: -->
- [ ] Financial model that recommends portfolio allocation strategies optimized for return and risk, accounting for evaluation bias correction
- [ ] User interface for investors to analyze their pitch meeting transcripts and identify where evaluation bias may be distorting deal selection
- [ ] APIs for real-time bias detection during investor Q&A sessions to improve evaluation quality
- [ ] Data on question framing patterns (promotion vs. prevention orientation) and their correlation with investment returns
- [ ] Benchmarks comparing portfolio performance of bias-corrected vs. uncorrected investment processes
- [ ] Models trained to classify investor questions as promotion-oriented or prevention-oriented
- [ ] Publications summarizing findings on the return and risk impact of correcting evaluation bias

## Data attributes

### Context

<!-- Describe the situation decision makers are in when then have to make a decision -->
The situation decision makers are in when they have to make a decision can be described by the following attributes:

1. **InvestmentStage** (Categorical): ['PreSeed', 'Seed', 'SeriesA', 'SeriesB', 'Growth']
2. **FundSize** (Numerical, integer): Total fund size in USD, influencing check sizes and deal flow.
3. **Sector** (Categorical): ['Technology', 'Healthcare', 'FinTech', 'ConsumerGoods', 'CleanTech', 'Other']
4. **FounderGender** (Categorical): ['Male', 'Female', 'Mixed']
5. **TeamGenderBalance** (Numerical, integer): Percentage of the founding team that is female (0-100).
6. **GPTeamGenderBalance** (Numerical, integer): Percentage of the fund's General Partners that is female (0-100).
7. **GeographicRegion** (Categorical): ['NorthAmerica', 'Europe', 'Asia', 'LatinAmerica', 'Africa', 'Other']
8. **PriorFundingRaised** (Numerical, integer): Amount of prior funding the startup has raised in USD.
9. **QuestionFraming** (Categorical): ['Promotion', 'Prevention', 'Neutral'] - Whether the investor's questions focus on potential gains (promotion) or potential losses (prevention), as identified by Kanze et al.
10. **InvestorExperience** (Numerical, integer): Years of investing experience.
11. **PortfolioDiversification** (Numerical, integer): Number of distinct sectors and founder demographics represented in the current portfolio.

### Actions

<!-- Describe what the decision makers can do to achieve their objectives -->
Decision makers can take the following actions:

1. **StructuredEvaluation** (Categorical): ['No', 'Yes'] - Whether a standardized evaluation rubric is used for all founders regardless of gender, reducing noise in deal selection.
2. **QuestionReframing** (Categorical): ['No', 'Yes'] - Whether investors actively reframe prevention-oriented questions into promotion-oriented equivalents to get comparable signal from all founders.
3. **BlindScreening** (Categorical): ['No', 'Partial', 'Full'] - Degree to which initial screening removes gender-identifying information to reduce selection bias.
4. **PortfolioGenderTarget** (Numerical, integer): [0, 100] - Target percentage of portfolio companies with female founders or gender-balanced teams, as a diversification lever.
5. **PostPitchReview** (Categorical): ['No', 'Yes'] - Whether pitch meetings are reviewed for evaluation bias patterns to improve decision quality over time.
6. **BiasTraining** (Categorical): ['None', 'Awareness', 'Structured'] - Level of bias-awareness training for the investment team.

### Outcomes

<!-- Describe the metrics decision makers are trying to optimize, on which they are evaluated -->
Decision makers are evaluated on the following outcomes:

1. **PortfolioReturn** (Numerical, integer): Internal Rate of Return (IRR) of the fund's portfolio, in percentage. Research shows that correcting gender evaluation bias unlocks access to a higher-performing, underfunded segment — BCG reports women-founded startups generate 2.5x more revenue per dollar invested, and First Round Capital data shows 63% higher returns from investments in female founders. (Maximize)
2. **PortfolioRisk** (Numerical, integer): Portfolio risk measured as the standard deviation of returns across portfolio companies, in percentage. Correcting evaluation bias leads to more diversified deal flow and more consistent evaluation quality, both of which reduce return variance. Gender-balanced leadership teams correlate with ~25% greater increases in valuation per IFC research, contributing to more stable portfolio performance. (Minimize)

## Data

<!-- Describe the data that is used to evaluate the decisions -->
(none)

## Code

<!-- Point to the repo that contains the code -->
(none)

## Needs
<!-- What kind of help is currently needed for this project? -->

List of needs:
- Contacts with VC firms and angel investor networks willing to share anonymized portfolio performance data
- Access to anonymized pitch meeting transcripts and funding decision data with return outcomes
- Data scientists experienced in financial modeling and portfolio optimization
- NLP/data scientists experienced in bias detection and text classification
- UI/UX experts for building investor-facing portfolio analysis tools
- Partnerships with organizations like the Inclusive AI Lab or The Inclusive AI
- Funding for research and tool development

## References

<!-- Provide a list of references or other resources used in the project -->
- Kanze, D., Huang, L., Conley, M. A., & Higgins, E. T. "We Ask Men to Win and Women Not to Lose: Closing the Gender Gap in Startup Funding." [Harvard Kennedy School](https://gap.hks.harvard.edu/we-ask-men-win-and-women-not-lose-closing-gender-gap-startup-funding), [ResearchGate](https://www.researchgate.net/publication/335679671_We_Ask_Men_to_Win_and_Women_Not_to_Lose_Closing_the_Gender_Gap_in_Startup_Funding), [Harvard Business School](https://www.hbs.edu/faculty/Pages/item.aspx?num=54068)
- Boston Consulting Group. ["Why Women-Owned Startups Are a Better Bet."](https://www.bcg.com/publications/2018/why-women-owned-startups-are-better-bet) Key finding: women-founded startups generate 78 cents per dollar invested vs. 31 cents for male-founded startups.
- TechCrunch. ["Broaden Your View of 'Best' to Make Smarter, More Inclusive Investments."](https://techcrunch.com/2021/02/26/broaden-your-view-of-best-to-make-smarter-more-inclusive-investments/)
- First Round Capital. [10 Year Project.](https://10years.firstround.com/#one) Key finding: investments in female founders outperformed by 63%.
- IFC (World Bank). ["Moving Toward Gender Balance in Private Equity and Venture Capital."](https://www.ifc.org/content/dam/ifc/doclink/2019/report-moving-toward-gender-balance-in-private-equity-and-venture-capital.pdf) Key findings: (1) Gender-balanced leadership teams correlate with ~25% greater increases in valuation; (2) Imbalance in portfolio companies is related to imbalance in GP investment teams.

## Discussion

<!-- Provide a link to a space for discussion or comments -->
- [Discussions about Goal 5: Gender Equality](https://github.com/Project-Resilience/platform/discussions/27)
- [Discussions about Goal 10: Reduce inequality within and among countries](https://github.com/Project-Resilience/platform/discussions/32#discussioncomment-15828390)

[Back to the list of projects](../README.md)
