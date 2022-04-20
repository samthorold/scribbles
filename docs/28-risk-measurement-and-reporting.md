## Risk quantification

For all risks, the probability of occurrence (**frequency**) and expected loss (**severity**) need to be assessed.

These are normally treated as random variables in models.

Risks are commonly assessed using simple scales which rate frequency and severity from low to high.

The product of frequency and severity scales represents the overall score for that risk, enabling them to be ranked.

The assessment would be done with and without controls, to assess their efficiency.

The assessment may be recorded in a risk register.

It is difficult to model low frequency events due to a lack of data.

Operational risk in particular can be difficult to quantify.

Approaches include;

- Broadbrush addition to other risks (for capital requirements)
- Scenario analysis

### Subjective assessment

A common approach to risk assessment used by financial institutions is to extend the risk identification "brainstorming" approach covered in Chapter 25 so that the probability and cost or impact of the risk event are each estimated.

These estimates would be on a five-point scale (or three-point scale).

For a five-point scale the assessments would be based on: 5 = high, 4 = medium-high, 3 = medium, 2 = medium-low, 1 = low.

The product of the probability assessment and the impact assessment gives a scale of 1 to 25 (or 1 to 9 for the three-point scale) as an assessment of the risk.

This risk-scoring approach provides a method for ranking risk events.

The assessment would be carried out with and without possible risk controls, to generate a figure for the effectiveness of proposed controls.

This will enable the efficiency of risk controls to be assessed against their cost.

### Using a model

A risk event may be assessed by developing a model in which the probability of loss and the amount of loss are both treated as a random variables.

To use a mathematical model, the first need is to assign a distribution both to the probability of the risk event occurring, and also to the loss if the event occurs.

For some risks occurrence isn't an on/off event, but to quantify the risk simply it is necessary to define the event.

For example, investing in equities carries market risk.

The firm could set an event as a 25% fall in equity price over a year and then research historic data to determine a probability distribution of this event.

The choice of parameter for the fall in the equity market would need to be consistent with the firm's risk appetite.

Another approach would be to set the frequency of the loss event in advance, and to use this to determine the size of the parameter.

For example, a 0.5% probability of an equity fall might involve a market movement of 40%.

**All the considerations described in Chapter 17 on Modelling need to be taken into account in designing an appropriate model** - in particular, the decision as to whether a stochastic or deterministic model is appropriate.

Obtaining the data to parameterise the model will be a crucial issue, and the availability of data may influence the decision as to what, or whether, a model is used.

This is particularly important when rare events are considered.

Even in areas where there is a large volume of data, such as mortality, where developed countries have been conducting censuses for well over 100 years, there is a need to consider a pandemic event.

Here one has to go back almost 100 years to the 1919 influenza epidemic, and then realise that the effects need to be adjusted for improvements in medical science (antibiotics, antivirals), lifestyle (population movement) and general population health.

### Operational risk

Operational risk is one of the most difficult to quantify.

There are so many operational risk events that can affect a firm that to quantify each would be impractical, and because the events are rare and often independent each would have little impact on the aggregate risk exposure of the firm.

!!! note "Not all operational risks are rare"

    Events relating to administration and processing errors or systems downtime may occur relatively frequently but would typically have relatively low severity.

    The more difficult operational risks to quantify are those that have low likelihood, such as dealing with the impact of external events eg terrorism or flooding.

    However, as noted above, even the more frequent operational events can be difficult to assess in totality, as there are normally so many possible processes, people and systems where failures could occur.

    There are two approaches that are typically used to assess or allow for operational risk with an organisation;

    - a broadbrush approach that does not perform any detailed analysis
    - scenario analysis.

One approach which has been adopted in the banking sector is simply to add a percentage uplift to the total aggregated risks other than operational risks.

This approach is also followed in the European Solvency II standard formula model for insurers.

This relates to the assessment of the amount of capital that is required to be held against adverse outcomes in relation to the risks, and is covered further in a later chapter.

Another approach is to use the technique of scenario analysis described in the next section.

This could involve dividing the possible operational risks into perhaps 10 - 15 categories and, for each category, assessing the cost of a plausible adverse scenario.

For example, the categories might include;

- fraud
- loss of key personnel
- mis-selling of financial products
- calculation error in the computer system
- loss of business premises
- loss of company e-mail access for 72 hours.

## Evaluation of risks

- [2018 April Paper 2 Q4](40-2018-04-02.md#4)

### Scenario analysis

[2020 September Paper 1 Q5ii](40-2020-09-01.md#5-ii)

#### Pros

Scenario analysis is a deterministic method of evaluating risk.

It is useful where it is difficult to fit full probability distributions to risk events.

Such as when there are insufficient data points to create a probability distribution ...

... given that [X events] are relatively rare.

#### The modelling process

- A scenario will be developed [for each region in which] the insurer operates.
- The management team and other experts can help determine the scenarios.
- The scenarios will be tested, with the results providing information on ...
- ... the impact on claim costs ...
- ... but not the likelihood of a claim arising.

---

- For each group of risks a representative plausible scenario is developed.
- For each scenario the consequences of the event occurring are calculated.
- A number of different scenarios may be considered.

Process

- Group risks into broad categories
- Develop plausible adverse scenario
- Calculate consequences of risk event occurring for each scenario
- Total costs calculated are taken as the financial cost of all risks represented by the chosen scenario

### Stress testing

involves testing for weaknesses in a portfolio by subjecting it to extreme market movements (or credit or liquidity events)

- Modelling of extreme changes and scenarios.
- Will be looking at correlations and volatilities which are observed to simultaneously increase during extreme events.
- Aim to identify weak areas by looking at effect of different combinations of correlations and volatilities number of different scenarios may be considered.
- Key area is constructing appropriate stress test scenarios.

- Identify "weak areas" in the portfolio and investigate effects of localised stress by looking at the effect of different combinations of corrs and vols
- Gauge impact of major market turmoil affecting all model params, while ensuring consistency between corrs while they are stressed

### Stress scenario

Stress and scenario testing can be combined to determine a **stress scenario**.

### Reverse stress testing

is the construction of a severe stress scenario that just allows the firm to be able to continue to meet its business plan, e.g. having insufficient capital to meet solvency reqs to cover its minimum risk appetite.

The scenario may be extreme, but it must be plausible.

### Stochastic modelling

is a natural extension of stress testing but can be complex and impractical in many cases.

- Variables are modelled using probability distributions.
- Dynamic interaction between variables.
- The result will be a distribution of outcomes.

Limitations in approach include

- Limit the time horizon (duration) of the model
- Limit the number of random variables
- Combine different stochastic runs deterministicly

## Aggregating risks

In many regulatory regimes, capital reqs are set in respect of an event occurring in the next 12 months with a probability of 0.5% (a 1 in 200 year event).

Individual risks need to be aggregated to allow for correlations and interactions.

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

Active measures for asset risk include historic tracking error and forward looking tracking error.

Liability risks are commonly measured by carrying out an analysis of actual vs expected experience.

Value at Risk (VaR) represents the maximum potential loss on a portfolio over a given future period with a given degree of confidence.

VaR calcs may be based on assumptions such as a normal dist of returns.

## Risk portfolios / registers

An individual or company should establish a risk portfolio or register, recording the impact and probability of each risk.

The risk portfolio can then be extended to indicate how the risk was dealt with, e.g. accepted, transferred, managed (reduced), or rejected.

Retained risks should have the following details

- How much capital is req'd
- Control measures
- Reassessment of value and impact after controls
- Risk owner
- Board committee / senior manager with oversight of the risk
- Identification of concentrations of risk and related actions

## Risk reporting

[2020 April Paper 1 Q2](40-2020-04-01.md#2)

FRAUD | CRIME
---|---
Financing (appropriate price, reserves, capital requirements) | Changes over time
Rating agencies | Regulator
Attractiveness to investors | Interactions
Understand better (risks and their financial impact) | Monitor effectiveness of controls
Determine appropriate control systems | Emerging risk identification

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
