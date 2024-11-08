# Project Resilience Data Guidelines

Project Resilience is about decision-making optimization:
learn from past decisions in order to improve future decisions.

Let's define what a "decision" is and how historical decisions can be collected.

## Decision

A decision represents a choice made by a decision maker in a particular situation. This choice
can then be evaluated based on the outcomes that resulted from it.

### Context

A description of the **situation** the decision maker is in.
What information is available to the decision maker at the time of the decision?
Ideally it should include all the information that is relevant to the decision.
The context information should be general enough so that it can be compared to other contexts
and used by other decision makers.

### Actions

A description of the **decisions** made by the decision maker.
Based on the context information, what did the decision maker do?
The actions should be general enough to make them comparable to other actions made in different contexts
or by other decision makers.

### Outcomes

A description of the **results** of the decisions.
Based on the context and actions taken, what were the results? Good or bad?
The outcomes capture the metrics used to evaluate the decisions.
They must be directly attributable to the actions taken.
They represent the Key Performance Indicators (KPIs) that the decision makers is trying to optimize.
There is often a delay between when the decision is made and when the outcome is observed.

## Format and Features

### Tabular data

In its simplest form, the data can be represented as a table with rows and columns
where each row represents a decision and each column represents a feature of the decision:
context, actions or outcomes. A `.csv` file is a common format for this kind of data.

### Simulator

A simulator or calculator can be used to evaluate the outcomes of a decision maker's actions.
A simulator for instance puts the decision maker in a particular situation and lets them make decisions.
The simulator then evaluates the outcomes of these decisions, providing feedback to the decision maker.
This is a good way to learn from mistakes and discover better strategies.

### Reinforcement Learning environment

Reinforcement learning environments can be considered as simulators where an agent (the decision maker)
interacts with an environment (the context) by taking actions and receiving rewards (the outcomes).

## Data Sources

### Democratic accountability

Project Resilience provides a mechanism for incorporating democratically sourced knowledge
into a decision-making process. However, guaranteeing that sourced
knowledge is democratic is a much larger (and more challenging) civil problem. The concepts of
power imbalances and information asymmetry are fundamental to this challenge. Our hope is that, by
starting to formalize and decompose decision-making processes more clearly, it will become easier to
identify which components of the process should be prioritized for interrogation and modification,
toward the goal of a system with true democratic accountability.

### Data Privacy and Security

Data privacy and security are important considerations when collecting data on decisions.

Ideally the data should come be publicly available and come from reliable, trusted, scientific, ethical sources.

The data collected should not contain any personally identifiable information (PII).
If the data contains PII, it should be anonymized or aggregated to protect the privacy of individuals.

One mechanism for improving security is to allow users of the platform to rate sources,
data, and models from a quality, reliability, and security standpoint.
For instance following established approaches in cybersecurity, like in
[Intelligence source and information reliability rating](https://en.wikipedia.org/wiki/Intelligence_source_and_information_reliability)
systems.

## Tips

### Predictability

We need some a priori theory of why/how Actions could affect Outcomes,
and why we should expect prediction of Outcomes to be easier from
Context/Actions rather than from a Context alone. A human being should,
just by looking at the context / action data, be able to predict more or less
what the outcome should be. At least be able to reason about it.
Alternatively, a basic predictor model mapping Context/Actions to Outcomes
should be able to show that it uses the Actions to make predictions better
than with Context alone. This simple predictor model does not need to use
the full data or input/output spaces, it just needs to make it clear that
there's something there. Feature-importance plots can be useful for this.

### Time-series

Time series data is often used in decision-making optimization.
Times series come with their own set of challenges:
- lookback windows: how far back in time should we look to make a decision?
- time delays: how long does it take for an action to have an effect?
- averaging: should we average over time to smooth out noise?
- seasonality: are there patterns that repeat over time?

Predicting from time series data often requires a specific type of model, such as an LSTM or a Transformer.
Consider predicting the outcomes in an autoregressive way, forecasting one step ahead at a time and rolling
the predictions forward.

### Missing Data

To give the project the best chance of success, the amount of missing data should be minimal.

### Data Sufficiency

Data rows should cover variations of decisions sufficiently.

We need enough cases for our predictor to learn something about how Actions
affect Outcomes. If we have thousands of samples to begin with, that certainly
gives us a better shot. A quick-and-dirty check for correlations between
actions and outcomes could be used as a gating function, i.e., the
correlation matrix should not look like noise. If it looks like noise,
the project may be possible but hard.

Data requirement grows exponentially with number of outcome objectives.

Note though that it's fine starting with a minimum amount of data: more data can be collected over time
and used to trained better predictors.

### Generalization

The Context / Actions / Outcomes data should be general enough to be useful for other decision makers
and other situations. It's important to be able to be able to **compare** different decisions.

### Consistency

Same context and actions should result in similar outcomes. Contradicting
samples should be minimal. In other words, not too many rows with same
Context and Actions resulting in different Outcomes.

### Observability

It should be possible to observe the outcome of an action in a reasonable
amount of time (e.g., less than 3 months)

### Availability and Updates to the Data

As a rule of thumb, the number of new samples should be at least on the order
of the problem dimension, or (dim(A) + dim(C)) x (dim(O)). More important
than the number of new samples is which data is sampled: one sample in a
previously-unknown region of interest may be more useful than thousands
in a region we already know well or don't care about. So, if we control
which data is sampled, we don't need as much of it.

### Transparency/Accountability

Data should come from reliable, trusted, scientific, ethical sources.
(e.g. not blackboxes or Facebook surveys).

### Possible issues

It's most probable that context, actions and outcomes data is not readily available as a single dataset.

Most frequently actions are not collected. If they are, it's possible only "good" actions are recorded.
But "bad" actions are also important to collect in order to learn from them.

Another common issue is that outcomes are not directly attributable to actions.

It's also important to consider temporal aspects of the data.
For example, if the outcomes are not observed immediately after the actions are taken,
it's important to have a way to link the actions to the outcomes.
