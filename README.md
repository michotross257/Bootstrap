# Bootstrap Resampling

Author: Michael Trossbach

Contact: mptrossbach@gmail.com

## Overview
Bootstrap resampling is random sampling with replacement from a sample to approximate the population value of a statistic. In this experiment, the statistic that I am trying to approximate is the mean. I resampled using different sample sizes (i.e. the size of the sample randomly chosen from the population) and tested the effect of how many times I bootstrap resample.

## Questions
1. Does bootstrap resampling of a statistic better approximate the population value the more you resample?
2. What is the effect on the bootstrap error (i.e. the absolute difference between the population mean and the bootstrap mean) of increasing the sample size?

## Results
1. No, the population value of a statistic (e.g. mean) is not reliably better approximated the more you resample using the bootstrap resampling technique.
2. As one would expect, increasing the sample size results in lower bootstrap errors overall. This conclusion is not interesting. The appeal of bootstrapping is that the population value of a statistic can be reasonably approximated with little data, meaning the sample is small.

**Sample Size**: 5% of the population
![alt text](https://raw.githubusercontent.com/michotross257/bootstrap-resampling/master/images/eval_plot_05.jpg)
**Sample Size**: 10% of the population
![alt text](https://raw.githubusercontent.com/michotross257/bootstrap-resampling/master/images/eval_plot_10.jpg)
**Sample Size**: 20% of the population
![alt text](https://raw.githubusercontent.com/michotross257/bootstrap-resampling/master/images/eval_plot_20.jpg)
**Sample Size**: 40% of the population
![alt text](https://raw.githubusercontent.com/michotross257/bootstrap-resampling/master/images/eval_plot_40.jpg)

## Improvements
I am not a statistics expert. If I've made any errors here please let me know by creating an issue.
