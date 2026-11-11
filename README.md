# Gnanaram M

Solutions consultant in US pharma and biotech commercial strategy and market
access. I turn commercial questions into data, models and product concepts:
who to target, what a policy change costs, how fast a brand will erode, and
what a better tool for the team would look like.

## Featured work

### [US Pharma Commercial Analytics](https://github.com/Gnanaram23/us-pharma-commercial-analytics)
Seven end-to-end case studies on US pharma commercial questions. Five run on
free public government data (CMS Medicare, Medicaid, Open Payments, FDA,
ClinicalTrials.gov); two use simulations with a known answer, so the methods
can be graded rather than trusted. Each has the data pull, Python analysis, a
rendered notebook, a written recommendation, and what did not work.

| Project | Question | Headline result | Methods |
|---|---|---|---|
| [GLP-1 market & prescriber targeting](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/01-glp1-market-and-targeting) | Where is GLP-1 growth left in Medicare, and which prescribers come first? | $27.9B market growing 40% a year; 6,700 prescribers hold half of a 4M-claim opportunity | Gradient boosting, SHAP reason codes, back-tested growth curves |
| [IRA negotiation exposure](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/02-ira-negotiation-exposure) | Who loses most from Medicare price negotiation, and who is next? | $21–25B a year in net impact; screen picked 11 of 15 actual selections in back-tests | Rules plus ML selection model, back-testing |
| [Loss-of-exclusivity forecast](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/03-loe-erosion-forecast) | How fast do brands erode, and what happens to Eliquis in 2028? | Two erosion regimes in Medicaid; Eliquis's free-to-Medicaid deal points to retention | Bayesian hierarchical mixture model, conformal prediction |
| [Obesity pipeline intelligence](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/04-obesity-pipeline-intelligence) | Who competes in US obesity by 2030? | About 10 new approvals expected, almost all in 2029–30; the leaders win on scale, not speed | Monte Carlo, Kaplan–Meier and Cox survival models, text mining |
| [Omnichannel HCP engagement](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/05-omnichannel-hcp-engagement) | Does promotion reach the right prescribers, and what should each one get next? | Top brand reaches 57% of top-decile prescribers; every attribution method misplaces ~30% of credit; a learning policy beats rules by 14% | Propensity matching, Markov and Shapley attribution, X-learner uplift, contextual bandits |
| [Marketing mix model](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/06-marketing-mix-model) | What does each channel return, and where should the next dollar go? | Calibrating with lift tests fixes the small channels; an optimiser can overpromise when the curve shape is wrong | Bayesian MMM (PyMC), adstock and saturation, lift-test calibration, budget optimisation |
| [Test & control experiments](https://github.com/Gnanaram23/us-pharma-commercial-analytics/tree/main/07-test-and-control-experiments) | What happens when Medicaid drops obesity drug coverage, and how should a pilot be sized? | Coverage removal cut use 75–93%; only 57% came back after restart; DiD with adjustment detects a 10% lift | Synthetic control, DiD, placebo tests, event study, power simulation |

**AI workflow:** an open-weights language model drafts a brief of each project
for a brand lead and for an analytics reviewer, and a checker traces every
number in each draft back to the project's results before it is published.

### [Life Sciences Product Concepts](https://github.com/Gnanaram23/Product-Concepts---Commercial-)
Four product concepts, each taken from problem statement to PRD to a working prototype. **[Try them in your browser](https://gnanaram23.github.io/Product-Concepts---Commercial-/)**.

- **Cortex:** governed AI analytics. A semantic layer turns plain-English questions about rebates and gross-to-net into SQL, and every answer comes with its query and sources.
- **ClearAuth:** a prior authorization platform for providers, patients and payers, with a coverage-policy engine that checks each request against plan criteria.
- **Pharma Action Builder:** Next Best Action for HCP engagement. It trains gradient boosting, random forest and other models in the browser and picks each HCP's best tactic by expected value.
- **GVD Process Map:** the end-to-end process for building a Global Value Dossier.

## What I work on

- **Commercial analytics:** market sizing, prescriber segmentation and targeting, forecasting
- **Market access:** IRA and Medicare policy impact, payer dynamics, loss-of-exclusivity planning
- **Product and AI:** turning a workflow problem into requirements, prototypes and an AI use case
- **Consulting:** solution design, proposals and stakeholder workshops for pharma and biotech clients

## Tools

Python (pandas, scikit-learn, SciPy, statsmodels, PyMC, SHAP, matplotlib) · TypeScript, React, Node.js, SQL ·
gradient boosting, Bayesian hierarchical models, causal inference (synthetic control, DiD, matching, uplift),
survival analysis, bandits, Monte Carlo · LLM workflows with open models (Ollama) · Jupyter · GitHub Actions ·
public healthcare data (CMS Medicare, Medicaid SDUD, Open Payments, openFDA, ClinicalTrials.gov) ·
AI-assisted prototyping (Lovable, Replit)

## Background

PGDM (Marketing, Analytics and Operations), Great Lakes Institute of Management ·
B.Tech Mechanical Engineering, Amrita Vishwa Vidyapeetham · Based in Chennai, India

[LinkedIn](https://linkedin.com/in/gnanaram/)
