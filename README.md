Research catalogue & repository index
On this page I'm trying to catalogue my research questions and link them to various repositories. The goal is to have a compact, navigable summary of my research ideas and project themes so visitors can quickly find code, papers, and research directions. Obviously, it's a work in progress....

Swap Medicaid for Universal Pre-K (Tags: Finance, Education Policy)

Proposal: Model federal funding of universal Pre-K by reallocating state/local Medicaid costs.
Why it matters: Large-scale early education policy could reduce inequality.
Possible repo links: policy-models, budget-sim
Federal Assumption of State Pension Debt (Tags: Finance, Fiscal Policy)

Proposal: Simulate federal assumption of pension liabilities and tax-reform financing.
Why it matters: Stabilize public pensions and analyze tax trade-offs.
Possible repo links: pension-sims, fiscal-data-tools
Housing Permits and Affordability (Tags: Housing, Urban Economics)

Proposal: Analyze building permits as % of housing stock vs. prices/rents across MSAs.
Why it matters: Empirical evidence for policy on housing supply.
Possible repo links: housing-permits, msa-visualizations
Impact of New Housing Supply on Prices (Tags: Housing, Urban Economics)

Proposal: Model how adding X units affects prices and rents (counterfactuals).
Why it matters: Quantify supply-side interventions for affordability.
Possible repo links: housing-models, counterfactual-sim
AI for Crime Prediction (“Cops on the Dots”) (Tags: Policing, Data Science)

Proposal: Use ML to predict spatial-temporal crime hot spots from open data.
Why it matters: Resource allocation and preventive policing (with ethics analysis).
Possible repo links: crime-forecast, spatial-ml
Police Use-of-Force Metrics and Crime Outcomes (Tags: Policing, Accountability)

Proposal: Rate departments on use-of-force trends and compare to crime trajectories.
Why it matters: Inform accountability and de-escalation policy.
Possible repo links: policing-metrics, force-vs-outcomes
Excess COVID-19 Mortality (Demographic Analysis) (Tags: Public Health, COVID-19)

Proposal: Compute excess deaths by race/age/gender and check undercounting early in the pandemic.
Why it matters: Reveals disparities and improves public-health data practices.
Possible repo links: excess-mortality, covid-demog
Cross-Country COVID-19 Outcomes Comparison (Tags: Public Health, Global)

Proposal: Compare excess vs reported deaths across countries, adjusting for demographics.
Why it matters: Learn which strategies reduced mortality and why.
Possible repo links: covid-crosscountry, pandemic-comparative
Malaria Mitigation Effectiveness (Tags: Global Health, Epidemiology)

Proposal: Identify policies and interventions linked to large declines in malaria mortality (2000–2019).
Why it matters: Translate comparative success into policy recommendations.
Possible repo links: malaria-analytics, global-health-case-studies
High Murder Rates and Policing in Developing Countries (Tags: Crime, International Development)

Proposal: Study causes of very high homicide rates and the role of police legitimacy vs deployment.
Why it matters: Inform interventions in high-violence contexts.
Possible repo links: homicide-intl, police-legitimacy
(Reference: Full spreadsheet: "Academic Questions List - Feb 26, 2021.xlsx")

Grouped / combined project themes
These groups combine related ideas into projects that can share data pipelines, models, and visualizations.

Housing Supply & Affordability
Combine: ideas 3 & 4 — historical permit analysis + counterfactual supply models.
Work items: data ingestion (Census, building permits), visualization notebooks, price-impact model.

Crime Data Analysis & Prediction
Combine: predictive models (idea 5) with correlation/lag studies and cross-geography analyses.
Work items: city-level datasets, spatial ML pipelines, ethics/PIA notebook.

Crime Demographics & Community Factors
Combine: youth-share vs crime, demographic-specific homicide rates.
Work items: demographic-normalized rates, maps, cohort analyses.

Policing Strategy & Performance
Combine: use-of-force metrics, deployment effectiveness, historical inequities.
Work items: departmental dashboards, time-series analyses, policy simulation.

Public Finance & Fiscal Policy
Combine: pension debt takeovers, Medicaid → Pre-K swap, fines/fees analysis.
Work items: budget models, revenue-impact scenarios, policy brief drafts.

Government Performance Metrics & Urban Indices
Combine: essential metrics for agencies, Urban Development Index.
Work items: index design, cross-city benchmarking visualizations.

City Infrastructure & Service Efficiency
Combine: waste/recycling efficiency, paving material cost comparisons.
Work items: lifecycle cost models, comparative case studies.

COVID-19 Excess Mortality Analysis
Combine: within-country demographic analysis + cross-country comparisons.
Work items: mortality excess pipeline, age-standardization tools, results paper/notebook.

Data Science Methods & Tools
Combine: new datasets for prediction, correlation matrices, visualization examples.
Work items: reusable utilities, example notebooks, tutorial READMEs.

How this README maps ideas → repos
Featured projects section (below) should point to the primary repos for each idea/group.
For each project repo I recommend a short README, one notebook that reproduces the main figure, and a small "data notes" file listing sources and refresh instructions.
Featured projects (replace/add links)
housing-permits — analyze permits per 1,000 housing units and plot price trends.
Tech: Python, pandas, altair · Status: active · Note: includes MSA example.

crime-forecast — spatial-temporal models for hotspot prediction.
Tech: Python, scikit-learn, geopandas · Status: prototype

excess-mortality — excess-death pipeline & demographic breakdowns.
Tech: R and Python notebooks · Status: maintained

LinkedIn / Google Scholar / ORCID links
Next steps I can do for you
Populate the Featured and Full catalogue automatically by fetching your public repos (requires permission/working GitHub API). I attempted this but hit an API/tool error (see note below).
Or: you can paste a list of featured repos (names + 1–2 line descriptions) and I will finish the README.
Or: tell me a repo (owner/repo) where to push this README and I will create README.md there.
Thanks — tell me which of the three options you want (manual fill, try fetching again, or push README to repo owner/repo) and I’ll proceed.

README.md
