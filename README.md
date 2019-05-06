# Statistical Inference Course Project 1

**Jeffrey M. Hunter**

May 6, 2019

The project consists of two parts.

#### Part 1: Simulation Exercise Instructions

Investigate an exponential distribution in R and compare it with the Central
Limit Theorem (CLM). The exponential distribution will be simulated in R with
`rexp(n, lambda)` where lambda is the rate parameter.

The mean of the exponential distribution is `1/lambda` and the standard
deviation is also `1/lambda`. Lambda will be set to `lambda = 0.2` for all of
the simulations. An investigation will be performed on the distribution of
averages of 40 exponentials for one thousand simulations.

Illustrate via simulation and associated explanatory text the properties of the
distribution of the mean of 40 exponentials.

Use RStudio and knitr to create a report in PDF format to:

1. Show the sample mean and compare it to the theoretical mean of the
   distribution.

1. Show how variable the sample is (via variance) and compare it to the
   theoretical variance of the distribution.

1. Show that the distribution is approximately normal.

The PDF report should be no more than 3 pages with 3 pages of supporting
appendix material if needed (code, figures, etcetera).

In order to address the requirements above and make it easy for reviewers to
clearly identify and evaluate the work, the project report will be structured 
using the following headings:

* **Title**: provide an appropriate title and include the author's name

* **Overview**: In a few (2-3) sentences, explain what is going to be reported
    on.

* **Simulations**: Include English explanations of the simulations you ran, with
    the accompanying R code. Your explanations should make clear
    what the R code accomplishes.

* **Sample Mean versus Theoretical Mean**: Include figures with titles. In the
    figures, highlight the means you are comparing. Include text that explains the
  figures and what is shown on them, and provides appropriate numbers.

* **Sample Variance versus Theoretical Variance**: Include figures
    (output from R) with titles. Highlight the variances you are comparing.
    Include text that explains your understanding of the differences of the
    variances.

* **Distribution**: Via figures and text, explain how one can tell the
distribution is approximately normal.

#### Part 2: Basic Inferential Data Analysis Instructions

In the second portion of the project, analyze the `ToothGrowth` data in the
R datasets package.

1. Load the ToothGrowth data and perform some basic exploratory data analyses

1. Provide a basic summary of the data.

1. Use confidence intervals and/or hypothesis tests to compare tooth growth by
   supp and dose. (Only use the techniques from class, even if there's other
   approaches worth considering)

1. State your conclusions and the assumptions needed for your conclusions.

### Repository Contents

This repository contains the following:

#### Part 1

* **exp-distrib-simulation.Rmd**: exploratory data analysis of the CLT in R Markdown format
* **exp-distrib-simulation.html**: exploratory data analysis of the CLT in HTML format created by knitr
* **exp-distrib-simulation.pdf**: exploratory data analysis of the CLT in PDF format created by knitr
* **/figures**: directory containing figures from *exp-distrib-simulation* in PNG format

#### Part 2

* **tooth-growth-analysis.Rmd**: analysis of ToothGrowth dataset in R Markdown format
* **tooth-growth-analysis.html**: analysis of ToothGrowth dataset in HTML format created by knitr
* **/figures**: directory containing figures from tooth_growth in png format

### Review Criteria

* Did you show where the distribution is centered at and compare it to the
  theoretical center of the distribution?

* Did you show how variable it is and compare it to the theoretical variance of
  the distribution?

* Did you perform an exploratory data analysis of at least a single plot or
  table highlighting basic features of the data?

* Did the student perform some relevant confidence intervals and/or tests?

* Were the results of the tests and/or intervals interpreted in the context of
  the problem correctly?

* Did the student describe the assumptions needed for their conclusions?
