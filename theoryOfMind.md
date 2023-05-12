What makes a significant digit significant?

In school, it was my experience they taught us trailing 0's were not significant.
However, this is wrong.

Consider a ruler measuring some distance, on which the smallest marking is a centimeter. Based on the marking, one could go farther and estimate down to the millimeter, or maybe if you have a magnifying glass and some confidence, you could even estimate down to a 10th of a millimeter level. Both of which could be 0's and still significant. So, depending on the operator the ruler has a resolution down to maybe a millimeter or submillimeter; though in most scientific process you would probably restrict yourself to the millimeter level even though making an estimate for the sub millimeter might convey additional information if you have any confidence about it: mostly because you don't want to come off as more confident than you are.

The true purpose of significant digits is to convey an estimate of the order of magnitude of measurement error.

Scientific notation might represent this as 2.600 * 10^2 millimters or 2.600E2

You (or maybe more realistically 10 seperate people since you will probably mentally anchor to your first measurement making further measurements correlated) measure that distance 10 times, and each time come up with a slightly different distance, clustered around the true distance with some variance that corresponds to some error bound.

When doing calculations with scientific formulas, or computations with a computer model, you have to propagate the error through the calculations.

variance is one measure of error then, and a common one, often represented as standard deviation; but far from foolproof. typically measured

Once you have a measurement, in order to accurately propagate error forward in the general case, you have to assume that the error corresponds to some probability distribution
https://en.wikipedia.org/wiki/Convolution_of_probability_distributions



what are the most fundamental abstractions

nodes - sets

and

edges - categories

which can be related to one another by

hypergraphs

geometry (manifolds: geometry gets more fundamental when localized? taken to limit?)

logics, statements, axioms (how do they play in)

https://en.wikipedia.org/wiki/Second-order_logic

neural net weight space as an approximation of error space

error propagation ~ function approximation

vs compression
