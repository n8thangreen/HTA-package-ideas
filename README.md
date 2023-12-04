# HTA package ideas

This is a curated, living document of potential solutions to problems in HTA and health economics modelling in R.

## Challenge areas
We will roughly categorise them to fit within four broad challenge areas. These are:

1.	Reproducibility in HTA
2.	Reading, cleaning, and storing HTA data
3.	Reporting HTA results
4.	HTA model robustness
5.	HTA functionality and workflows 

## Project ideas
Example projects within these themes are:

* Extending existing packages
  *  e.g. extended multistate model packages (`msm`, `mstate`) to explicitly incorporate cost-effectiveness analysis.
* Better handling of sensitivity analysis data from multiple runs
* Improving visualisation of economic evaluation
  * input data
  * summary statistics
  * uncertainties
* Improving ease of use
  * e.g. simply by adding an extra level of abstraction to existing R package so that new higher-level functions can be exploited by practitioners and policymakers
* Linking R and BUGS or Stan for HTA
* Automate reporting a CHEERS checklist
  * e.g. [using Roxygen comments](https://github.com/n8thangreen/rocletCHEERS).
* Provides a class for maintaining cost-effectiveness related metadata
  * [Cost user-defined types](https://github.com/n8thangreen/ce_unit)
  * [QALY user-defined types](https://github.com/Health-Economics-in-R/QALY)
* Tools for setting up an HTA project in R
  * e.g. like `devtools`
* Convert an HTA MS Excel file into an R program.
  * [Decision tree model](https://healtheconomicshackathon.github.io/xlerate/)
* Scrape and export data from the web and files
  * [Take a pdf table of input data and wrangle it into a form for HTA](https://github.com/HealthEconomicsDataDive/pdf2data).
* Exploit new AI models
  * ChatGPT for automatic systematic literature review (SLR)
  * Data cleaning
* Easily convert from scripts to packages  
* Automatically commenting HTA code
* Automatically adding tests to HTA code
* A framework for HTA model testing
  * [Like `testthat`](https://github.com/n8thangreen/testhta) 

## Suggestions
Please [create an Issue](https://github.com/n8thangreen/HTA-package-ideas/issues) with any ideas or input to this list.
