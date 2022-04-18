Modelling is central to many of the chapters that follow. In particular:

- **Data** is one of the key inputs into any model.

    By data we are referring to information regarding policyholders or members.

    In some cases data relating to each policyholder or member will be used.

    In other cases it will be necessary to create model points, i.e. summarise the data.


- **Assumptions** such as mortality and interest rates are another key input into the modelling process.

    They should be set so that they are appropriate for the purpose.

- Models may be used to project how mortality and morbidity rates could change in future.

- **Expense** assumptions are often needed as inputs into cashflow models.

    In addition, modelling can be used in order to allocate expenses between different classes of business and different policies.

- Two of the main uses of models in actuarial work are **pricing** new products (or repricing old ones)

    and **valuing liabilities**.

## Producing a solution

*why models are often used to arrive at a solution to an actuarial problem*

There are various approaches that can be taken to produce the solution to an actuarial or financial problem.

The approach taken will be strongly driven by the purpose of the exercise and the nature of the problem.

Simple problems can have a simple solution that is arrived at by some straightforward mathematics ...

... for example calculating the yield on a fixed-interest asset, or the present value of a series of known cashflows.

**A model must capture the most important features of the actual solution.**

### The need to develop a model

However, most problems that require actuarial skills involve taking a view on uncertain future events.

It is possible to take a view on various parameters, such as;

- future economic conditions,
- future mortality rates,
- or the amount of business that a provider might write in future,

and produce a single answer that is appropriate in these best estimate conditions.

If this is done then **the communication of the solution to the client needs care** ...

... because of the uncertainties in the underlying assumptions.

In these circumstances the client is likely to wish to know the variability of the answer provided, should circumstances not be as estimated.

To assess the effects of varying the assumptions used in producing the answer, it is normally necessary to use an actuarial model of future events.

The variability of the answer might be assessed by carrying out:

- sensitivity analysis – varying individual assumptions and assessing the impact on the results
- scenario testing – changing many assumptions in combination, for example to look at the many assumptions that may change if the economy were to move into a recession.

The client must be made aware of the uncertainties underlying the model assumptions.

#### Modelling LI activities

- calculating provisions
- setting premium rates
- assessing reinsurance requirements
- estimating future investment returns
- estimating future mortality improvements
- estimating future discontinuance rates
- estimating future expense levels
- determining future capital requirements
- estimating future new business levels
- valuing guarantees and/or options.

### What is a model

> a cut-down, simplified version of reality that captures the essential features of a problem and aids understanding.

The final phrase in this definition recognises the importance of being able to communicate the results effectively.

Modelling requires a balance to be struck between

- realism - and hence complexity
- simplicity - for ease of application, verification and interpretation of results

### Finding a model

When faced with an actuarial or financial problem, there are various approaches to modelling:

- a commercial modelling product could be purchased
- an existing model could be reused, possibly after modification
- a new model could be developed.

The merits of each of these approaches will depend on the following:

- the level of accuracy required the "in-house" expertise available
- the number of times the model is to be used
- the desired flexibility of the model the cost of each option.

## Construction of an actuarial model

*key objective of a model and operational issues that need to be considered when models are being constructed*

- [2018 April Paper 2 Q3](40-2018-04-02.md#3)

Any model should be fit for the purpose for which it is being used.

This is particularly relevant when a model is being purchased from an external provider or when an existing model is being reused for a different purpose, possibly after modification.

Even with new purpose-built models, the potential for model error remains – a model that replicates past results may still prove unreliable in projecting future results.

### Operational issues

- Documentation

    The model being used should be adequately documented.

    This is so that the key assumptions and approximations made are understood and so that it can be run by other members of staff and improvements introduced over time.

- Communication

    The workings of the model should be easy to appreciate and communicate.

    The results should be displayed clearly.

- Dynamic

    The model should exhibit sensible joint behaviour of model variables.

    This means that the model needs to make an allowance for variables that are linked to each other.

    The relationship between them needs to have been modelled in an appropriate way.

    The **assumptions should also be consistent**, e.g. the assumed rate of investment return should be consistent with the assumed rate of inflation.

- Verifiable

    The outputs from the model should be capable of independent verification for reasonableness and should be communicable to those to whom advice will be given.

- Simple and quick to run

    The model, however, must not be overly complex ...

    ... so that either the results become difficult to interpret and communicate ...

    ... or the model becomes too long or expensive to run ...

    ... unless this is required by the purpose of the model.

    It is important to avoid the impression that everything can be modelled.

    Therefore we might not attempt to model every small detail of a scenario ...

    ... if reasonable approximations can be used instead.

- Capable of development and refinement

    The model should be capable of development and refinement.

    Nothing complex can be successfully designed and built in a single attempt.

- Flexible implementation

    A range of methods of implementation should be available to facilitate testing, parameterisation and focus of results.

- Appropriate time and period between cashflows

    The more frequently the cashflows are calculated the more reliable the output from the model ...

    ... although there is a danger of spurious accuracy.

    The less frequently the cashflows are calculated the faster the model can be run and results obtained.

    (time period between projected cashflows, eg monthly, quarterly or annually.)


### Deterministic vs Stochastic

- [2020 September Paper 1 Q8ii](40-2020-09-01.md#8-ii)

It is necessary to decide between deterministic and stochastic modelling, or a combination of the two.

A deterministic model is one where the parameter values are fixed at the outset of running the model and the result of running the model is a single outcome. Sensitivity analysis and scenario testing can then be carried out to assess the potential variability of the results.

A stochastic model estimates at least one of the parameters by assigning it a probability distribution. The model is run a large number of times, with the values of stochastic parameters being selected from their distributions on each run. The outcome is a range of values, giving an understanding of the likely distribution of outcomes.

#### Deterministic

Pros

- A deterministic model is more readily explicable to a non-technical audience, since the concept of variables as probability distributions is not easy to understand.
- It is clearer what economic scenarios have been tested.
- The model is usually cheaper and easier to design, and quicker to run.

Cons

- It requires thought as to the range of economic scenarios that should be tested.

    Since only a limited number of economic scenarios will be tested, there is a danger that certain scenarios, which could be particularly detrimental to the company, are not identified.

- Users can get "blinded by science" by complex models, assuming they must be working correctly, but without verifying or testing this.

#### Stochastic

Pros

- A stochastic model tests a wider range of economic scenarios.
- The programming is more complex and the run time longer, but the benefit is in the quality of the result.
- It does depend on the parameters that are used in any standard investment model.

The actuary needs to decide whether the increased amount of information that a stochastic valuation will provide justifies the significant additional computations needed.

Other important considerations are;

- the degree of spurious accuracy that may be introduced,
- the increased difficulty in interpreting and communicating the results,
- and the questionable accuracy of the distribution functions that are replacing the deterministic values.

Stochastic models are particularly important in assessing the impact of financial guarantees or to allow for investment mismatching risks.

The decision should balance the practical advantages of running a deterministic model with the increased amount of information produced by a stochastic model.

### Deterministic and Stochastic

In many cases the problem can be solved by a combination of stochastic and deterministic modelling.

Variables whose performance is unknown and where the risk associated with them is high might be modelled stochastically, while other variables can sensibly be modelled deterministically.

For these reasons, the stochastic approach is usually limited to the economic assumptions, with the demographic assumptions being modelled deterministically.

For example, a model for pricing an investment guarantee attached to a life insurance policy might use a stochastic investment model ...

... but would be unlikely to model fluctuations in mortality rates other than deterministically.

This is because it is normally self-evident which direction of movement in mortality rates would give rise to financial difficulties.

Another example relates to modelling general insurance claims experience.

It is usual to model claim frequency and the average size of each claim separately.

One approach would be to determine the number of claims stochastically and to use a deterministic average claim cost for each homogeneous group of policies.

Another approach would be to determine the claims amounts stochastically for each of the deterministic expected number of claims.

### Dynamism of the model

In all cases the dynamism of the model is vital.

By dynamic we mean that the asset and liability parts of the model and all the assumptions are programmed to interact as they would in "real life".

For example inflation and interest rates remain consistent under changing modelled economic conditions.

Rules need to be determined as to how the various features would interact in different circumstances.

For example,

- how life assurance bonus rates would vary with fixed-interest yields,
- how policy lapse rates would vary with economic conditions, or
- how unemployment rates would vary with economic conditions.

These interactions are usually much more important than the type of model.

Considerable actuarial judgement may be required in choosing and using the model and in setting the parameters and interactions between the different features.

Interactions are particularly important when the assets and the liabilities are being modelled together.

For example, economic conditions can affect both the investment return achieved on the assets and the value of the liabilities.

### Developing a model

- Specify the purpose and key features
- Collect, group, and modify data
- Choose the form of the model, identifying its parameters or variables
- ascribe values to the parameters using past experience and appropriate estimation techniques
- (choose a suitable density function for each of the variables to be modelled stochastically)
- (specify correlation between variables)
- construct a model based on the expected cashflows test the model in order to identify any build errors, and correct if necessary
- check that the goodness of fit is acceptable (and attempt to fit a different model if the first choice does not fit well)
- run the model using estimates of the values of variables in the future
- run the model several times to assess the sensitivity of the results to different parameter values.

    (run the model many times, each time using a random sample from the chosen density function(s))

    The model might also be run under different scenarios to test the robustness of the results to many parameters changing at the same time.

- (produce a summary of the results that shows the distribution of the modelled results after many simulations have been run, eg at various confidence levels.)

## Use of models for pricing

*the use of models for pricing a life insurance company's business*

A model could be developed to determine a premium or charging structure for a new or existing product that will meet an insurance company’s profit requirement.

A company will need a model to set the premiums when it first starts to sell a particular class of business.

It will also use the model to monitor the appropriateness of premium rates at regular intervals, in order to:

- check that the business is profitable
- check that rates are appropriate for all groups

    ie the rates are not inappropriately low or high for certain types of policyholder

- ensure the rates remain competitive.

### Using model points

- [2020 September Paper 1 Q8i](40-2020-09-01.md#8-i)

The underlying business being modelled will typically comprise a very wide range of different policies ...

... and these will need to be brought together into a manageable number of relatively homogeneous groups.

The groupings need to be made in a way that each policy in a group is expected to produce similar results when the model is run.

It is then sufficient for a representative single policy in each group to be run through the model, the result to be found, and for this result to be scaled up to give the result of the total set of policies in the group.

The representative single policy in a group is termed a "model point" and a set of such model points can then be used to represent the whole of the underlying business.

A model point needs to capture the most important characteristics of the group of policies it represents.

#### Practicalities

Need to consider whether full policy records are available.

Consider whether the actual policy data is in a format suitable for the model.

The model may not be set up to accept actual policy data.

It may be difficult to determine model points ...

... as the underlying business may comprise a very wide range of different policies ...

... which will be difficult to compile into appropriately homogeneous groups ...

... and judgement will be required, eg whether to differentiate by age, sum assured etc.

Formulating the model points incurs a cost and can be time consuming.

The groups formed need to be such that each policy in a group is expected to have similar results.

### Rate for discounting cashflows

For each model point, cashflows would be projected, allowing for reserving and solvency margin requirements, on the basis of a set of base values for the parameters in the model.

The net projected cashflows will then be discounted at a rate of interest, the risk discount rate.

This could be a rate that allows for:

- the return required by the company, and
- the level of statistical risk attaching to the cashflows under the particular contract

    ie their variation about the mean as represented by the cashflows themselves.

Statistical risk here is intended to encompass all types of risk, and comprises the model risk, parameter risk and random fluctuation risk.

Risk should be allowed for through the discount rate to the extent that allowance has not been made explicitly in valuing the cashflows ...

... eg attaching to a cashflow the probability of that cashflow arising.

The level of statistical risk could be assessed:

- in some situations, analytically – by considering the variances of the individual parameter values used
- by using sensitivity analysis, as described below, with deterministically assessed variations in the parameter values
- by using stochastic models for some, or all, of the parameter values and simulation by comparison with any available market data.

Alternatively, a stochastic discount rate could be used.

In theory, a different rate could be used for each component of the net cash flows to allow for the different levels of risk in each cash flow.

In practice, a single rate us used to reflect the average levels of risk.

### Competitive premiums

The premiums / charges resulting from the model need to be considered relative to the market. Consider

- Product design
- Distribution channels
- Profit requirements
- Size of the market
- Whether to go ahead with the product

The company actuary should also consider the appropriateness of the premiums / charges given the company's business strategy and capital requirements.

### Assessing the capital requirements and the return on capital

The net cashflows for the model points described in the section on pricing above can be grossed up for the expected new business ...

... and used to assess the amount of capital that will be required to write the product, either on a regulatory or an economic basis.

Any one-off development costs can be added, to the extent that they are not amortised (spread over a period) and included in the cashflows used.

This gives the total capital requirement ...

... and can be compared with the profits expected to emerge from the product ...

... to determine the expected return on that capital.

The design of the product or the profit requirement may need to be amended to ensure the required return on capital is achieved.

## Use of models for setting future financing strategies

*use of models for managing benefit schemes*

Similar modelling techniques are used by benefit schemes to determine future financing strategies.

- divide members into homogeneous groups, choose model points, etc.

The results of the model give the amount and timing of future contributions.

A potential financing strategy is determined, in terms of both the amount and timing of future contributions.

The cashflows from the existing assets and future contributions can be modelled, as can the liability cashflows, taking all the possible decrements into account.

It is acceptable for a scheme to have a deficit ...

... as long as the sponsor covenant is strong enough ...

... and there are sufficient assets to meet benefit outgo as it falls due.

## Use of models in risk management

Cashflow models are used in risk management to determine the amount of capital that it is necessary to hold to support the risks retained by a financial institution.

The various modelling approaches are discussed in [Chapter 27](27-accepting-risk.md).

As well as the full corporate model to assess capital requirements ...

... models of specific risks can be used to determine the extent of a risk event that will occur at a given probability ...

... even if a full stochastic model is too slow, too complex, or otherwise not used.

For example, a company that is targeting being able to withstand a 0.1% probability of ruin needs to know what equity market fall to test in a deterministic scenario.

A standard equity market stochastic model can be used and calibrated to historical performance of the market being considered.

By running the model several thousand times and ranking the results, the equity fall that gives the one in a thousand worst result can be found.

## Valuing provisions on an individual basis

*how liabilities are valued for regulatory purposes*

The valuation of a company's liabilities for regulatory purposes is likely to be carried out on each individual policy or member, rather than by using model points.

This is because the regulators want assurance that the company has sufficient provisions to meet the claims of all of the actual policyholders and risks being covered.

It is possible that an approximate approach using model points might lead to under-reserving.

## Use of models for pricing options and guarantees

In most cases the options and guarantees that give a provider of benefits on future financial events cause for concern are those that are dependent on future investment returns, or an investment value (yield or capital value) at some future point in time.

Because of the uncertainty, a stochastic investment model should be used to assess the provisions necessary for such guarantees.

The stochastic model can provide information on the likelihood of the option or guarantee applying together with the associated cost.

Examples of guarantees include:

- a savings product promising a minimum average future investment return of 4% per annum
- an annuity product providing annual increases at the lower of price inflation and 5%.

If future returns exceed a certain level, or if a value or index is above (or below) a fixed value at some future point, there will be no cost to the company.

But if future returns are below that level, there will be a cost, which increases as returns reduce.

Similarly, if the value or index is below (or above) the fixed value at the future point, depending on the precise nature of the guarantee, there could be a cost.

Hence a range of future investment scenarios should be tested.

## Sensitivity analysis

*benefits of carrying out sensitivity analyses to understand the potential variability of future experience*

### Reliability

### Understanding potential variability of experience

### Model error

There is a possibility of model error if the model developed is not appropriate for the financial products, schemes, contracts or transactions being modelled.

Checks of goodness of fit will be needed to assess the suitability of the model, but taking account of expected changes in experience into the future.

### Parameter error

The effect of mis-estimation of parameter values can also be investigated by carrying out a sensitivity analysis.

This involves assessing the effect on the output of the model of varying each of the parameter values.

When doing this, any correlation between different parameters should be allowed for.

In the case of a model used for pricing, the results from the sensitivity analysis will help to assess the margins that need to be incorporated into the parameter values.

For example, let’s consider the steps that an actuary might take if they identify that a product is unduly sensitive to withdrawal rates and mortality rates.

If the product profitability is overly sensitive to any factor, as noted above the results may indicate the need to redesign the product or increase the margins in the assumptions.

If the product is too sensitive to increasing withdrawal rates then a reduction in surrender values should be considered.

If the product is too sensitive to mortality then the reinsurance programme could be revised.

Alternatively, additional margins could be included in the pricing basis to reflect the increased risk.

In the case of models used to assess return on capital and profitability of existing business, the results will enable the actuary to quantify the effect of departures from the chosen parameter values when presenting the results of the model to the company.

## Model and parameter error

The results of a model are only as good as the model itself and the choice
of parameter values.

Sensitivity analysis is used to illustrate the potential variability of the
results and to identify the impact of mis-estimation of the parameter values.

Scenario testing involves changing many parameters in combination.

Goodness of fit tests help to reduce model error.

## Alternative ways of allowing for risk

Statistical risk associated with parameter values can be allowed for in the
discount rate and / or by including margins in the parameter values.

## Core reading example

*A unit-linked life assurance policy guarantees to pay a maturity value equal to the sum of premiums on the chosen maturity date, or the value of units allocated if greater.*

*At all other times the surrender value is based on the value of units.*

*Describe the steps involved in assessing the provision to be made for the cost of this guarantee.*

The steps involved are:

- Choose a stochastic asset model – a complex model gives better results but takes longer to run.
- Determine assumptions – particularly unit growth rate mean and volatility.

    It is not sufficient to simply say "determine assumptions": we need to give examples of those that will have the greatest impact on whether the guarantee comes into effect or not.

    In this case it is the unit growth rate that is the primary driver.

- Determine consistent deterministic assumptions for mortality and surrender rates and future expenses.
- Consider dynamic links between assumptions – eg lapse rates to unit values.
- Choose a time period – probably annual for efficient running.
- Determine appropriate model points for the portfolio.

    If there were sufficient marks on offer, we could expand to discuss how to choose model points – as was discussed earlier in this chapter.

- The model will project the unit values to maturity, allowing for future premiums and all decrements.
- This will be done for a large number of randomly generated investment scenarios – say between 1,000 and 5,000.
- For each scenario and each model point, the projected unit value will be compared with the guaranteed maturity value, and the cost for that particular scenario and model point determined.
- The projected costs are discounted to the present, scaled up by the appropriate factors and summed across all model points.

    The scaling up is performed in order to represent the actual volume of business.

- The average across all scenarios is the expected cost of the guarantee.
- The variability should be assessed by looking at the quartiles and 5th / 95th percentiles, when the results are ranked.
- For reserving purposes, an appropriate ruin probability needs to be chosen. Perhaps 1 in 100, in which case the reserve is the 99th percentile.
