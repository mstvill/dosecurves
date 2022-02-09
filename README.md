# dosecurves
Repository for "Assessing opioid use disorder treatments in trials subject to non-adherence via a functional generalized linear mixed effects model" by St. Ville, Bergen, Baurley, Bible, and McMahan

This repository contains the necessary code to implement the proposed methodology and contains files that creates a fake 
buprenorphine maintenance treatment clinical trials data set (Create_Fake_Data_Set.txt), which is saved as (opioid_data.csv), 
to mimic the buprenorphine maintence treatment efficacy and safety clinical trials dataset, and the necessary data structuring code,
and runs a complete analysis of the data set (Data_Analysis.txt).

For the logistic link, it is necessary to install the BayesLogit package in R. This package is no longer available
for download from CRAN, so we have provided the source files (BayesLogit_0.6.tar) for installation.
