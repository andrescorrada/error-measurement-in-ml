error-measurement-in-ml
=======================

A monograph on how to measure the errors of machine learning algorithms when no ground truth is available.

## Why?

Data is plentiful. Machine algorithms are plentiful. Is it possible to exploit the combination of both to carry out an "error correcting" algorithm on the output of recognizers, labelers, rankers, recommenders, etc.? Or devise algorithms that can measure the error in situations where you don't have any ground truth to verify what the correct answer is?

## How?

By estimating a statistic of ground truth, not ground truth itself. You can set-up what is a multi-variable polynomial set of equations on the statistic that you want to estimate. When you have enough algorithmic outputs to compare, on enough data, you can deduce the error rates of the algorithms and even a little something about the data you are using to carry out your measurement.

&copy; Andres Corrada-Emmanuel, 2014