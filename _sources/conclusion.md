(ch:conclusion)=
Conclusion
==========

The purpose of this book is to explain how uncertainty
quantification can be accurately and reliably achieved for engineering
systems, when the available data is of poor quality or if a limited
quantity of data is available.
The computational techniques required to perform this simulation in a feasible
computational time are of particular importance.
The developed uncertainty quantification techniques have been discussed in the
context of reliability engineering, however the potential applications of these
techniques are much wider than this.

Chapter {ref}`ch:uncertainty_models` presented a review of uncertainty
models which model joint uncertainty of unknown variables (e.g.
*generative* probabilistic models, convex sets and probability boxes).
Techniques for general computation with such models are described. The
construction of such models with or without experimental data was
discussed.

Chapter {ref}`ch:machine_learning` discussed techniques to create
uncertainty models, where the uncertainty in one variable is dependent
on the uncertainty in other variables. These models include Bayesian
regression, neural networks, Gaussian processes and interval predictor
models. Techniques to validate the performance of these models is
discussed.

Chapter {ref}`ch:reliability_analysis` presented a state of the art review
of techniques for reliability analysis, where the probability of failure
of a system under the influence of uncertainty is calculated.
Reliability measures were discussed for probabilistic models, convex set
models and imprecise probability models. Efficient computational
techniques were discussed for performing the simulation required to
calculate the reliability of expensive black-box models of systems.

## Unanswered questions

The field of uncertainty quantification is still developing, and undoubtably
many future interesting applications of uncertainty quantification are yet to be
made.

There are several areas where development is likely to focus in future:

- Further application of the latest developments in neural networks and Gaussian
processes to engineering.
- Algorithms amenable to massive data sets, particularly algorithms involving
imprecise probabilities.
- Further development and application of imprecise probability models in some
form, though they may not be labelled explicitly as such.

## What should I read next?

After reading this book and being presented with an overview of the field,
engineers may be searching for further reading material.
A useful recommendation is largely dependent on the interests of the reader.
Readers with a general interest in statistics may benefit from reading textbooks
such as {cite}`friedman2001elements`, {cite}`gelman2013bayesian`,
{cite}`tarantola2005inverse` and {cite}`jaynes2003probability`.
Readers wishing to understand more about engineering applications of uncertainty
should refer to {cite}`sundararajan2012probabilistic` or
{cite}`melchers2018structural` (many similar books exist).
For those in industry, whitepapers from government organisations may also be
informative.
For those beginning a postgradutate programme of study, I highly recommend
reading the original papers for techniques of interest and then reviewing the
code of open source software libraries such as {cite}`patelliopencossan`.
