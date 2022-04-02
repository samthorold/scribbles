## Risk quantification

For all risks, the probability of occurrence (frequency) and expected loss
(severity) need to be assessed.
These are normally treated as random variables in models.

Risks are commonly assessed using simple scales which rate frequency and
severity from low to high.
The product of frequency and severity scales represents the overall score
for that risk, enabling them to be ranked.
The assessment would be done with and without controls, to assess their
efficiency.
The assessment may be recorded in a risk register.

It is difficult to model low frequency events due to a lack of data.

Operational risk in particular can be difficult to quantify.
Approaches include;

- Broadbrush addition to other risks (for capital requirements)
- Scenario analysis

## Evaluation of risks

- [2018 April Paper 2 Q4](40-2018-04-02.md#4)

**Scenario analysis** is useful where it is difficult to fit full probability
distributions to risk events.

- For each group of risks a representative plausible scenario is developed.
- For each scenario the consequences of the event occurring are calculated.
- A number of different scenarios may be considered.

- Group risks into broad categories
- Develop plausible adverse scenario
- Calculate consequences of risk event occurring for each scenario
- Total costs calculated are taken as the financial cost of all risks
represented by the chosen scenario

**Stress testing** involves testing for weaknesses in a portfolio by subjecting
it to extreme market movements (or credit or liquidity events)

- Modelling of extreme changes and scenarios.
- Will be looking at correlations and volatilities which are observed to simultaneously increase during extreme events.
- Aim to identify weak areas by looking at effect of different combinations of correlations and volatilities number of different scenarios may be considered.
- Key area is constructing appropriate stress test scenarios.

- Identify "weak areas" in the portfolio and investigate effects of localised
stress by looking at the effect of different combinations of corrs and vols
- Gauge impact of major market turmoil affecting all model params,
while ensuring consistency between corrs while they are stressed

Stress and scenario testing can be combined to determine a **stress scenario**.

**Reverse stress testing** is the construction of a severe stress scenario that
just allows the firm to be able to continue to meet its business plan,
e.g. having insufficient capital to meet solvency reqs to cover its minimum
risk appetite.
The scenario may be extreme, but it must be plausible.

**Stochastic modelling** is a natural extension of stress testing but can be
complex and impractical in many cases.

- Variables are modelled using probability distributions.
- Dynamic interaction between variables.
- The result will be a distribution of outcomes.

Limitations in approach include

- Limit the time horizon (duration) of the model
- Limit the number of random variables
- Combine different stochastic runs deterministicly

## Aggregating risks

In many regulatory regimes, capital reqs are set in respect of an event
occurring in the next 12 months with a probability of 0.5%
(a 1 in 200 year event).
Individual risks need to be aggregated to allow for correlations and
interactions.
This can be achieved with

- Stochastic modelling, but this may be impractical
- Simple formulae if risk events are fully dependent (sum of individual
capital reqs) or fully independent (root sum of squares)
- Corr matrices
- Copulas - functions that take as inputs marginal cumulative dist functions
and output a joint cumulative dist function.
Different copulas are used to describe different degrees of dependence
between random variables such as in the tails of distributions

## Risk measures

Active measures for asset risk include historic tracking error and
forward looking tracking error.

Liability risks are commonly measured by carrying out an analysis of actual
vs expected experience.

Value at Risk (VaR) represents the maximum potential loss on a portfolio
over a given future period with a given degree of confidence.
VaR calcs may be based on assumptions such as a normal dist of returns.

## Risk portfolios / registers

An individual or company should establish a risk portfolio or register,
recording the impact and probability of each risk.

The risk portfolio can then be extended to indicate how the risk was dealt
with, e.g. accepted, transferred, managed (reduced), or rejected.

Retained risks should have the following details

- How much capital is req'd
- Control measures
- Reassessment of value and impact after controls
- Risk owner
- Board committee / senior manager with oversight of the risk
- Identification of concentrations of risk and related actions

## Risk reporting

Vital to ensure risk management process is effective

- Identify new risks
- Quantify impact of individual risks
- Determine appropriate control systems for specific risks
- Monitor effectiveness of existing control systems
- Assessing changes to risks faced
- Assessing interaction between risks
- Assisting with pricing, reserving, and determining capital reqs

Regular risk reporting is also helpful for

- Shareholders and potential shareholders: understand attractiveness of
investment
- Credit rating agencies: determine appropriate rating
- Regulators: areas which could require more scrutiny

Risk reporting should be consistent across the enterprise to optimise the
allocation of risk appetite and make the best use of diversification for
captial efficiency.

It is normal to report externally on risk by quantifying the capital reqs to
protect against ruin at a particular ruin probability.

The main issues facing providers of financial benefits in completing
assessments are

- Ruin prob expressed over a single year or whole run-off of business?
- Models with more than two random variables are impractical?
Corr matrix here instead?
- Interactions between risks
- Some risks, e.g. operational, are highly subjective
- Using past data to estimate future consequences needs to be undertaken
with caution, particularly for low frequency events.
